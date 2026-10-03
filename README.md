# signature-one-archive-shard-25

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c03158.jsonl.gz` … `specs-c03267.jsonl.gz`
  (JAH-SPEC-473551 … JAH-SPEC-490050 — 16500 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry (lazy-loaded on demand).
- FROZEN: never write new chunks here; new drip chunks always land in the main repo.
