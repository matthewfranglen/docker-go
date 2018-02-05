Docker Go
---------

This provides the `go` command using docker.

### Usage

Using current version:

```bash
go help
```

Use custom version:

```bash
DOCKER_GO_VERSION=1.8 go help
```

This will always use the alpine version.
You can see the available versions [here](https://hub.docker.com/_/golang/).

### Installation

If you have [antigen](https://github.com/zsh-users/antigen) then just run the following:

```bash
antigen-bundle matthewfranglen/docker-go
```

Otherwise just clone this repo and add the `bin` folder to the $PATH.
