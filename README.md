<div align="center">

# asdf-golang-aux [![Build](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/build.yml/badge.svg)](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/build.yml) [![Lint](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/lint.yml/badge.svg)](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/lint.yml)

[golang-aux](https://github.com/yamaya-masayuki/golang-aux) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add golang-aux
# or
asdf plugin add golang-aux https://github.com/yamaya-masayuki/asdf-golang-aux.git
```

golang-aux:

```shell
# Show all installable versions
asdf list-all golang-aux

# Install specific version
asdf install golang-aux latest

# Set a version globally (on your ~/.tool-versions file)
asdf global golang-aux latest

# Now golang-aux commands are available
golang-aux --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yamaya-masayuki/asdf-golang-aux/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [M.Yamaya/CM](https://github.com/yamaya-masayuki/)
