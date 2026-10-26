# FOMI releases

Official FOMI Android installation packages, SHA-256 checksums and release notes.

This repository contains release artifacts and documentation only. Application source code, project folders, source archives, signing keys, credentials and user data must never be uploaded here.

## Installation and updates

Download [FOMI 0.10.1](https://github.com/natan-webs/fomi-releases/releases/tag/v0.10.1). The signed test APK uses the existing development certificate for compatible upgrades.

Keep the existing application identifier and signing certificate to preserve local data. The update client reads update.json and verifies the downloaded checksum, package identifier, version and signing certificate before opening the Android installer.

A signed APK does not prevent inspection or reverse engineering. Third-party licensing obligations remain applicable.
