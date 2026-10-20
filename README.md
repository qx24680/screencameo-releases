# ScreenCameo releases

This repository hosts the downloads for **[ScreenCameo](https://screencameo.com)**, a screen recorder for macOS.
It holds release files only. ScreenCameo's source code is not public and is not in this repository.

**Get ScreenCameo:** [screencameo.com/download](https://screencameo.com/download/)

## What each release contains

| File | What it is |
| --- | --- |
| `ScreenCameo-<version>.dmg` | The installer. Open it and drag ScreenCameo to Applications. |
| `ScreenCameo-<version>.zip` | The update archive the app downloads when you choose to install an update. |
| `SHA256SUMS` | SHA-256 checksums of the two files above. |

Every build is signed with ScreenCameo's Developer ID and notarized by Apple. Updates are also signed, and the app
checks that signature before it installs anything.

The "Source code" archives that GitHub adds to every release are generated automatically. They contain only this
README.

## Check a download (optional)

In Terminal, in the folder with the downloaded files:

```sh
shasum -a 256 -c SHA256SUMS --ignore-missing
```

Each file you downloaded should say `OK`.

## Help

Email [support@screencameo.com](mailto:support@screencameo.com). Issues are turned off in this repository.
