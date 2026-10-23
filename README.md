# Omni-OS releases

Official Windows installers for **Omni-OS**, by [Kondux](https://kondux.io).

Download the latest version from **[Releases](https://github.com/Kondux/Omni-OS-releases/releases/latest)**.

Omni-OS checks this page for updates (when it starts, and once a day) and offers a new version with *Update now / Later / Skip this version*. You can turn that off under Settings → Updates.

## Verify a download

Each release includes a `SHA256SUMS` file. Before installing, check the installer against it:

```
certutil -hashfile Omni-OS-Setup-<version>.exe SHA256
```

The in-app updater does this check automatically and won't run an installer that doesn't match.

## Licence

Omni-OS is licensed under the Apache License 2.0. The licence and third-party notices are included with every installer.

This repository holds releases only.
