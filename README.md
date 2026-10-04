# fmenezes zsh plugin

A small collection of [Oh My Zsh](https://ohmyz.sh/) helper functions.

| Function | Description |
| --- | --- |
| `darkmode` | Toggle macOS dark mode (macOS only, uses the bundled Automator workflow) |
| `uuid` | Generate a lowercase UUID |
| `compress-pdf <file>` | Compress a PDF with Ghostscript, writing to stdout |

## Requirements

- `gs` (Ghostscript) for `compress-pdf` — `brew install ghostscript`
- macOS for `darkmode`

## Installation

Clone into your Oh My Zsh custom plugins directory:

```sh
git clone https://github.com/fmenezes/zsh-plugin ~/.oh-my-zsh/custom/plugins/fmenezes
```

Then add the plugin to the `plugins` array in `~/.zshrc`:

```sh
plugins=(... fmenezes)
```

## License

[MIT](LICENSE)
