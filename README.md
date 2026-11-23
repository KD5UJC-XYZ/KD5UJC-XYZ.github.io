# KD5UJC-XYZ.github.io

The KD5UJC.XYZ organisation's site, served at https://kd5ujc.xyz.

- `index.html`: the landing page.
- `pools/<ticker>.json`: the off-chain metadata of the stake pools the organisation runs (CIP-6 fields: `name` up to
  50 characters, `ticker` 3-5 characters, `description` up to 255, `homepage` up to 64). A pool's registration
  certificate commits to the file's exact bytes by their Blake2b-256 hash: editing a file needs the pool re-registered
  with the new hash, or explorers reject the metadata.
