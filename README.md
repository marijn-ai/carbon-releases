# Carbon releases

Built copies of Carbon, the Borish mail client for Mac. Nothing here is source code.

Each release carries `Carbon-<version>-<build>.zip`, the same build as a `.dmg`, and `appcast.json`. Installed copies of Carbon read `appcast.json` from the latest release, verify the zip's Ed25519 signature, and offer the update under Settings → App. First-time installs use the DMG.
