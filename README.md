# CreamiTracker versions

One small file, `versions.json`, with the newest version numbers of CreamiTracker, a private app.
An administrator's browser reads it at most once a day to show "a newer version exists".
The app itself never reads it and never updates itself.

- `release` — the newest final release.
- `prerelease` — the newest pre-release (`X.Y.Z-rcN`).

The file is written only by the app's release script, after the image has been built.
It holds nothing but version numbers: no code, no data, no links.

This repository takes no issues, pull requests or contributions.
