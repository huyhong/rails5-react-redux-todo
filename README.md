# TodoMVC App (Rails 5 API + React + Redux)

## General

This application is simple TodoMVC-style app (forked from https://github.com/kogoto/rails5-react-redux-todo with simple word/phrase translations to English). It is meant to be a boilerplate application to build off of, using Rails 5 API alongside React + Redux for the frontend (via create-react-app).

## Instructions

We'll be using this repo as the basis for a few exercises when you come in.

You will need to fork this repo and clone it to your local dev machine, ensure the environment works properly, check to make sure everything starts up properly, and get comfortable with the code base. Feel free to modify the code base as needed to suit your preferences/style.

## Setup

Fork and clone the app:

```bash
$ git clone https://github.com/huyhong/rails5-react-redux-todo.git
(^ this should be your fork's url)
$ cd rails5-react-redux-todo
```

For Ruby deps (using Ruby 2.3.1 and up) and Rails:

```bash
$ bundle install --path vendor/bundle
$ rails db:migrate
```

For Node deps (using Node 6.x and up) and Webpack:

```bash
$ cd ./client
$ npm install
```

## Development

In one console window, run the Rails dev server (API hosted on port `8000`):

```bash
$ rails s -p 8000
=> Booting Puma
=> Rails 5.0.0 application starting in development on http://localhost:8000
=> Run `rails server -h` for more startup options
=> Puma starting in single mode...
```

In another terminal window, run the Webpack server (client hosted on port `3000`):

```bash
$ cd ./client
$ npm start
=> Compiled successfully!
=> The app is running at http://localhost:3000/
```

Go to (http://localhost:3000) to see the running app.
