# Asset attribution

Every non-code asset in this repository (images, icons, fonts, example drawings, presets) is listed
here with its author, source and licence. `cargo xtask assets` (part of `cargo xtask ci`) fails if
an asset file is missing from this table.

**Policy (mandatory):** CADCraft contains **no Autodesk, Adobe or Avid iconography, images,
artwork, fonts, hatch patterns, linetypes, templates or presets.** Every asset is original work by
CADCraft contributors or third-party material under an open licence (OSI open source, public domain
/ CC0, or Creative Commons that allows redistribution). Screenshots of Autodesk software are never
committed. Font files are not added here: shared fonts live in
[storytold/craft-fonts](https://github.com/storytold/craft-fonts), an optional build input. The one
exception is the Unigreen brand (`assets/brand/` and the app icon in `assets/app-icon/`, the Unigreen
three-leaf mark on a Unigreen dark tile with the app label): trademarks of Unigreen Power Co., Ltd.,
not covered by MIT OR Apache-2.0 (see NOTICE).

Generated-in-code assets are original and have no file to list:
- the UI icon set (`crates/ui-egui/src/icons.rs`);
- the "CADCraft Stroke" single-stroke drafting font (`crates/fonts/src/stroke.rs`);
- the standard linetype and hatch-pattern libraries (`crates/doc/src/library.rs`; industry-common
  names, our own dash/spacing values);
- the colour index palette, generated from its structure (`crates/color/src/lib.rs`);
- the sample drawings (`crates/engine/src/sample.rs`).

| Asset | Author | Source | Licence | Notes |
|---|---|---|---|---|
| `assets/app-icon/hicolor/128x128/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/16x16/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/24x24/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/256x256/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/32x32/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/48x48/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/512x512/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/hicolor/64x64/apps/ai.storyteller.cadcraft.png` | Unigreen Power Co., Ltd. | generated from `assets/app-icon/cadcraft-1024.png` | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Linux hicolor icon |
| `assets/app-icon/cadcraft.icns` | Unigreen Power Co., Ltd. | generated (packaging/icons.sh) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; macOS icon |
| `assets/app-icon/cadcraft.ico` | Unigreen Power Co., Ltd. | generated (packaging/icons.sh) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label; Windows icon |
| `assets/app-icon/cadcraft-64.png` | Unigreen Power Co., Ltd. | generated | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label |
| `assets/app-icon/cadcraft-256.png` | Unigreen Power Co., Ltd. | generated | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label |
| `assets/app-icon/cadcraft-1024.png` | Unigreen Power Co., Ltd. | generated | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label |
| `assets/app-icon/cadcraft-macos-512.png` | Unigreen Power Co., Ltd. | generated (macOS margin variant) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | the Unigreen three-leaf mark on a Unigreen dark tile with the app label |
| `packaging/macos/dmg/background.svg` | Unigreen Power Co., Ltd. (layout and generator originally by @XusBadia) | Unigreen DMG window background (Unigreen logo, app icon and app name; text outlined Inter), written by Unigreen's make_dmg.py | Unigreen logo and icon: Unigreen trademark (see NOTICE); layout: MIT OR Apache-2.0 | Finder window background of the macOS DMG; `packaging/macos/dmg/generate.py` renders it to `background.tiff` (see `packaging/macos/dmg/README.md`) |
| `packaging/macos/dmg/background.tiff` | Unigreen Power Co., Ltd. (layout and generator originally by @XusBadia) | Rendered from `packaging/macos/dmg/background.svg` by `packaging/macos/dmg/generate.py` | Unigreen logo and icon: Unigreen trademark (see NOTICE); layout: MIT OR Apache-2.0 | 1x + 2x HiDPI TIFF for the macOS DMG window; includes the app icon (see its row) and LittleCMS's built-in sRGB profile ("No copyright, use freely") |
| `examples/apartment.dxf` | CADCraft contributors | sample drawing made with cadcraft-cli commands | MIT OR Apache-2.0 | Original |
| `docs/images/ui-apartment.png` | CADCraft contributors | screenshot of CADCraft itself (examples/apartment.dxf) | MIT OR Apache-2.0 | Original; no Autodesk UI |
| `docs/images/ui-layout.png` | CADCraft contributors | screenshot of CADCraft itself (a layout of examples/apartment.dxf) | MIT OR Apache-2.0 | Original; no Autodesk UI |
| `docs/images/ui-bracket.png` | CADCraft contributors | screenshot of CADCraft itself (sample drawing generated in code) | MIT OR Apache-2.0 | Original; no Autodesk UI |
| `assets/brand/unigreen-logo.svg` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen logo for light backgrounds; trademark, not open source |
| `assets/brand/unigreen-logo.png` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen logo for light backgrounds; trademark, not open source |
| `assets/brand/unigreen-logo-white.svg` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen logo for dark backgrounds; trademark, not open source |
| `assets/brand/unigreen-logo-white.png` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen logo for dark backgrounds; trademark, not open source |
| `assets/brand/unigreen-mark.svg` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen three-leaf mark; trademark, not open source |
| `assets/brand/unigreen-mark.png` | Unigreen Power Co., Ltd. | Unigreen logo (FINAL_LOGO.eps) | Unigreen trademark; not covered by MIT OR Apache-2.0 (see NOTICE) | Unigreen three-leaf mark; trademark, not open source |

## Interface translations

| Asset | Author | Source | Licence | Notes |
|---|---|---|---|---|
| `crates/ui-egui/src/i18n/uk.tsv` | @dmatviichuk | Original Ukrainian translations of CADCraft English strings | MIT OR Apache-2.0 (`LICENSE-MIT`, `LICENSE-APACHE`) | No proprietary localization resources copied |
| `crates/ui-egui/src/i18n/de.tsv` | the CADCraft contributors | Original German translations of CADCraft English strings | MIT OR Apache-2.0 (`LICENSE-MIT`, `LICENSE-APACHE`) | No proprietary localization resources copied |
| `crates/ui-egui/src/i18n/es.tsv` | @PedroGuille | Original Spanish translations of CADCraft English strings | MIT OR Apache-2.0 (`LICENSE-MIT`, `LICENSE-APACHE`) | No proprietary localization resources copied |
| `crates/ui-egui/src/i18n/pt_br.tsv` | @WladmirJunior | Original Brazilian Portuguese translations of CADCraft English strings | MIT OR Apache-2.0 (`LICENSE-MIT`, `LICENSE-APACHE`) | No proprietary localization resources copied |
