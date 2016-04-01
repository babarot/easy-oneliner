# Easy One-liner

![](https://raw.githubusercontent.com/b4b4r07/screenshots/master/easy-oneliner/demo.gif)

## Usage

Type `C-x C-x` on your command-line.

## Installation

By using [zplug](https://github.com/b4b4r07/zplug), it's possible to easily install this:

```zsh
# Install easy-oneliner (If fzf is already installed)
zplug "b4b4r07/easy-oneliner", if:"which fzf"

# Install easy-oneliner with fzf
zplug "junegunn/fzf-bin", \
    as:command, \
    file:fzf, \
    from:gh-r \
    | zplug "b4b4r07/easy-oneliner", if:"which fzf"
```

## License

MIT
