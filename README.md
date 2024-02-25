# Flatboat

![Logo](https://github.com/JuanCSUCoder/flatboat-brand/blob/main/logo.png?raw=true)

Flatboat is a CLI tool that integrates **Docker** and **Kubernetes** tooling into the **ROS workspace** workflow.

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Features

- **Automatic** container lifecycle managment
- **Create ROS workspaces** from devcontainer templates
- **Execute ROS2 commands** inside the container
- **Execute shell commands** inside the container
- Out of the box graphical user interface **GUI support**
- Out of the box **GPU support**
- Out of the box workspace **volume binding**
- Out of the box **host network** connectivity
- Out of the box **avahi service** for .local domain resolution
- Compatible with **Devcontainer Specification**

## Compatibility

Compatible with **Linux** distributions capable of running **Docker** with **X11** window system and **avahi daemon**.

**NOTE:** Linux distros with diferent configuration may be able to run flatboat with a few workarounds.

## Installation

### Dependencies

- Docker [Installation](https://docs.docker.com/engine/install/)
- NodeJS [Official Download](https://nodejs.org/en) or [Installation with NodeSource](https://github.com/nodesource/distributions?tab=readme-ov-file#debian-and-ubuntu-based-distributions)
- Devcontainer `npm i -g @devcontainers/cli`
- Rust and Cargo `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`

### Install

Install Flatboat with `cargo`

```bash
  cargo install flatboat
```

## Usage

Learn about Flatboat with:

```bash
  flatboat -h
```

## Authors

- [@JuanCSUCoder - Juan Camilo Sánchez Urrego](https://www.github.com/JuanCSUCoder) - <juancsucoder@gmail.com>

## Roadmap

1. Templates
    1. Package Dockerfile
    2. Kubernetes Workers
    3. Kubernetes Master
2. Integration of Templates
3. Local Kubernetes Driver
