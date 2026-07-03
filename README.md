# Nulls Brawl APK mirror

> Mirror for [Obtainium](https://github.com/ImranR98/Obtainium) — **do not use this repo for anything else.**
> Looking for the official source? [Download from nulls.gg](https://nulls.gg/servers/nulls-brawl/download/)

[![Downloads](https://img.shields.io/github/downloads/Merennor/nullsb-releases/total?style=for-the-badge)](https://github.com/Merennor/nullsb-releases/releases)

Releases are published by a GitHub Actions workflow that downloads the latest APK from the official source (nulls.gg).

Nulls Brawl doesn't have an in-app updater. When a new version is released, the game prompts you to visit their website — and won't let you play until you update. With Obtainium, you can automate this: it checks for updates in the background and handles APK cleanup automatically.

## Setup

1. Paste `https://github.com/Merennor/nullsb-releases` as the app URL in Obtainium
2. Tap **Save**, then wait up to 5–10 minutes (**don't leave the app** or you may get an error)

That's it. Obtainium will notify you whenever a new release is available.

## How it works

| What | Detail |
|---|---|
| Source | `https://dnull.xyz/latest_bs` (redirects to latest APK) |
| Release tag | `{version}` e.g. `xx.yyy` |
| Release title | `{version} ({commit})` e.g. `xx.yyy (hash)` |
| Old versions | Removed after each new release |
