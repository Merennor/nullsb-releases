# nb APK mirror

> Auto-mirror for [Obtainium](https://github.com/ImranR98/Obtainium) — **do not use this repo for anything else.**

New releases are published by a GitHub Actions workflow that tracks `dnull.xyz/latest_bs`

## Obtainium setup

1. Open Obtainium → **Add App**
2. Paste this repo URL
3. Source is auto-detected as **GitHub** — hit Save

That's it. Obtainium will notify you when a new release appears.

## How it works

| What | Detail |
|---|---|
| Source | `dnull.xyz/latest_bs` (redirect to latest APK) |
| Release tag | `{version}-{commit}` e.g. `xx.yyy-(hash)` |
| Release title | `{version} ({commit})` e.g. `xx.yyy (hash)` |
| Duplicate guard | Skips publishing if the tag already exists |
