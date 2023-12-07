<div align="center">

# asdf-onyx [![Build](https://github.com/jtakakura/asdf-onyx/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-onyx/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-onyx/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-onyx/actions/workflows/lint.yml)

[onyx](https://onyxlang.io/docs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add onyx
# or
asdf plugin add onyx https://github.com/jtakakura/asdf-onyx.git
```

onyx:

```shell
# Show all installable versions
asdf list-all onyx

# Install specific version
asdf install onyx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global onyx latest

# Now onyx commands are available
onyx version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-onyx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
