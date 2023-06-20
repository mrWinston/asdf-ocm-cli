<div align="center">

# asdf-ocm-cli [![Build](https://github.com/mrWinston/asdf-ocm-cli/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-ocm-cli/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-ocm-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-ocm-cli/actions/workflows/lint.yml)

[ocm-cli](https://github.com/openshift-online/ocm-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies


- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ocm-cli
# or
asdf plugin add ocm-cli https://github.com/mrWinston/asdf-ocm-cli.git
```

ocm-cli:

```shell
# Show all installable versions
asdf list-all ocm-cli

# Install specific version
asdf install ocm-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ocm-cli latest

# Now ocm-cli commands are available
ocm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-ocm-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)
