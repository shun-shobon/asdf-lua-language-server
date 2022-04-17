# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test lua-language-server https://github.com/shun-shobon/asdf-lua-language-server.git "lua-language-server --version"
```

Tests are automatically run in GitHub Actions on push and PR.
