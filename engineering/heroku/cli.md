## Heroku CLI

Use `--app=app-staging` or `--app=app-production` for staging and production environments respectively.

* Connect to rails console ```heroku run console --app=app-staging```
* Check logs ```heroku logs -t --app=app-staging```
* Run a rake task (e.g. migrate database) ```heroku run rake db:migrate --app=app-staging```
