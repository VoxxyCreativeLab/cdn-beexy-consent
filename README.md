# cdn-beexy-consent

Public CDN distribution repo for **Beexy Consent** (Voxxy Creative Lab), served via jsDelivr at `@v1`.

This repo is a distribution mirror. The single source of truth for all code and config is the private
development repo. Do not edit files here directly; they are synced from source on each release.

## Served assets

| Path | Purpose |
|---|---|
| `beexy-consent.js` | Banner script (injected by the GTM template) |
| `beexy-global.json` | Global legal config (regions, models, categories, English texts) |
| `lang/{lang}.json` | Per-language UI strings + duration lexicon |
| `cookies-{small,medium,large}.json` | Cookie database tiers |
| `cookie-purposes/{tier}/{lang}.json` | Translated cookie-purpose descriptions (lazy-loaded) |
| `assets/*` | Badge / logo images |

A new semver tag is pushed on every release so jsDelivr `@v1` serves the latest code.
