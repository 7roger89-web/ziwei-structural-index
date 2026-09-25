# Ziwei Structural Index v1

This public, artifact-only repository distributes the verified structural reference index for years **1924–1983**.

- 60 yearly SQLite partitions; 518,400 exact-key reference records.
- Structural chart data only. No interpretation prose and no full-text search (FTS).
- SQLite partitions are GitHub Release assets, never Git-tracked files.
- The dataset is reference-only. It is not an authoritative live Huyền Học Lab chart result; `chartParityProven=false`.
- Source corpus engine: `iztro 2.5.8`. Huyền Học Lab's live chart authority remains `SylarLong/iztro 2.6.1`.

The release tag `ziwei-structural-index-v1` contains the 60 yearly partitions, `ziwei-structural-index-manifest.json`, and `SHA256SUMS`. Use the manifest to select a partition and verify its bytes and SHA-256 before use. Do not infer a match from adjacent years or a similar Ganzhi.

Dataset attribution and license are in [ATTRIBUTION.md](ATTRIBUTION.md).
