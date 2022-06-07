<div align="center">

# asdf-encore [![Build](https://github.com/hharzer/asdf-encore/actions/workflows/build.yml/badge.svg)](https://github.com/hharzer/asdf-encore/actions/workflows/build.yml) [![Lint](https://github.com/hharzer/asdf-encore/actions/workflows/lint.yml/badge.svg)](https://github.com/hharzer/asdf-encore/actions/workflows/lint.yml)


[encore](https://encore.dev/docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add encore
# or
asdf plugin add encore https://github.com/hharzer/asdf-encoredev.git
```

encore:

```shell
# Show all installable versions
asdf list-all encore

# Install specific version
asdf install encore latest

# Set a version globally (on your ~/.tool-versions file)
asdf global encore latest

# Now encore commands are available
encore --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/hharzer/asdf-encore/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Holger Harzer](https://github.com/hharzer/)
