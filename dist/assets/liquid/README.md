# Media notes

These optimized local WebP/JPEG assets were derived from images already uploaded to the existing `loungebarliquid.com` WordPress media library. They are not hotlinked.

- `hero-cocktails.webp`, menu photography, and gallery photography: existing Liquid website uploads.
- `favicon.png`: existing Liquid website mark.
- `espresso.webp`: AI-generated Espresso menu photograph created for this project; no logo or text.
- `cold-drinks.webp`, `hot-drinks.webp`, `breakfast.webp`, `shisha.webp`: AI-generated category photography used as menu-item fallbacks; no logos or text.

## Replacing menu images

Every menu item uses its own file in `menu/`, named after its stable product ID. Keep the filename and WebP format when replacing an image. For example:

- Espresso: `menu/espresso.png`
- Cappuccino: `menu/cappuccino.png`
- Pizza Liquid: `menu/pizza-liquid.png`
- Blue Lagoon: `menu/blue-lagoon.png`

Recommended replacement size: square `640 × 640px`, WebP quality `80–85`, ideally below `200 KB`.

Before production launch, the owner should confirm image rights and replace any general menu photograph that does not depict the exact named product.
