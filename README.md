# PLOPAL Emulator — Public Updates

This is the **official public Windows x64 update distribution** for PLOPAL Emulator. The PLOPAL source code stays **private** in a separate repository.

## For users

Install PLOPAL using an official `PLOPAL-Setup.exe` from the [Releases page](https://github.com/Fort1k3FN/PLOPAL-UPDATE/releases). Then open **PLOPAL → Settings → Updates** to check and install the latest version automatically.

**No GitHub account, GitHub Desktop, Git for Windows, or access token is required** to download published updates.

## Release assets

Each verified release contains:
- `plopal-windows-x64.zip` — Windows update package
- `plopal-update.json` — version, channel, size and SHA-256 checksum
- `PLOPAL-Setup.exe` — Windows installer (for new users and recovery)

PLOPAL verifies package metadata and downloaded bytes before installing. Preview builds are prereleases; stable updates appear on the stable channel.

**For the developer:** compile and test the private source using its Release Center. The publisher authenticates with GitHub only on the developer's machine to upload release assets here. Never upload source code, credentials, private files or signing keys to this public repository.

This repository can be empty of Releases until the first verified binary publication.
