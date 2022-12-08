<div align="center">

# asdf-melt [![Build](https://github.com/chessmango/asdf-melt/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-melt/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-melt/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-melt/actions/workflows/lint.yml)


[melt](https://github.com/charmbracelet/melt) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add melt https://github.com/chessmango/asdf-melt.git
```

melt:

```shell
# Show all installable versions
asdf list-all melt

# Install specific version
asdf install melt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global melt latest

# Now melt commands are available
melt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-melt/graphs/contributors)!

# License

See [LICENSE](LICENSE)
