# EVM++ Toolkit (`etkpp`)

[![license](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue)](https://github.com/gzanitti/etkpp)

`etk` is a for of the original [ETK](https://github.com/quilt/etk), a collection of tools for writing, reading, and analyzing EVM bytecode, but with new features, tweaks and small modifications.

## Documentation

For the time being, you can refer to the original ETK documentation. We will soon publish a documentation adapted to the new features included in ETK++.

The [`etk` book](https://quilt.github.io/etk) is the most comprehensive guide to using `etk`.

- [Introduction](https://quilt.github.io/etk)
- [Usage](https://quilt.github.io/etk/ch01-cli/index.html)
  - [`eas`](https://quilt.github.io/etk/ch01-cli/ch01-eas.html)
  - [`disease`](https://quilt.github.io/etk/ch01-cli/ch02-disease.html)
- [Language & Syntax](https://quilt.github.io/etk/ch02-lang/index.html)

There are also several examples in the [`etk-asm/tests/asm`](etk-asm/tests/asm) directory.

## Quickstart

### Installation

`etk++` requires the latest `rustc` from the stable channel.

```console
cargo install --features cli etk-asm etk-dasm
```

### Dependencies

`ecfg` requires z3 to build

Ubuntu Installation Instructions (example):

```console
sudo apt-get update -y
sudo apt-get install -y z3
sudo apt-get install -y libz3-dev
```

Check the system logs to confirm that there are no related errors.
