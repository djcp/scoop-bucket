# scoop-bucket

Scoop bucket for [enplace](https://github.com/djcp/enplace) — a CLI recipe manager powered by Claude AI.

## Install

```powershell
scoop bucket add djcp https://github.com/djcp/scoop-bucket
scoop install enplace
```

Upgrade with `scoop update enplace`.

## About this repo

The manifest (`enplace.json`) is generated and published automatically by
[GoReleaser](https://goreleaser.com) whenever a non-prerelease `enplace` release
is tagged. Don't edit it by hand — changes will be overwritten on the next release.
