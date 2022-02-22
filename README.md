<div align="center">

# asdf-awsls [![Build](https://github.com/chessmango/asdf-awsls/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-awsls/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-awsls/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-awsls/actions/workflows/lint.yml)


[awsls](https://github.com/jckuester/awsls) plugin for the [asdf version manager](https://asdf-vm.com).

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

Pending: [#557](https://github.com/asdf-vm/asdf-plugins/pull/557)
```shell
asdf plugin add awsls https://github.com/chessmango/asdf-awsls.git
```

awsls:

```shell
# Show all installable versions
asdf list-all awsls

# Install specific version
asdf install awsls latest

# Set a version globally (on your ~/.tool-versions file)
asdf global awsls latest

# Now awsls commands are available
awsls --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-awsls/graphs/contributors)!

# License

See [LICENSE](LICENSE)
