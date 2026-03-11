# AGENTS.md

## Project
This repository is the controlled central registry for balamod.

## Purpose
This repo defines which Balatro mods are allowed to be recommended and installed by `balamod-cli`.

## Core rules
- Only include mods from the controlled GitHub owner `yuyue1015`, unless explicitly approved later.
- Forked mod repositories remain independent repositories.
- Do not convert mod sources into subdirectory repositories.
- Do not include arbitrary public mods outside the controlled ecosystem.
- This repo stores metadata only. It does not contain mod source code copies.

## Files this repo should maintain
- `mods.json`
- `packs.json`
- `categories.json`
- `tags.json`
- `schemas/mods.schema.json`
- `schemas/packs.schema.json`
- `policies/trusted-owners.json`
- `policies/install-rules.md`
- `README.md`

## Directory structure
```text
.
  README.md
  mods.json
  packs.json
  categories.json
  tags.json
  schemas/
    mods.schema.json
    packs.schema.json
  policies/
    trusted-owners.json
    install-rules.md
  changelog/
