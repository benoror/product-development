# Product Development Guidelines

General styleguides &amp; documentation for modern product development

---

# Engineering

## 🏗 DevOps

### Git

- [PRs (Pull Requests)](engineering/git/PRs.md)
- [Semantic Commits](engineering/git/commits.md)
- [Git Workflow (basic)](https://github.com/benoror/guides/blob/master/git/workflow.md)
- [Gitflow: A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Git Tools - Rewriting History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)

### Heroku

- [CLI](engineering/heroku/cli.md)
- [Postgres](engineering/heroku/postgres.md)
- [Rollbacks](https://blog.heroku.com/releases-and-rollbacks#rollbacks)

## ⚙️ Backend

### Ruby (on Rails)

- [Ruby Styleguide](engineering/style.md)
  - [Rubocop Styleguide](https://github.com/rubocop-hq/ruby-style-guide)

#### Best Practices & Design Patterns

##### Controllers

- Memoizing
  - [Explaining the rationale behind using memoized helper methods for controller resources](https://gist.github.com/bloudermilk/8345597)
  - [The Basics of Ruby Memoization](http://gavinmiller.io/2013/basics-of-ruby-memoization/)
  - [Rails best practices: Use memoization](https://rails-bestpractices.com/posts/2010/11/22/use-memoization/)
  - [4 Simple Memoization Patterns in Ruby (And One Gem)](https://www.justinweiss.com/articles/4-simple-memoization-patterns-in-ruby-and-one-gem/)
    
##### Service Objects

- [A simple explanation of Service Objects for Ruby on Rails](https://medium.freecodecamp.org/service-objects-explained-simply-for-ruby-on-rails-5-a8cc42a5441f)
  
##### Testing

  - [How to configure RSpec in Ruby on Rails](https://blog.eq8.eu/article/junior-developer-set-up-rails-with-rspec-factorybot-database-cleaner.html)

##### Migrations

- **_Data_** Migrations
  - [Data Migrations in Rails](https://thoughtbot.com/blog/data-migrations-in-rails)
  - [Migrating Data - Rails Migrations or a Rake Task?
](https://www.urbanbound.com/make/migrating-data-rails-migrations-or-a-rake-task)

### REST APIs

#### Specifications

- [JSON:API](https://jsonapi.org/)

## 🖼 Frontend

### Javascript
  
#### HTML & CSS

- [Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
  - [Grid by Example](https://gridbyexample.com/examples/)
  - [Learn CSS Grid](https://learncssgrid.com/)

#### React

- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Presentational and Container Components (Dan Abramov)](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
  - [Example Gist (Michael Chan)](https://gist.github.com/chantastic/fc9e3853464dffdb1e3c)
  - [Usage with Redux](https://redux.js.org/basics/usage-with-react#presentational-and-container-components)
- [React Cheat Sheet](https://reactcheatsheet.com/)
- [React Patterns](https://reactpatterns.com/)

##### CSS-Modules

- [CSS Modules](https://github.com/css-modules/css-modules)
- [CRA: Adding CSS Modules](https://facebook.github.io/create-react-app/docs/adding-a-css-modules-stylesheet)
- [Getting started with CSS modules in React](https://blog.pusher.com/css-modules-react/)
- [What are CSS Modules and why do we need them?](https://css-tricks.com/css-modules-part-1-need/)
- [What are CSS Modules? A visual introduction](https://www.javascriptstuff.com/what-are-css-modules/)

##### State Management

- Hooks & Context API
  - [Application State Management with React](https://kentcdodds.com/blog/application-state-management-with-react)
  - [State Management with React Hooks and Context API in 10 lines of code!
](https://medium.com/simply/state-management-with-react-hooks-and-context-api-at-10-lines-of-code-baf6be8302c)
- [MobX](https://mobx.js.org/intro/overview.html)
  - [Ten minute introduction to MobX and React](https://mobx.js.org/getting-started.html)
  - [MobX: Concepts & Principles](https://mobx.js.org/intro/concepts.html)
  - [Video: Preethi Kasireddy - MobX vs Redux: Comparing the Opposing Paradigms - React Conf 2017](https://www.youtube.com/watch?v=76FRrbY18Bs)
[Redux](https://redux.js.org/introduction/motivation)
- [Redux (react-redux)](https://react-redux.js.org/introduction/why-use-react-redux)
  - [Leveling Up with React: Redux](https://css-tricks.com/learning-react-redux/)
  - [React Redux Tutorial for Beginners: The Definitive Guide (2019)](https://www.valentinog.com/blog/redux/)
  - [Redux and React: An Introduction](http://jakesidsmith.com/blog/post/2017-11-18-redux-and-react-an-introduction/)
  - [What Does Redux Do? (and when should you use it?)](https://daveceddia.com/what-does-redux-do/)
  - [How Redux Works: A Counter-Example](https://daveceddia.com/how-does-redux-work/)
  - [Redux Architecture and Best Practices](https://github.com/markerikson/react-redux-links/blob/master/redux-architecture.md)
  - [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links)
  - [JSON:API resources for React + Redux](https://gist.github.com/benoror/9988c235d5cb53acfcf57ea668bd95cb)

## ⭐️ Misc

- [DockYard Styleguides](https://github.com/DockYard/styleguides)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Tractical Guides](https://github.com/benoror/guides)

## 📚 Books

### Technical

- [Refactoring (Martin Fowler)](https://refactoring.com/)
- [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer)
- [Domain-Driven Design (Eric Evans)](https://domainlanguage.com/ddd/)
- [Domain-Driven Design Distilled](https://www.oreilly.com/library/view/domain-driven-design-distilled/9780134434964/)
- [Patterns of Enterprise Application Architecture (Martin Fowler)](https://www.martinfowler.com/books/eaa.html)
- [JavaScript: The Good Parts (Douglas Crockford)](http://shop.oreilly.com/product/9780596517748.do)

### Non-technical

- [Inspired: How to Create Tech Products Customers Love](https://svpg.com/inspired-how-to-create-products-customers-love/)
