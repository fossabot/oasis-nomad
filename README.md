# Oasis Nomad Manager

[![CircleCI](https://circleci.com/gh/xvello/oasis-nomad/tree/master.svg?style=shield)](https://circleci.com/gh/xvello/oasis-nomad/tree/master)
[![Go Report Card](https://goreportcard.com/badge/github.com/xvello/oasis-nomad)](https://goreportcard.com/report/github.com/xvello/oasis-nomad)
[![GoDoc](https://godoc.org/github.com/xvello/oasis-nomad?status.svg)](https://godoc.org/github.com/xvello/oasis-nomad)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fxvello%2Foasis-nomad.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fxvello%2Foasis-nomad?ref=badge_shield)

A Nomad management CLI for single-node and small cluster use cases

# What

Oasis provides a set of commands to easily manage a single-node Nomad server,
run tasks and keep them up to date.
Its design is opinionated and tailored to the single-node, self-hosted use case, with
the goal of reducing operational toil while keeping the tasks secure and up-to-date.

# Why Nomad

While containers' immutability is great for self-hosted servers where things might
quickly become dangerously tangled, the docker API and docker-compose and notoriously
hard to program with. Nomad provides a sane API in a small footprint. Associated with
Consul for configuration and service discovery, it provides all the features needed.

# How to use

TODO


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fxvello%2Foasis-nomad.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fxvello%2Foasis-nomad?ref=badge_large)