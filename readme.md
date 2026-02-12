```txt
█▀ ▀█▀ ▄▀█ █▀█ █▀ █░█ █ █▀█
▄█ ░█░ █▀█ █▀▄ ▄█ █▀█ █ █▀▀
```

My starship config

---

## Installation

Starships config file needs to be in `${XDG_CONFIG_HOME}`.
To put it in a git repo like this one, we need to symlink the
config file to there.

This zsh setup used the standard XDG directories for config, cache, etc.
To enable this, we must set `ZDOTDIR` to the XDG config directory.
The earliest we can do this is when `~/.zshenv` is loaded.

To install this zsh setup:

```sh
git clone https://github.com/unkie/starship/ zsh
cd "${XDG_CONFIG_HOME:-$HOME/.config}"
ln -s starship/starship.toml .
```

---

Header text generated with [hyprtxt](https://github.com/unkie/hyprtxt/)
