# RL Coach Companion: downloads

Live Rocket League coaching for Windows. It reads the game's official Stats API (no injection, no memory reading), shows short in-game tips, and builds post-match reviews from your replays.

This repository hosts **releases only**: installers, update manifests and the winget manifests. The source code is private.

## Download

- **Stable:** [latest release](https://github.com/tobysword/LiveRLCoach/releases/latest) → `RL-Coach-Companion_<version>_x64-setup.exe` (or the portable `.zip`)
- **Beta:** [releases](https://github.com/tobysword/LiveRLCoach/releases), marked *Pre-release*
- **winget:** `winget install tobysword.LiveRLCoach` (once accepted)

Windows SmartScreen may warn because the installer isn't code-signed yet: click **More info → Run anyway**. Check downloads against `SHA256SUMS.txt` on each release.

The app updates itself. Updates are signed, and the app checks the signature before installing.

## Help and feedback

Use the **Feedback** button in the app, or open an [issue](https://github.com/tobysword/LiveRLCoach/issues).

## Licence

Versions **0.12.0-beta.1 and earlier** were published under the GNU AGPL-3.0. That licence still applies to those versions and their source. Later versions are proprietary freeware: free to install and use, with optional paid Coach Pro features. See the terms shown in the app.
