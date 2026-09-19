# Mac setup

Public, standalone macOS setup lives in
[wozi-x/PKGMacSetupPublic](https://github.com/wozi-x/PKGMacSetupPublic).

Prepare a new Mac's controller prerequisites:

```sh
curl -fsSL https://wozi-x.github.io/mac |
  /bin/bash -p -s -- --prepare
```

Then choose and preview a complete configuration:

```sh
# Admin
curl -fsSL https://wozi-x.github.io/mac |
  /bin/bash -p -s -- --config examples/admin.yml --plan

# iOS Dev (use examples/web-dev.yml for Web Dev)
curl -fsSL https://wozi-x.github.io/mac |
  /bin/bash -p -s -- --config examples/ios-dev.yml --plan
```

The public flow does not authenticate GitHub or retrieve private configuration.
Review the repository README before replacing `--plan` with `--apply`.
