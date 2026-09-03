# Allumeria Traditional Chinese Translation

Traditional Chinese (`zh-TW`) translation content and release distribution for Allumeria.

## Current release

- Translation version: `v1.0.0`
- Supported game build: `0.15.5`
- Community API: `1.x`
- Required runtime: `Allumeria-Mods/COMMUNITY-API-BRIDGE` release `0.15.5`

## Browse the translation

The public, release-synchronized translation snapshot is under:

```text
content/0.15.5/
├── keys.txt
├── info.json
└── community-mod.json
```

`keys.txt` is the exact Traditional Chinese translation pack shipped in the current `v1.0.0` release for Allumeria `0.15.5`.

## Installation

1. Install `COMMUNITY-API-BRIDGE` release `0.15.5`.
2. Download `Allumeria-Traditional-Chinese-Translation-0.15.5.zip` from this repository's `v1.0.0` release.
3. Extract the archive into the Allumeria installation root while preserving the archive paths.

The release archive contains the runtime DLL and glyph catalog in addition to the public translation content shown in this repository.

## Repository scope

This repository intentionally publishes reviewable translation content and release metadata, but not the private engineering project. Build tooling, C# implementation source, tests, compatibility research, acceptance evidence, SPEC documents, build overrides, and other engineering material remain in the private Engineering repository.

`distribution.json` is the machine-readable release index and records the exact translation artifact and required Bridge identities.
