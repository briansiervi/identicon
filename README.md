# Identicon

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).


### Install EGD
Add dependency
```
{:egd, github: "erlang/egd"}
```
Run
```
mix local.rebar --force
mix deps.get
```

### Install Docs
Add dependency
```
{:ex_doc, "~> 0.12"}
```
Run
```
mix deps.get
mix docs
```

## Run app
```
iex -S mix
```