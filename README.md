# Cinejoy TV update feed

This public repository contains update metadata for sideloaded Cinejoy TV installs. APKs are attached to GitHub Releases rather than committed into Git.

- Stable feed: `https://raw.githubusercontent.com/youssefbm2008/cinejoy-tv-updates/main/stable.json`
- Version history: `versions/`
- Download assets: version-tagged GitHub Releases

To publish a version, create its GitHub Release and upload the signed APK first. Then add a snapshot under `versions/` and update `stable.json` with the APK's direct release URL and SHA-256. Push the feed commit only after the asset is downloadable. Always increment `versionCode` and use the original signing key.
