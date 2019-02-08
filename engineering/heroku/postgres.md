## Copy PRODUCTION Database to STAGING

### Using `pg:backups`

Restoring the db is way faster than pg:pull or pg:copy.

1. ```heroku pg:backups restore `heroku pg:backups public-url --app app-production` HEROKU_POSTGRESQL_BRONZE_URL --app app-staging```

2. `heroku run rake db:migrate --app app-staging`

### Using `pg:copy`

1. `heroku pg:copy app-production::DATABASE_URL DATABASE_URL --app app-staging`

2. `heroku run rake db:migrate --app app-staging`

## Copy PRODUCTION Database to DEVELOPMENT (local)

### Using `pg:pull` (Faster way, latest snapshot)

1. `dropdb app_development`
2. `heroku pg:pull DATABASE_URL app_development --app app-production`

### Using `pg:backups` (Slower way, specific backup)

To be able to restore production DB into local environment, just local db must exist first.

1. `dropdb app_development`
2. `createdb app_development`
3. Get backup id (`heroku pg:backups --app app-production`) and then:
```
heroku pg:backups:download backupId --app app-production
```
4. Load dump into DB.
```
pg_restore --verbose --clean --no-acl --no-owner -h localhost -U username -d app_development latest.dump
```
