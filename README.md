# verdictui-releases

Prebuilt VerdictUI command-line releases, published for the
[`medlars/homebrew-tap`](https://github.com/medlars/homebrew-tap) formula:

```sh
brew install medlars/tap/verdictui
```

This repository holds release assets only: no source and no source history.
Each release ships `verdictui-<version>-macos-universal.zip` (arm64 + x86_64)
and its `.sha256`. The binary is signed with Developer ID (team `P6R899T379`),
hardened runtime, and notarized by Apple.

Every published asset is scanned on release (`.github/workflows/asset-audit.yml`):
no home-directory paths, no secrets, valid signature.
