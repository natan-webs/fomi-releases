# FOMI releases

Official FOMI Android installation packages, SHA-256 checksums and bilingual release notes.

This repository contains release artifacts and documentation only. Application source code, project folders, source archives, signing keys, credentials and user data must never be uploaded here.

## Installation and updates

Download the [latest FOMI release](https://github.com/natan-webs/fomi-releases/releases/latest). Signed test APKs use the existing development certificate for compatible upgrades.

Keep the existing application identifier and signing certificate to preserve local data. The update client reads update.json and verifies the downloaded size, checksum, package identifier, version and signing certificate before opening the Android installer. Starting with 0.11.0, foreground entry checks can show an Update shortcut beside Home search. GitHub metadata caches may take a few minutes to refresh after publication.

A signed APK does not prevent inspection or reverse engineering. Third-party licensing obligations remain applicable.
