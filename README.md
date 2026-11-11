# Neon Horizon

A retro '80s neon dark theme for [Orca](https://github.com/stablyai/orca): an app theme (UI + code colors) and a matching terminal palette. Inspired by Synthwave '84.

## Install

```sh
orca plugin install <this-repo-url>   # or a local folder path
```

Then pick **Neon Horizon** in Settings → Appearance (app theme) and in the terminal palette picker.

## Develop

```sh
orca plugin validate .
orca plugin dev watch .   # live-reloads edits to themes/ and terminal/
```

Files: `themes/neon-horizon.json` (app tokens + `tokenColors`), `terminal/neon-horizon.json` (ANSI palette).
