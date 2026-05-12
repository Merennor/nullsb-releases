# nb APK mirror

> Mirror for [Obtainium](https://github.com/ImranR98/Obtainium) — **do not use this repo for anything else.**
> If you're looking for official source to download from, [click here](https://nulls.gg/servers/nulls-brawl/download/)

[![Downloads](https://img.shields.io/github/downloads/Merennor/nullsb-releases/total?style=for-the-badge)](https://img.shields.io/github/downloads/Merennor/nullsb-releases/total?style=for-the-badge)

**Releases are published by a GitHub Actions workflow (manual) that downloads from official source of this game (nulls.gg, direct link)**

Nulls doesn't have an in-app updater as such, and when a new version is released, it simply asks you to go to their website to download the new update. (And keep in mind that it won't let you play until you install the update)

With Obtainium, we can set up auto-updates without having to open a browser (and also Obtainium will clean up the update apk file eventually)

## Setup

1. [Add it to Obtainium](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium://add/https://github.com/Merennor/nullsb-releases) (or do it manually by copy pasting this repo's link)
2. hit Save button, then wait up to 5-10mins (**DON'T LEFT THE APP**, or you will get error)

And that's all you need to do. Now Obtainium will notify you when a new release appears.

## How it works

| What | Detail |
|---|---|
| Source | `dnull.xyz/latest_bs` (redirect to latest APK) |
| Release tag | `{version}-{commit}` e.g. `xx.yyy-(hash)` |
| Release title | `{version} ({commit})` e.g. `xx.yyy (hash)` |
| Old versions | Will be removed after new update/release |
