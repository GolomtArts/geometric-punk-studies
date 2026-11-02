# Artwork validation review

Reviewed 2026-11-03. **Two artist-approved artworks out of twenty.** Studies 03–20 remain provisional.

## Approved inventory

| Artwork | Title | Source / type | Status | Edition |
| --- | --- | --- | --- | --- |
| 01/20 | Composition No. 8348 | CryptoPunk #8348 / Male | Artist-approved | 1/1 planned, not minted |
| 02/20 | Composition No. 4121 | CryptoPunk #4121 / Male | Artist-approved, final artwork | 1/1 planned, not minted |

## Image integrity

- #8348: PNG, 1254 × 1254 px, RGB, 8 bits/channel, 1,756,455 bytes. Original artwork, gallery copy, and all Study 01 metadata remain unchanged from main before this update.
- #8348 SHA-256: `7bb8b6d8990a09cf0c94079ed41ef9b1d23462e83a1d9267acfb2a1c88ca0d91`.
- #4121: supplied file is PNG, 1254 × 1254 px, RGB, 8 bits/channel, 1,437,315 bytes. Archived at `assets/works/composition-no-4121.png` and mirrored at `docs/assets/composition-no-4121.png`; both match the supplied file byte for byte. No conversion, resizing, cropping, recompression, or other modification.
- #4121 SHA-256: `b6d63e83b310b124cdbd593a5da7e27c939c854f8c5df1f7ad4a5578eb24c25d`.
- Earlier style-reference JPEGs remain separate and unchanged.

## Source verification

On 2026-11-03, the [official CryptoPunks #4121 page](https://www.cryptopunks.app/cryptopunks/details/4121) returned HTTP 200 and confirmed **Male** type and exactly six accessory traits: **Spots, Silver Chain, Chinstrap, Earring, Mohawk, Cigarette**. Type is not an additional accessory. No discrepancy with the artist-provided information was found.

The [Larva Labs catalog URL](https://www.larvalabs.com/catalog/cryptopunks/4121) and [Larva Labs archive URL](https://archive.larvalabs.com/cryptopunks/details/4121) were not accessible through the browsing tool during this update; they were not used as fresh evidence. The accessible current official detail page supplies all six names and the count. No collection-wide trait frequencies or rarity statistics were calculated.

Study 01’s prior verification is preserved: [Larva Labs catalog #8348](https://www.larvalabs.com/catalog/cryptopunks/8348) and [official archive #8348](https://archive.larvalabs.com/cryptopunks/details/8348) confirm Male and Cigarette, Buck Teeth, Classic Shades, Earring, Top Hat, Big Beard, Mole. Its metadata has not been rewritten or reinterpreted.

## Artistic principle

Preserve the original CryptoPunk silhouette, head proportions, facial structure, and neck extending directly to the lower canvas boundary. Apply geometric abstraction primarily through internal color planes and structural divisions. Do not introduce additional shoulders or artificial neck extensions.

## Validation and restrictions

- All 20 JSON files parse. The CSV has 20 rows and seven columns. Study 02 title, source ID, six verified names, and approval status agree across records.
- Study 01 and Studies 03–20 metadata and CSV rows are unchanged. Study 02 blockchain fields are null; commercial derivative-rights review remains pending.
- Gallery: 20 cards, two approved images, 18 placeholders. CSS layout and `object-fit: contain` behavior are preserved; Study 01’s rendered card is unchanged. Image paths and dimensions resolve to the archived originals.
- Source research is preserved as historical comparison, with #4121’s later approval recorded. README, gallery documentation, and protocol now reflect two completed works.
- GitHub Pages remains disabled. No deployment workflow, contracts, or minting were added or executed. Intellectual-property and derivative-rights notices remain in place.
