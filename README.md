# Steam Machine projects

Things I'm building for my Steam Machine: plugins, tools and tweaks for
SteamOS on a TV. Coded with [Claude](https://claude.ai).

## Projects

| Project | What it is | Status |
| --- | --- | --- |
| [Couch PiP](couch-pip) | Decky Loader plugin: picture-in-picture video over your games, made for TVs, with a controller remote. | Working, v0.4.5 |

Each project lives in its own repository and is linked here as a folder, so
each one keeps its own history, releases and updates.

## Getting everything at once

```sh
git clone --recurse-submodules https://github.com/CaraJean206/steam-machine
```

Or to bring every project up to date later:

```sh
git submodule update --remote
```

## Adding a project

- **Its own repo (best for anything people will install):** create the repo,
  then link it here with `git submodule add <repo-url> <folder-name>` and add a
  row to the table above.
- **A small idea or experiment:** make a plain folder in this repo with a
  `README.md` describing it. It can move to its own repo later.
