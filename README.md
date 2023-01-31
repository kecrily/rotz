# Rotz 👃
[![crates.io](https://img.shields.io/crates/v/rotz)](https://crates.io/crates/rotz)
![](https://img.shields.io/badge/platform-windows%20%7C%20linux%20%7C%20macos-lightgrey)
[![](https://img.shields.io/crates/l/rotz)](https://github.com/volllly/rotz/blob/main/LICENSE)

Fully cross platform dotfile manager and dev environment bootstrapper written in Rust.

> `Rust Dotfilemanager`<br>
> `Rust Dotfile manager`<br>
> `Rust Dotfile s`<br>
> `Rust Dot s`<br>
> `R ust Dots`<br>
> `R ots`<br>
> `Rot s`<br>
> `Rotz`

## [🗺️ Roadmap](https://github.com/users/volllly/projects/1/views/1)

## [📖 Documentation](https://volllly.github.io/rotz/)

## Overview

Rotz has three main functionalities:

1. Linking dotfiles from a common repository to your system
2. Installing the applications you need to start working on an new/empty machine
3. Full Cross platform functionality [See Configuration](https://volllly.github.io/rotz/docs/configuration/os-specific-configuration)

## Installation

You can install Rotz using cargo.

```sh
cargo install rotz
```

### Other File Formats

Rotz uses [`yaml`](https://yaml.org/) configuration files per default. You can also use [`toml`](https://toml.io/) or [`json`](https://www.json.org/) files instead.

To use another format install Rotz using one of the following comands:
* ```sh
  cargo install rotz --no-default-features --features toml
  ```
* ```sh
  cargo install rotz --no-default-features --features json
  ```

> ***Note:** You can install multiple formats and rotz will auto detect the filetype.*

## Getting Started

If you already have a `dotfiles` repo you can clone it with the `rotz clone` command.

```sh
rotz clone git@github.com:<user>/<repo>.git
```

To bootstrap your dev environment use `rotz install`.

To link your `dotfiles` use `rotz link`.

## Usage

Run `rotz --help` to see all commands Rotz has.

## Contribute

Feel free to create pull requests and issues for bugs, features or questions. 
