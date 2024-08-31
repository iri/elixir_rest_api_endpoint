# elixir-rest-api-endpoint
Elixir HTTP server with REST API endpoint

mix phx.new real_deal_api --no-install --app real_deal_api --database postgres --no-live --no-assets --no-html --no-dashboard --no-mailer --binary-id

We are almost there! The following steps are missing:

cd real_deal_api
mix deps.get

Then configure your database in config/dev.exs and run:
mix ecto.create

Start your Phoenix app with:
mix phx. server

You can also run your app inside IEx (Interactive Elixir) as:
iex -S mix phx.server

