# CicadaLauncher releases

Downloads for [CicadaLauncher](https://github.com/improvestuff/CicadaLauncher), a minimal, very fast keystroke launcher for Windows.

**Get the latest version:** open [Releases](https://github.com/improvestuff/CicadaLauncher-releases/releases/latest), download `CicadaLauncher-vX.Y.Z-windows-x64.zip`, unzip it and run `cicada.exe`. Windows 10/11 x64; no installer and no runtime needed.

Once installed, CicadaLauncher keeps itself up to date from this page. You can turn that off in Settings > General.

## How updates are protected

Each release has a `latest.txt` manifest giving the version, the SHA-256 of `cicada.exe` and its download URL. The manifest is signed with an ECDSA P-256 key that never leaves the release machine.

The app installs an update only when all three hold:
- the signature verifies against the public key built into the app;
- the version is newer than the one running;
- the downloaded exe matches the signed checksum.

This repository contains release binaries only.
