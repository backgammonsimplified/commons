# Technology Commons logo and emblem assets

This folder contains the source-of-truth brand assets for Technology Commons.

## Usage rule

- Use the **AA logo** for favicons, navbar branding, avatars, and any rendered use below roughly **130 px**.
- Use the **full Commons emblem** for larger website placements, course/teaching materials, signs, posters, and other contexts where the lighthouse, waves, growth, and roots remain legible.

## `logo/`

The AA mark is a deliberately simple arrow/A structure derived from the original hand-drawn mark.

- `aa-logo.svg`: canonical black SVG
- `aa-logo-black.svg`, `aa-logo-white.svg`: explicit monochrome variants
- `aa-logo-transparent.png`: black mark on transparent background, 512x512
- `aa-logo-white-background.png`: black mark on white, 512x512
- `aa-logo-white-transparent.png`: white mark on transparent background
- favicon, Apple touch icon, and web app icon exports
- `aa-logo-fabrication.svg` and `.dxf`: simplified fabrication/CAD versions

## `emblem/`

The full emblem contains the lighthouse/AA structure, gold growth/leaves and roots, blue waves, and circular frame.

- `commons-emblem.svg`: canonical full-colour vector
- transparent and white-background PNG exports, 1024x1024
- navy monochrome versions
- light/off-white monochrome versions using `#FAF7F2`
- fabrication SVG and DXF

## Colours

- Commons navy: `#062650`
- Commons gold: `#D49A00`
- Light/off-white: `#FAF7F2`
- AA black: `#111111`
- White: `#FFFFFF`

## Fabrication

The fabrication SVG/DXF files avoid fonts and raster images and use simple closed/outlined geometry suitable for:

- vinyl cutting
- laser cutting or engraving
- CAD import
- extrusion or stamp preparation in Onshape

For a 3D printed stamp, import the AA or emblem fabrication SVG/DXF into Onshape, clean/scale as required, then extrude the positive or negative geometry.

## Notes

The SVG files are the source of truth. Use PNG only where SVG is unsupported.
