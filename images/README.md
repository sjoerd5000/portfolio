# Image Organization

Each case study has its own folder with the following convention:

## Naming Convention
- `thumb-1.png`, `thumb-2.png`, `thumb-3.png`, `thumb-4.png` — Four polaroid-style thumbnails shown on the homepage (recommended: 800×600px each, 4:3 landscape aspect ratio)
- `carousel-1.png`, `carousel-2.png`, `carousel-3.png`, `carousel-4.png` — Four larger images for the case study overlay carousel (recommended: 1200×900px each, 4:3 landscape aspect ratio)
- Additional images can be named descriptively (e.g., `dashboard.png`, `user-flow.png`) and added to the `images` array in the JavaScript

## Folders
- `monks-flow/` — Monks.Flow enterprise AI platform
- `google/` — Google AI products portfolio
- `zoox/` — Zoox autonomous vehicle service
- `adidas/` — Adidas Locker Room marketplace

## Image Specs
- Format: PNG
- Thumbnails (thumb-1 through thumb-4): ~800×600px (4:3 landscape aspect ratio) — small versions for homepage polaroid stack
- Carousel images (carousel-1 through carousel-4): ~1200×900px (4:3 landscape aspect ratio) — larger versions for case study overlay
- Additional images: optimize for web (under 500KB each)

## Two Sets of Images

**1. Homepage Polaroid Stack (thumbnails):**
- Displayed as a playful polaroid stack on the homepage
- Rotated at slight angles and overlap horizontally
- On hover, they lift up slightly with enhanced shadows
- Creates a casual, portfolio-on-a-table aesthetic
- Uses: `thumb-1.png` through `thumb-4.png`

**2. Case Study Carousel (carousel):**
- Larger images shown in a minimal carousel on the case study overlay
- Simple dot navigation at the bottom
- Extends 20% wider than text column on larger screens for more visual impact
- Clean, focused presentation of project screens
- Uses: `carousel-1.png` through `carousel-4.png`
