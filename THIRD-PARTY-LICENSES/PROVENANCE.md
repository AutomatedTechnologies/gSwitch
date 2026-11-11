# Third-party provenance — gSwitch (Academy fork)

Filed 2026-11-11 under audit finding GS-F-06 (see
`files/pipeline/gSwitch-AUDIT.md` in the Academy program record). The root
`LICENSE` (MIT, © Cody Schrank) covers gSwitch's own original code only. The
two components below are incorporated under their own licenses; their texts
are now filed in this tree as recorded here.

## 1. gfxCardStatus — BSD 3-clause

- **Upstream:** https://github.com/codykrieger/gfxCardStatus (Cody Krieger)
- **License text filed at:** `THIRD-PARTY-LICENSES/gfxCardStatus-LICENSE.txt`
  — verbatim copy of the upstream repo's `LICENSE`, fetched 2026-11-11 from
  `https://raw.githubusercontent.com/codykrieger/gfxCardStatus/master/LICENSE`
  (GitHub blob `07d5ac82aa0d9edae88c1a0b75434a2913d192e8`; 1,493 bytes;
  SHA-256 `3dcc95f44e8b0f8334279cc12bc171de0a04123e51c4a277152282970673bd3f`).
  Copyright line as filed upstream today: "Copyright (c) 2010-2020, Cody Krieger".
- **Derived files in this tree** (copied/adapted from gfxCardStatus; before
  this filing they carried only a header comment linking the upstream
  LICENSE URL, citing its Jun 17, 2012 state, "Copyright (c) 2010-2012,
  Cody Krieger"):
  - `gSwitch/Core/GPUManager.swift` — GPU mux connect/state logic
  - `gSwitch/Core/GSProcess.h`
  - `gSwitch/Core/GSProcess.m` — discrete-GPU process scanner
  - `gSwitch/Util/Constants.swift` — the `GPUState`, `DispatchSelectors`,
    and `Features` enums (the app's GPU mux vocabulary)

## 2. Google Material icons — Apache License 2.0

- **Upstream:** https://github.com/google/material-design-icons (Google)
- **License text filed at:** `icons/LICENSE` — verbatim copy of the upstream
  repo's `LICENSE`, fetched 2026-11-11 from
  `https://raw.githubusercontent.com/google/material-design-icons/master/LICENSE`
  (GitHub blob `7a4a3ea2424c09fbe48d455aed1eaa94d9124835`; 11,357 bytes;
  SHA-256 `58d1e17ffe5109a7ae296caafcadfdbe6a7d176f0bc4ab01e12a689b0499d8bd`).
  Attribution for the icon set is in `icons/ATTRIBUTION.md`.
- **Covered material:** the brightness icon exports under `icons/`
  (`ic_brightness_auto_black_18dp`, `ic_brightness_high_black_18dp`,
  `ic_brightness_low_black_18dp` — Android/iOS/web densities), and the same
  three icons as used by the app in
  `gSwitch/Assets.xcassets/ic_brightness_*.imageset/`.
