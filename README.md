# Chip Hermes Desktop

Two [Omarchy](https://omarchy.org/) palettes adapted as skins for [Hermes Agent](https://hermes-agent.nousresearch.com/docs/): **White** and **Tokyo Night**.

## Install

```sh
git clone https://github.com/evgyur/chip-hermes-desktop.git
cd chip-hermes-desktop
mkdir -p "${HERMES_HOME:-$HOME/.hermes}/skins"
cp skins/omarchy-white.yaml skins/omarchy-tokyo-night.yaml "${HERMES_HOME:-$HOME/.hermes}/skins/"
```

Choose a skin:

```sh
hermes skin use omarchy-white
# or
hermes skin use omarchy-tokyo-night
```

To restore the default, run `hermes skin use default`. These skins change Hermes colors, not the system theme or fonts.
