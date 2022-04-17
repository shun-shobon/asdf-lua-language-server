<div align="center">

# asdf-lua-language-server [![Build](https://github.com/shun-shobon/asdf-lua-language-server/actions/workflows/build.yml/badge.svg)](https://github.com/shun-shobon/asdf-lua-language-server/actions/workflows/build.yml) [![Lint](https://github.com/shun-shobon/asdf-lua-language-server/actions/workflows/lint.yml/badge.svg)](https://github.com/shun-shobon/asdf-lua-language-server/actions/workflows/lint.yml)


[lua-language-server](https://github.com/sumneko/lua-language-server) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lua-language-server https://github.com/shun-shobon/asdf-lua-language-server.git
```

lua-language-server:

```shell
# Show all installable versions
asdf list-all lua-language-server

# Install specific version
asdf install lua-language-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lua-language-server latest

# Now lua-language-server commands are available
lua-language-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/shun-shobon/asdf-lua-language-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Shuntaro Nishizawa](https://github.com/shun-shobon/)
