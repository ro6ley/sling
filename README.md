## About

Sling is a Slack clone built with Phoenix and React. 

## Getting started

To run the project locally:

#### Running the Phoenix app

Download dependencies

```
cd api
mix deps.get
```

Edit the database connection config in `/config/dev.exs` or `config/dev.secret.exs`
with your postgres user info if needed

Create and migrate the database

```
mix ecto.create ecto.migrate
```

Start the server

```
mix phoenix.server
```

#### Running the React app

Install [Yarn](https://github.com/yarnpkg/yarn)

Install dependencies

```
cd web
yarn
```

Copy `.env.example` contents into to a new `.env` file

Start the dev server

```
npm start
```
