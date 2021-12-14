<div align="center">

# asdf-yt-dlp [![Build](https://github.com/juusujanar/asdf-yt-dlp/actions/workflows/build.yml/badge.svg)](https://github.com/juusujanar/asdf-yt-dlp/actions/workflows/build.yml) [![Lint](https://github.com/juusujanar/asdf-yt-dlp/actions/workflows/lint.yml/badge.svg)](https://github.com/juusujanar/asdf-yt-dlp/actions/workflows/lint.yml)


[yt-dlp](https://github.com/yt-dlp/yt-dlp) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add yt-dlp
# or
asdf plugin add yt-dlp https://github.com/juusujanar/asdf-yt-dlp.git
```

yt-dlp:

```shell
# Show all installable versions
asdf list-all yt-dlp

# Install specific version
asdf install yt-dlp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global yt-dlp latest

# Now yt-dlp commands are available
yt-dlp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/juusujanar/asdf-yt-dlp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Janar Juusu](https://github.com/juusujanar/)
