Steam-Play-Linux
---
Run Windows games which don't officially support Linux but ship Linux binaries regardless.

# Installation

## Install manually

- Download this repository as an archive file: [Download](https://github.com/SnoutBug/steam-play-linux/archive/refs/heads/main.tar.gz)
- Create the directory `~/.steam/steam/compatibilitytools.d` if it doesn't exist yet
- Extract it to `~/.steam/steam/compatibilitytools.d/`
- Set the compatibility-tool for the game in your library to "Linux"

# Usage

- In steam launch options, set the path to your Linux binary

# Why

Some developers might decide that their game does not run sufficiently good on Linux and will in turn not make a Linux version public.
However they still want to provide some more tech-savvy people access for testing purposes packaged with the windows version.

Steam play linux allows you to launch native linux games packaged as a windows game by reading the launch options.
This should also enable all steam functions, such as cloud saves, achievements, time tracking and rich presence, should the game support that.

# License
This work is licensed under CC0. See [LICENSE](LICENSE):
