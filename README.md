# Mac setup

Copy and run this on a new Mac:

```sh
curl -fsSL https://wozi-x.github.io/mac | /bin/bash -p
```

Skip the menu with `--base`, `--dev`, or `--admin`:

```sh
curl -fsSL https://wozi-x.github.io/mac | /bin/bash -p -s -- --dev
```

Use `--status` instead for a read-only check of the last recorded role and key
installed features. Older Macs without a receipt show an unknown role.

Run from Terminal using your administrator account, without adding `sudo` to
the command. Enter your Mac login password when the installer asks for it.

Choose the role first; the starter then prepares Command Line Tools, Homebrew,
and GitHub CLI:

- **Base** — Raycast, Zed, Amphetamine, Oh My Zsh, shell tools, and selected macOS preferences.
- **Dev** — the complete development setup; repository access is required.
- **Admin** — the development setup with Admin additions; repository access is required.

Base uses the [public setup](https://github.com/wozi-x/PKGMacSetupPublic) and can
use a local configuration directory. It does not require a GitHub account or
GitHub sign-in. Choose the role before prerequisite downloads, then press Enter
at any readiness pause once ready; s skips and q quits. Base prompts for App
Store sign-in when apps are missing. Dev and Admin guide GitHub browser sign-in
before retrieving their setup, include App Store work in the same run when
ready. Admin setup also offers enabled private storage in the same run, after
you confirm NAS access and close DEVONthink. Press Enter to continue, s to
defer, or q to quit. Dev setup does not request private storage.
Command Line Tools installation continues automatically when ready. Local
Dev/Admin failures offer Enter to retry the current stage without repeating
completed stages.
