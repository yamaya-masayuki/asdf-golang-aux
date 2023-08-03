<div align="center">

# asdf-golang-aux [![Build](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/build.yml/badge.svg)](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/build.yml) [![Lint](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/lint.yml/badge.svg)](https://github.com/yamaya-masayuki/asdf-golang-aux/actions/workflows/lint.yml)

arm64 build for old versions of golang plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add golang-aux https://github.com/yamaya-masayuki/asdf-golang-aux.git
```

golang-aux:

```shell
# Show all installable versions
asdf list-all golang-aux

# Install specific version
asdf install golang-aux 1.15.1-darwin-arm64

# Use specific version on local
asdf local golang-aux 1.15.1-darwin-arm64

# Now go commands are available
go --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# To support another version

If you want to build golang on your own, please refer to [fkr | go on darwin/arm64](https://hazardous.org/archive/blog/go/apple/2020/11/26/go-on-darwin-arm64), cross-compile and upload the resulting archive (.tbz) to `archive/`.

You will need to use git lfs since it is a large file.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yamaya-masayuki/asdf-golang-aux/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [M.Yamaya/CM](https://github.com/yamaya-masayuki/)
