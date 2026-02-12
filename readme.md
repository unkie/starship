```txt
█▀ ▀█▀ ▄▀█ █▀█ █▀ █░█ █ █▀█
▄█ ░█░ █▀█ █▀▄ ▄█ █▀█ █ █▀▀
```

My starship config.

---

## Installation

Starships config file needs to be in `${XDG_CONFIG_HOME}`.
To put it in a git repo like this one, we need to symlink the
config file to there.

To install:

```sh
cd "${XDG_CONFIG_HOME:-$HOME/.config}"
git clone https://github.com/unkie/starship/ starship
ln -s starship/starship.toml .
```

---

Header text generated with [hyprtxt](https://github.com/unkie/hyprtxt/).
