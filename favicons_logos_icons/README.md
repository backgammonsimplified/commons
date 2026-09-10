# Technology Commons brand assets

This folder contains the Technology Commons visual identity assets. SVG files are the source of truth. PNG files are exports for software that does not handle SVG reliably.

## Usage rule

- Below approximately **130 px**, use the **AA mark** in `logo/`.
- At larger sizes, use the **Commons emblem/seal** in `emblem/` when the extra detail is useful.
- The AA mark is the favicon and compact navigation/avatar mark.
- The full emblem is intended for the homepage, course landing pages, posters, signs, worksheets, and larger graphics.

## Colours

- Commons navy: `#022751`
- Commons gold: `#CF9713`
- Light gold: `#F4D98C`
- Warm off-white: `#FAF7F2`
- AA black: `#111111`
- White: `#FFFFFF`

## `logo/`

- `aa-logo.svg`: canonical AA logo, black, transparent background.
- `aa-logo-black.svg` / `aa-logo-white.svg`: black and white vector variants.
- `aa-logo-transparent.png`: 512 x 512 black AA on transparency.
- `aa-logo-white-background.png`: 512 x 512 black AA on white.
- `aa-logo-white-transparent.png`: 512 x 512 white AA on transparency.
- `technology-commons-lockup.svg`: AA mark with Technology Commons wordmark, with lettering converted to vector paths.
- `favicon.svg`, `favicon.ico`, `favicon-96x96.png`: browser icons.
- `apple-touch-icon.png`: 180 x 180.
- `web-app-manifest-192x192.png` / `web-app-manifest-512x512.png`: application icons.
- `aa-logo-fabrication.svg` / `.dxf`: simplified fabrication masters for vinyl, laser, or CAD import.

## `emblem/`

- `commons-emblem.svg`: canonical full-colour emblem with a transparent exterior and white field inside the ring.
- `commons-emblem-transparent.png`: 1024 x 1024, transparent outside the seal.
- `commons-emblem-white-background.png`: 1024 x 1024 on white.
- `commons-seal.*`: compatibility aliases for the full emblem naming used in planning notes.
- `commons-emblem-monochrome-blue.svg`: one-colour navy version.
- `commons-emblem-monochrome-light.svg`: one-colour `#FAF7F2` version for dark surfaces.
- Matching transparent and white-background PNG exports are included.
- `commons-emblem-monochrome-light-navy-background.png`: preview/use case for the light mark on navy.
- `commons-emblem-fabrication.svg` / `.dxf`: one-colour fabrication versions for vinyl, laser, CAD, embossing, and stamp workflows.
- `commons-social.png`: one static 1200 x 630 share image. There is no social-card generator.

## Fabrication notes

The fabrication SVGs contain no fonts, gradients, or embedded raster images. The DXF files are 2D outline geometry and can be scaled after import. For a 3D printed stamp, import the AA or emblem fabrication SVG/DXF into Onshape, create a sketch, then extrude the desired positive or negative relief.

The website SVGs may use colour or gradient styling. Use the fabrication variants when the process requires a single cut/engrave colour or closed geometry.

## Generated exports

`generate_brand_assets.py` creates the PNG, ICO, app-icon, compatibility alias, and static social-image exports from the vector masters. The generated raster files are committed to the repository so the website and external tools can use them without requiring a local render step.
