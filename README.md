# hyperwallet-content

Rebranded mirror of the FAQ, Edu and Guides content used by the Hyper Wallet Android app.

## Sources

| Path | Upstream | Ref |
|---|---|---|
| `faq.json`, `faq/` | https://github.com/horizontalsystems/unstoppable.money | `main` @ `46b72e7340d8aa8b8bf692e40afde4510ee2909a` |
| `edu.json`, `edu/` | https://github.com/horizontalsystems/unstoppable.money | `main` @ `46b72e7340d8aa8b8bf692e40afde4510ee2909a` |
| `guides/` | https://github.com/horizontalsystems/blockchain-crypto-guides | tag `v1.2` @ `3160a4fe507adbd8ffd869b3d21377d7ff23b684` |

Only files referenced by `faq.json`, `edu.json` and `guides/index.json` (plus images linked from those markdown files) are included. Relative paths are unchanged, so the app resolves markdown and images relative to each JSON file.

## Changes from upstream

Text only (titles and markdown prose, all languages):

- "Unstoppable Wallet" / "Unstoppable" → "Hyper Wallet"
- "Horizontal Systems" → "Buckleson"

URLs, link targets, e-mail addresses, file paths and image paths are not modified. Upstream references that point to files missing upstream are left as they are.

## App URLs

- `FAQ_URL`: `https://raw.githubusercontent.com/buckleson/hyperwallet-content/main/faq.json`
- `EDU_URL`: `https://raw.githubusercontent.com/buckleson/hyperwallet-content/main/edu.json`
- `GUIDES_URL`: `https://raw.githubusercontent.com/buckleson/hyperwallet-content/main/guides/index.json`

## Licence

The guides content is distributed under the MIT License; the original notice is kept in [`guides/LICENSE`](guides/LICENSE) (Copyright (c) 2020 Horizontal Systems). The upstream `unstoppable.money` repository ships no licence file at the mirrored revision.
