# AeroSpace config

Personal [AeroSpace](https://github.com/nikitabobko/AeroSpace) window manager config, paired with [JankyBorders](https://github.com/FelixKratz/JankyBorders) for the active-window border.

## Setup on a new machine

1. Install apps by the developers recommended channels.

2. AeroSpace looks for `~/.aerospace.toml` by default, usually on my machine the repos live at `~/Developer/*` and for this project we need to create a symlink pointing `~/Developer/aerospace/aerospace.toml` to `~/.aerospace.toml`.

JankyBorders is launched by AeroSpace itself via `after-startup-command` in the config (no separate service/LaunchAgent needed).

Reload after editing:

```sh
aerospace reload-config
```
