<div align="center">

# asdf-bpkg [![Build](https://github.com/bpkg/asdf-bpkg/actions/workflows/build.yml/badge.svg)](https://github.com/bpkg/asdf-bpkg/actions/workflows/build.yml) [![Lint](https://github.com/bpkg/asdf-bpkg/actions/workflows/lint.yml/badge.svg)](https://github.com/bpkg/asdf-bpkg/actions/workflows/lint.yml)


[bpkg](https://github.com/bpkg/bpkg) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bpkg
# or
asdf plugin add bpkg https://github.com/bpkg/asdf-bpkg.git
```

bpkg:

```shell
# Show all installable versions
asdf list-all bpkg

# Install specific version
asdf install bpkg latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bpkg latest

# Now bpkg commands are available
bpkg --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bpkg/asdf-bpkg/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Francesco Bianco](https://github.com/bpkg/)
