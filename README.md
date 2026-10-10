# Lattice Windows releases

Windows installers and signed update metadata for Lattice. Application source is maintained separately; this repository contains no user documents or provider credentials.

## Updating

A configured Lattice installation checks the publisher feed automatically. When a newer release is available, the download arrow appears at the bottom left. Clicking it downloads and verifies the package, installs quietly, and restarts the app. Finish any running answer and save settings before updating.

Older unconfigured installations require a one-time bootstrap. Preview releases remain labelled pre-release until native upgrade qualification passes. The publisher feed is the `latest.json` asset on the `update-channel` release; installers are stored under immutable version tags.

Updater signatures verify package integrity and version. Windows Authenticode signing is separate and is not currently provided. Windows 11 x64 is the current supported test target.

See [Releases](https://github.com/rizkhan786/Lattice-Releases/releases) for available packages and their qualification status.
