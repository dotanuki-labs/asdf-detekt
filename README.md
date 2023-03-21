# asdf-detekt

[![CI](https://github.com/dotanuki-labs/asdf-detekt/actions/workflows/ci.yml/badge.svg)](https://github.com/dotanuki-labs/asdf-detekt/actions/workflows/ci.yml)
[![Code Style](https://img.shields.io/badge/code%20style-%E2%9D%A4-FF4081.svg)](https://shellcheck.net/)
[![License](https://img.shields.io/github/license/dotanuki-labs/gradle-profiler-pttest)](https://choosealicense.com/licenses/mit)


A [detekt-cli](https://github.com/detekt/detekt) plugin for the [asdf version manager](https://asdf-vm.com).


## Installing

Installing this plugin:

```bash
$> asdf plugin add detekt https://github.com/dotanuki-labs/asdf-detekt.git
```

## Using

Installing the `detekt-cli` with `asdf`:

```bash

# Show all installable versions
$> asdf list-all detekt

# Install specific version
$> asdf install detekt latest

# Set a version globally (on your ~/.tool-versions file)
$> asdf global detekt latest

# Now detekt commands are available
$> detekt --version
```

## Additional information

Check [asdf](https://asdf-vm.com/) for more instructions on how to install and manage versions.

## License

Copyright (c) 2023 - Dotanuki Labs - [The MIT license](https://choosealicense.com/licenses/mit/)

