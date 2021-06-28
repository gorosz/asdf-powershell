<div align="center">

# asdf-powershell ![Build](https://github.com/gorosz/asdf-powershell/workflows/Build/badge.svg) ![Lint](https://github.com/gorosz/asdf-powershell/workflows/Lint/badge.svg)

[powershell](https://docs.microsoft.com/en-us/powershell/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add powershell
# or
asdf plugin add powershell https://github.com/gorosz/asdf-powershell.git
```

powershell:

```shell
# Show all installable versions
asdf list-all powershell

# Install specific version
asdf install powershell latest

# Set a version globally (on your ~/.tool-versions file)
asdf global powershell latest

# Now powershell commands are available
pwsh --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gorosz/asdf-powershell/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gergely Orosz](https://github.com/gorosz/)
