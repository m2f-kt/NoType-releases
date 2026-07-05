# TypeNot — Desktop releases

This repository is the **public download and auto-update channel** for the **TypeNot** desktop app
(a.k.a. NoType). The application source lives in a separate private repository; only built installers
are published here.

## Download

Grab the latest build from the [**Releases**](https://github.com/m2f-kt/NoType-releases/releases/latest)
page. Each release attaches:

- `TypeNot-<version>-arm64.dmg` — macOS (Apple Silicon)
- `TypeNot-<version>-arm64.dmg.sha256` — checksum to verify the download

## Automatic updates

The desktop app checks this repository's latest release on launch and prompts you when a newer version
is available. Releases are published automatically by CI when a new version is tagged.

## Verifying a download

```sh
shasum -a 256 -c TypeNot-<version>-arm64.dmg.sha256
```

---

_Installers are published here automatically; do not commit application source to this repository._
