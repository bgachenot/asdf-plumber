<div align="center">

# asdf-plumber [![Build](https://github.com/bgachenot/asdf-plumber/actions/workflows/build.yml/badge.svg)](https://github.com/bgachenot/asdf-plumber/actions/workflows/build.yml) [![Lint](https://github.com/bgachenot/asdf-plumber/actions/workflows/lint.yml/badge.svg)](https://github.com/bgachenot/asdf-plumber/actions/workflows/lint.yml)

[plumber](https://docs.getplumber.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add plumber
# or
asdf plugin add plumber https://github.com/bgachenot/asdf-plumber.git
```

plumber:

```shell
# Show all installable versions
asdf list-all plumber

# Install specific version
asdf install plumber latest

# Set a version globally (on your ~/.tool-versions file)
asdf global plumber latest

# Now plumber commands are available
plumber --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bgachenot/asdf-plumber/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Brandon Gachenot](https://github.com/bgachenot/)
