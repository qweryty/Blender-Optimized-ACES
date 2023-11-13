# Blender optimized ACES 1.2 OpenColorIO configuration
## Original repository
Original github repository can be found [here](https://github.com/AcademySoftwareFoundation/OpenColorIO-Config-ACES).

## About optimizations

- Using cg-config-v2.0.0\_aces-v1.3\_ocio-v2.2.ocio as base
- Added alias colorspaces for 
  - `sRGB` - alias to `sRGB - Texture`
  - `Linear Rec.709` - alias to `Linear Rec.709 (sRGB)`
  - `Non-Color` - alias to `Raw`

Missing color spaces:
- AgX Base Display P3
- AgX Base Rec.1886
- AgX Base Rec.2020
- AgX Base sRGB
- AgX Log
- Display P3
- Filmic Log
- Filmic sRGB
- Linear CIE-XYZ D65
- Linear CIE-XYZ E
- Linear DCI-P3 D65
- Linear FilmLight E-Gamut

**Attention!** This config doesn't aim to replicate the exact looks of vanilla blender, but to make transition to ACES workflow as painless as possible. Your older files **will** look different with this config, but this is intended behaviour.

