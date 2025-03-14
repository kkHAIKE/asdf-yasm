<div align="center">

# asdf-yasm [![Build](https://github.com/kkHAIKE/asdf-yasm/actions/workflows/build.yml/badge.svg)](https://github.com/kkHAIKE/asdf-yasm/actions/workflows/build.yml) [![Lint](https://github.com/kkHAIKE/asdf-yasm/actions/workflows/lint.yml/badge.svg)](https://github.com/kkHAIKE/asdf-yasm/actions/workflows/lint.yml)

[yasm](https://www.tortall.net/projects/yasm/manual/html/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add yasm
# or
asdf plugin add yasm https://github.com/kkHAIKE/asdf-yasm.git
```

yasm:

```shell
# Show all installable versions
asdf list-all yasm

# Install specific version
asdf install yasm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yasm latest

# Now yasm commands are available
yasm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kkHAIKE/asdf-yasm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [kkhaike](https://github.com/kkHAIKE/)
