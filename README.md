# xkb

Custom xkb keyboard keymaps

## Install

Clone repo to `$HOME/.xkb` or `$XDG_CONFIG_HOME/xkb` or to path specified by `XKB_EXTRA_PATH` environment variable.

## Usage

```console
xkbcomp -I$HOME/.xkb -R$HOME.xkb ~/.xkb/keymap/programming $DISPLAY
```
