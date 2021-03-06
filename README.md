# ruby-directory-sync-example

An example Sinatra application demonstrating how Directory Sync works with WorkOS and Ruby.

## Clone and Install

Clone this repo and install dependencies:

```sh
git clone git@github.com:workos-inc/ruby-directory-sync-example.git && cd ruby-directory-sync-example && bundle install
```

## Configure your environment

1. Grab your [API Key](https://dashboard.workos.com/api-keys).
2. Run `cp .env.example .env` and add your API key. The `workos` gem will read your API key from the ENV variable `WORKOS_API_KEY`. You may also set the API key yourself by adding `WorkOS.key = $YOUR_API_KEY` to `app.rb`.

## Run the app

```sh
ruby app.rb
```

Head to `http://localhost:4567`!

For more information, see the [WorkOS Ruby SDK documentation](https://docs.workos.com/sdk/ruby).
