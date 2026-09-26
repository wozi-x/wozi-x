# Mac setup

Copy and run this on a new Mac:

```sh
curl -fsSL https://wozi-x.github.io/mac | /bin/bash -p
```

Run from Terminal using your administrator account, without adding `sudo` to
the command. Enter your Mac login password when the installer asks for it.

The starter prepares Command Line Tools, Homebrew, and GitHub CLI, guides GitHub
browser sign-in, then lets you choose:

- **Base** — Raycast, Zed, shell tools, and selected macOS preferences.
- **Dev** — the complete development setup; repository access is required.
- **Admin** — the development setup with Admin additions; repository access is required.

Base uses the [public setup](https://github.com/wozi-x/PKGMacSetupPublic) and can
use a local configuration directory. Dev and Admin use the existing setup and
defer App Store and private-storage stages.
