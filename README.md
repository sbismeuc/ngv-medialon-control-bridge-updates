# NGV Medialon Control Bridge updates

This public repository distributes signed release manifests and DMG artifacts
for the NGV Medialon Control Bridge. It deliberately contains no source code,
site configuration, credentials, or signing key.

Installed release builds check [`stable.json`](stable.json). The app verifies
the manifest's Ed25519 signature and the downloaded DMG's SHA-256 before
opening the normal macOS installer.

The bridge source is maintained separately in a private repository.
Signed release feed for NGV Medialon Control Bridge
