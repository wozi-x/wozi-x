# Mac setup

Copy and run this on a new Mac:

```sh
curl -fsSL https://wozi-x.github.io/mac | /bin/bash -p
```

Run from Terminal using your administrator account, without adding `sudo` to
the command. Enter your Mac login password when the installer asks for it.

It installs or updates Homebrew, Chrome, 1Password, the ChatGPT desktop app with
Codex, and GitHub CLI; authenticates GitHub; then clones or updates PKGMacSetup
and starts standard setup. Standard setup does not request private SMB storage.

The public installer source is reviewed at
[wozi-x/PKGMacSetupPublic](https://github.com/wozi-x/PKGMacSetupPublic).
