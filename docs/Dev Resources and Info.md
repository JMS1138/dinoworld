# Developer Resources and Info

This document is a place (dumping ground?) for interesting articles and other
information on game development.

## Initial Setup

In order to get started on development, you need to install a few things:

- [ASDF](https://asdf-vm.com/guide/getting-started.html), a tool for managing
  other dev tools
- [Godot Engine](https://godotengine.org/download/) ≥ 4.2. make sure to get the
  `.Net` version

In the project root, install all of the tooling dependencies with:

``` bash
asdf install
```

Next, we set up some custom githooks to help with development, so you need to
configure `git` to use them:

``` bash
git config --local core.hooksPath tools/githooks/
```

## Build Tooling and Processes

- https://blog.codemagic.io/godot-games-cicd/
- https://github.com/marketplace/actions/godot-ci
