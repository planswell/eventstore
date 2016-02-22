# EventStore

CQRS Event Store implemented in Elixir.

Uses Postgres as the underlying storage.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add eventstore to your list of dependencies in `mix.exs`:

        def deps do
          [{:eventstore, "~> 0.0.1"}]
        end

  2. Ensure eventstore is started before your application:

        def application do
          [applications: [:eventstore]]
        end
