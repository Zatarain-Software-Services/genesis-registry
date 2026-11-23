# genesis-registry

Community registry index for [Genesis](https://github.com/Zatarain-Software-Services/Genesis) `gpm` packages.

Static JSON over HTTPS — no server required. Point a project at it with `"registry"` in `genesis.json` or `--registry` (see `docs/registry.md` in the Genesis repo for the format and trust model).

- `index.json` — package directory for `gpm search`/`info`
- `packages/<alias>.json` — per-package metadata and version sources

Package sources remain plain `github:` specifiers; this repo only maps aliases to sources.
