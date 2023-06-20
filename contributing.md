# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test ocm-cli https://github.com/mrWinston/asdf-ocm-cli.git "ocm --version"
```

Tests are automatically run in GitHub Actions on push and PR.
