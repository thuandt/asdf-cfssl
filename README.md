<div align="center">

# asdf-cfssl ![Build](https://github.com/mathew-fleisch/asdf-cfssl/workflows/Build/badge.svg) ![Lint](https://github.com/mathew-fleisch/asdf-cfssl/workflows/Lint/badge.svg)

[cfssl](https://github.com/cloudflare/cfssl) [plugin](https://github.com/mathew-fleisch/asdf-cfssl) for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- bash
- curl

# Install

Plugin:

```shell
asdf plugin add cfssl
# or
asdf plugin add https://github.com/mathew-fleisch/asdf-cfssl.git
```

cfssl:

```shell
# Show all installable versions
asdf list-all cfssl

# Install specific version
asdf install cfssl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cfssl latest

# Now cfssl commands are available
cfssl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).


### Notes

- https://computingforgeeks.com/how-to-install-cloudflare-cfssl-on-linux-macos/
- https://github.com/cloudflare/cfssl/releases
- https://github.com/asdf-vm/asdf/blob/master/docs/plugins-create.md
- https://github.com/asdf-vm/actions
- https://github.com/asdf-vm/asdf-plugins