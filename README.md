# Repository Views
![Viewers](https://bigyap.goatcounter.com/counter/TOTAL.svg?no_branding=1)

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