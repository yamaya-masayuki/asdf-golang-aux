# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test golang-aux https://github.com/yamaya-masayuki/asdf-golang-aux.git "golang-aux --help"
```

Tests are automatically run in GitHub Actions on push and PR.
