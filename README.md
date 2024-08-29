# Heroku buildpack for DuckDB
This is a [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for [DuckDB](https://duckdb.org/) required to work with gem [Ruby DuckDB](https://github.com/suketa/ruby-duckdb)

## Usage
Add the buildpack to your Heroku app:
```bash
heroku buildpacks:add https://github.com/dataPlor/heroku-buildpack-ruby-duckdb.git
```
it should be added before the Ruby buildpack.
