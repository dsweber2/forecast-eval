# Forecast Eval

Epiforecast scoring and interactive evaluation tools.

## Steps to contribute
1. Create a new branch off of `dev`
2. Create a pull request into `dev`

Branch `main` is the production branch. Branch `dev` will be merged into main when a release is ready.


## Building

This project requires a recent version of gnu/make and docker.

Builds use a containerized R environment. See the `docker_build` directory for more details.

To build: 

```bash
> make build
```

To start `bash` shell in the docker container, which would let you start a R session:

```bash
> make start_repl
```

## Starting a local shiny server

To start a docker image of the shiny server locally:

```bash
> make start_dashboard
```
