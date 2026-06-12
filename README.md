# tamag0-releases

> Public release artifacts for the [tamag0](https://tamag0.ai) desktop app.

tamag0 is a collaborative AI agent platform built by [Softizy](https://www.softizy.com).
Instead of a single assistant, you get a full team of specialized agents — each with their own
identity, expertise, and adaptive memory — working together and operational in minutes, not days.

This repository hosts the distributable binaries for **tamag0 Desktop** (Electron), across all
supported platforms. Releases are published automatically from
[`tamag0-desktop`](https://github.com/Softizy/tamag0-desktop) and serve as the update feed
for the auto-updater.

## Download

Grab the latest release from the [Releases page](https://github.com/Softizy/tamag0-releases/releases/latest).

| Platform | Format |
|----------|--------|
| macOS (Apple Silicon) | `.dmg`, `.zip` |
| macOS (Intel) | `.dmg`, `.zip` |
| Windows | `.exe` (installer) |
| Linux (x64) | `.AppImage`, `.deb` |
| Linux (arm64) | `.AppImage`, `.deb` |

## Auto-updates

tamag0 Desktop uses [`electron-updater`](https://www.electron.build/auto-update) and pulls
update metadata from this repository. No action required — the app notifies you when a new
version is available.

## Source code

The source for tamag0 Desktop lives in [`Softizy/tamag0-desktop`](https://github.com/Softizy/tamag0-desktop).
Issues and feature requests should be opened there.
