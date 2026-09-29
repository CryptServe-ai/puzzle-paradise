# Puzzle Paradise

One umbrella repository for three independent browser puzzles. Open `index.html` to choose a game. No installation or build step is required.

| Puzzle | Folder | Original repository |
| --- | --- | --- |
| Neighbourhood | `neighbourhood-puzzle/` | [CryptServe-ai/neighbourhood-puzzle](https://github.com/CryptServe-ai/neighbourhood-puzzle) |
| Feral But Flowering | `feral-puzzle/` | [CryptServe-ai/feral-puzzle](https://github.com/CryptServe-ai/feral-puzzle) |
| A Picture of Peace | `peace-puzzle/` | [CryptServe-ai/peace-puzzle](https://github.com/CryptServe-ai/peace-puzzle) |

Each folder contains the original game, artwork, and README. The game files are unchanged, so their controls and relative image paths continue to work. Use your browser’s Back button to return to the chooser. Feral uses optional Google Fonts; its game and artwork are local.

## Local preview

Open the root `index.html` directly, or serve this directory:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Repository history

The default-branch histories of all three original repositories are retained through unsquashed merge commits. Original commits retain their authors and hashes. Source repositories remain independent; future changes are not automatically synchronized. Issues, pull requests, repository settings, and other GitHub metadata are not migrated.

Imported revisions:

- Neighbourhood: `cfd959e57f9cddaffaa707a3f5447123af67af28`
- Feral and Peace: see their respective import merge commit’s second parent for the exact original revision.

## Hosting

This is a static repository. It can be served from its root on any static host. To use GitHub Pages, select **Settings → Pages → Deploy from a branch → main → / (root)** in the new repository. Hosting is optional and is not enabled by this import.

## Artwork and licensing

Original artwork attribution and source documentation are retained in each puzzle folder. Consolidation does not grant a new license to the source code or artwork.
