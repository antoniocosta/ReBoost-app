<p align="center">
  <img src=".github/assets/reboost-icon.png" width="128" height="128" alt="ReBoost icon">
</p>

<h1 align="center">ReBoost</h1>

<p align="center">
  An Android client for Reddit with no ads, no purchases and no tracking.
  <br>
  Inspired by Boost for reddit, rebuilt on a modern stack.
  <br><br>
  <a href="https://github.com/antoniocosta/ReBoost-app/releases/latest">Releases</a>
</p>

This repository is the only place where ReBoost is published. Download APKs from [**Releases**](https://github.com/antoniocosta/ReBoost-app/releases/latest). Source is still private for now.

ReBoost is an independent project and is not affiliated with Boost for reddit. It is released with the permission and blessing of Boost's author.

## Requirements

- Android 8.0 or newer
- Your own Reddit client ID. ReBoost does not ship one: the first-start screen asks for it. Create one at [reddit.com/prefs/apps](https://www.reddit.com/prefs/apps) and copy it into the app.

## Install

1. Open the [latest release](https://github.com/antoniocosta/ReBoost-app/releases/latest) on your phone and download `reboost-X.Y.Z.apk` from **Assets**.
2. Open the downloaded file. If Android blocks it, allow **Install unknown apps** for your browser or file manager, then go back and tap **Install**.
3. Open ReBoost, enter your Reddit client ID, and log in.

## Update

- **Obtainium:** add `https://github.com/antoniocosta/ReBoost-app` to [Obtainium](https://github.com/ImranR98/Obtainium) to get notified of new releases.
- **By hand:** download the new APK and install it over the current version.

Android cannot install an older version over a newer one. To downgrade, uninstall first. Uninstalling deletes your local settings.

## Verify the APK

Every release lists the SHA-256 of the APK and of the signing certificate. The certificate must always be:

```
09:2C:E2:AF:0F:E9:7F:07:31:54:C8:F4:E8:CB:0E:48:7E:66:28:DA:31:3C:2C:27:9E:CA:9D:85:F7:20:2E:57
```

Check it with [AppVerifier](https://github.com/soupslurpr/AppVerifier) on the phone, or with the Android SDK:

```sh
apksigner verify --print-certs reboost-X.Y.Z.apk
shasum -a 256 reboost-X.Y.Z.apk
```

Only install APKs downloaded from this page.

## Privacy

No data is collected. See [PRIVACY.md](PRIVACY.md).

## Changelog

See the [release notes](https://github.com/antoniocosta/ReBoost-app/releases).

## Contact

Bugs and suggestions: [Issues](https://github.com/antoniocosta/ReBoost-app/issues)
