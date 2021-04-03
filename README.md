<p align="center">
  <p align="center">
    <img src="https://www.svgrepo.com/show/293646/cube.svg" height="100" alt="Scalar" />
  </p>
  <h3 align="center">
  About <code>Scalar</code>
  </h3>
  <p align="center">
    Distributed Scalability Toolbox
  </p>
  <p align="center">
    <a href="https://github.com/clintnetwork/scalar/actions?workflow=scalar"><img src="https://github.com/clintnetwork/scalar/workflows/scalar/badge.svg" /></a>
    <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Made%20With-Rust-dea584" /></a>
    <a href="https://github.com/clintnetwork/scalar/blob/master/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" /></a>
  </p>
</p>

## Introduction

Lucid is an high performance, secure and distributed key-value store accessible through an HTTP API, that is built arround a modulable configuration to enable features on the fly, like persistence, encryption SSE, compression, replication, and more.

## Getting Started

Get the latest binary from the [releases](https://github.com/clintnetwork/scalar/releases) page and run these commands:

```
$ ./scalar agent --install
```

## Command Line Interface

```
FLAGS:
    -h, --help         Prints help information
    -V, --version      Prints version information

OPTIONS:
    -c, --config <config>    Specify the `Scalar` configuration file
    -n, --node <node>        Connect to a specify `Scalar` node.

SUBCOMMANDS:
    help         Prints this message or the help of the given subcommand(s)
    agent        Setup or configure a Scalar agent
    logs         Play with remote logs
    nodes        Manage all your nodes
    settings     Change Scalar settings
```
