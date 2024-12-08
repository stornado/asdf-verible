<div align="center">

# asdf-verible [![Build](https://github.com/stornado/asdf-verible/actions/workflows/build.yml/badge.svg)](https://github.com/stornado/asdf-verible/actions/workflows/build.yml) [![Lint](https://github.com/stornado/asdf-verible/actions/workflows/lint.yml/badge.svg)](https://github.com/stornado/asdf-verible/actions/workflows/lint.yml)

[verible](https://chipsalliance.github.io/verible/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add verible
# or
asdf plugin add verible https://github.com/stornado/asdf-verible.git
```

verible:

```shell
# Show all installable versions
asdf list-all verible

# Install specific version
asdf install verible latest

# Set a version globally (on your ~/.tool-versions file)
asdf global verible latest

# Now verible commands are available
verible-verilog-format --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stornado/asdf-verible/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [仲夏叶](https://github.com/stornado/)
