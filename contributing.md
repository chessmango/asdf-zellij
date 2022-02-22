# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test awsls https://github.com/chessmango/asdf-awsls.git "awsls --version"
```

Tests are automatically run in GitHub Actions on push and PR.
