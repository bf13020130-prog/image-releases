# image desktop releases

This public repository contains no-key desktop update assets only. It does not contain source code, AI API configuration, Codex authentication, user data, logs, images, or canvas history.

## Windows

Download the latest Windows x64 folder update from [Releases](https://github.com/bf13020130-prog/image-releases/releases/latest).

The desktop client reads `latest.json` and `latest.json.sig` from the `main` branch, verifies the Ed25519 signature with its packaged public key, and then verifies the selected ZIP and every installed program file by SHA-256. Existing `data/` is not part of public updates.

## macOS

Signed and notarized Apple Silicon assets will be published only after Developer ID and Apple Silicon validation. Until then, no macOS automatic-update asset is advertised here.
