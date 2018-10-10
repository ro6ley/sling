![bitmoji](https://render.bitstrips.com/v2/cpanel/9e8f7839-cd6d-4222-82fe-4a31d013e2b1-5dd5ae52-a074-4fb4-af60-8374a83964f5-v1.png?transparent=1&palette=1&width=246)

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
