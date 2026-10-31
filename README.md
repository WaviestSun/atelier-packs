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

## Release `packs-2` (2026-10-31)

Unchanged copies of five CC0 zips, downloaded on 2026-10-31 from the authors' own pages. Each zip's own licence file says CC0 1.0. Atelier takes only named folders out of them, checked against the SHA-256 below.

| File | SHA-256 | Source |
|---|---|---|
| Universal-Animation-Library-2-Standard.zip | 4008ea208a604773a2b2177d965f0f5d3195498b5bf838c3f5785d68e95f2a68 | Quaternius, Universal Animation Library 2 (Standard), https://quaternius.com/packs/universalanimationlibrary2.html, renamed from `Universal Animation Library 2[Standard].zip` |
| Universal-Base-Characters-Standard.zip | fdbf1804c90dfc1ea03e992bff7da2dfd1a79318e13270a660180f9308455f40 | Quaternius, Universal Base Characters (Standard), https://quaternius.com/packs/universalbasecharacters.html, renamed from `Universal Base Characters[Standard].zip` |
| kenney_furniture-kit.zip | e67652d0932cee41683f74711c03d3e192a2af9979ef8e6b237711f5482d46b0 | Kenney, Furniture Kit 2.0, https://kenney.nl/assets/furniture-kit |
| kenney_nature-kit.zip | fa7974a0d342bfe63c38664ba9f8ec1a4aab8ea25f099bdc56870e33588c4d9d | Kenney, Nature Kit 2.1, https://kenney.nl/assets/nature-kit |
| kenney_food-kit.zip | cdad90853682499b94c9fda2f87678b24bfd8f3264e0ed323f6b6a27fd7c6f6f | Kenney, Food Kit 2.0, https://kenney.nl/assets/food-kit |

Support the authors: https://www.patreon.com/quaternius and https://kenney.nl/donate
