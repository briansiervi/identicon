# Identicon

**TODO: Add description**

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

### Install Phoenix (linux)
Phoenix
```
https://hexdocs.pm/phoenix/installation.html#content

$ mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new.ez
```
PostgreSQL
```
sudo apt update
sudo apt install postgresql postgresql-contrib
sudo -u postgres psql
\q

font: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04
```
Sqlite alternative to Postgres
```
font: https://github.com/jazzyb/sqlite_ecto
```

inotify-tools
```
apt-get install inotify-tools
```