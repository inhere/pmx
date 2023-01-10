# pmx

![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/gookit/gcli?style=flat-square)
[![Unit-Tests](https://github.com/gookit/gcli/actions/workflows/go.yml/badge.svg)](https://github.com/gookit/gcli/actions/workflows/go.yml)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/gookit/gcli)](https://github.com/gookit/gcli)
[![Go Reference](https://pkg.go.dev/badge/github.com/gookit/goutil.svg)](https://pkg.go.dev/github.com/gookit/goutil)
[![Go Report Card](https://goreportcard.com/badge/github.com/gookit/gcli)](https://goreportcard.com/report/github.com/gookit/gcli)

pmx - Lightweight process manager by Go

- Dynamic process supervision: create, start, stop, restart, delete.

> **[EN README](README.md)**

## Install

```shell
go get github.com/{{ .TplCtx.RepoPath }}
```

## Usage

```go
// ...
```

## Procfile

Procfile example:

```yaml
web: node run dev
api: go run ./server
```

## Refers

- Procfile - https://devcenter.heroku.com/articles/procfile
- https://github.com/mattn/goreman
- https://github.com/ddollar/forego
- https://github.com/ntt360/pmon2
- https://github.com/DarthSim/hivemind
- https://github.com/DarthSim/overmind
