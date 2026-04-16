![Viewers](https://bigyap.goatcounter.com/counter/TOTAL.svg?no_branding=1&style=%23gcvc-border%7Bfill%3A%230b1220%3Bstroke%3A%23222c3d%3B%7D%23gcvc%7Bfill%3A%23e5e7eb%3Bfont-family%3AInter%2CSegoe%20UI%2CArial%2Csans-serif%3B%7D%23gcvc-for%7Bfill%3A%239ca3af%3B%7D%23gcvc-views%7Bfill%3A%2360a5fa%3Bfont-weight%3A700%3B%7D)

# UEFN Themes

Custom Unreal Editor for Fortnite (UEFN) color themes as importable JSON presets.

## Repository Contents

- `Vapor.json` - dark blue/cyan theme.
- `VaporTeal_1.json` - dark teal variation of Vapor.
- `Purple.json` - dark purple-focused theme.
- `VerseDark.json` - dark indigo/verse-inspired theme.

Each file follows the UEFN theme preset format with:

- `Version` for schema versioning
- `Id` for unique theme identity
- `DisplayName` for UI name
- `Colors` containing `EStyleColor::*` mappings

## How To Use In UEFN

1. Download or clone this repository.
2. Pick a theme JSON file you want to use.
3. In UEFN, open theme/import settings for editor style colors.
4. Import the selected JSON file.
5. Apply and save the theme.

If your UEFN build exposes slightly different menu names, use the same flow: locate theme/style settings, import JSON, then apply.