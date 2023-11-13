# Blender optimized ACES 1.2 OpenColorIO configuration
## Original repository
Original github repository can be found [here](https://github.com/AcademySoftwareFoundation/OpenColorIO-Config-ACES).

## About optimizations

- Using cg-config-v2.0.0\_aces-v1.3\_ocio-v2.2.ocio as base
- Added alias colorspaces for 
  - `sRGB` - alias to `sRGB - Texture`
  - `Linear Rec.709` - alias to `Linear Rec.709 (sRGB)`
  - `Non-Color` - alias to `Raw`

**Attention!** This config doesn't aim to replicate the exact looks of vanilla blender, but to make transition to ACES workflow as painless as possible. Your older files **will** look different with this config, but this is intended behaviour.

