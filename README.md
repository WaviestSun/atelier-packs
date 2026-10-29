# atelier-packs

Copies of free third-party files that Atelier can download with `atelier get`. They are kept here because their
own sites have no stable direct link. Every file is CC0 and unchanged from the original download. Atelier checks
each one against its SHA-256 before using it.

## Universal Animation Library (Standard)

By Quaternius. CC0 1.0 (https://creativecommons.org/publicdomain/zero/1.0/).
Source: https://quaternius.com/packs/universalanimationlibrary.html (downloaded from https://quaternius.itch.io/universal-animation-library on 2026-10-29).
Support the author: https://www.patreon.com/quaternius

Release `characters-1`:

| File | SHA-256 | What it is |
|---|---|---|
| Universal-Animation-Library-Standard.zip | cc73fc4e495b82958207316596317a3f40b9fa38065bde1027937452da537724 | The original zip, renamed from `Universal Animation Library[Standard].zip` |
| UAL1_Standard.glb | 69591853d817488edaa8fd9bf8fc1d821eaeaf789f8627b3cd23b41c4ed67997 | From the zip's `Unreal-Godot/` folder: one rigged mannequin and 43 animations, root motion off |
| UAL1_Standard_RM.glb | be684571ed655a1b892c2c07e6e2aeca053b606c442d34004adaf1d944090d01 | The same with root motion baked into every animation |
| License.txt | 6d01f55c6e4c49a2c9963e147e561945ae2c83958c8ca667d90a6bffdbfac061 | The licence file from the zip |
| README.txt | ccd02718886b5a57f10f0a8911a38cfe10c36880e1d6dfa3445923fba32d2a72 | The readme from the zip |

The `.glb` files are byte-for-byte the ones inside the zip. Check with `shasum -a 256`.
