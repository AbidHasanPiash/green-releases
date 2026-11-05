# Green Gateway — Android downloads

The Green Gateway app for Android: the full Green merchant app (orders,
customers, accounting) plus sending your store's SMS from this phone's SIM.

**Download the latest version:**
https://github.com/AbidHasanPiash/green-releases/releases/latest/download/Green-Gateway.apk

This link never changes; it always serves the newest build. Every build is
listed under [Releases](https://github.com/AbidHasanPiash/green-releases/releases)
with its SHA-256 checksum. `latest.json` describes the newest one
(version, build number, checksum, size, minimum Android).

## Installing

1. Open the link on the phone and download the APK.
2. Allow your browser to install apps when Android asks.
3. Open Green Gateway and sign in with your store account.

Requires Android 7.0 or newer. A new version installs over the old one and
keeps you signed in. (Builds from 0.3.3 on use a new signing key: if an older version is installed, uninstall it once first.)

## How releases are made

`.github/workflows/build-gateway.yml` checks the app's source every 15 minutes.
When it has changed, the workflow builds the APK, checks its signature, and
publishes it here as the newest release.
