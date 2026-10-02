# StackSpan Product Image License Notes

Every product image in this folder is a stock photo (Pexels or Unsplash) or a public-domain Wikimedia Commons file. Each one is credited below and has a row in `MANIFEST.csv`.

## Amazon product images: removed (2026-10-02 PT)

StackSpan no longer uses Amazon product images. All 61 Amazon-sourced files (35 masters and 26 table-thumb derivatives, covering 35 ASINs) were deleted from `public/images/products/`, `foot-tools/`, `sandbags/` and `shoes/`. Their `MANIFEST.csv` rows and license notes were removed at the same time, and the pages that showed them are now text-only. No Amazon image is hotlinked, embedded via SiteStripe or loaded through PA-API. Affiliate `/go/` links are unchanged. The earlier records are in git history before this change.

## Home movement kit thumbnails (2026-10-01 PT; stock photos, not Amazon images)

Generic product-type thumbnails for `/natural-fitness/home-movement-kit/`. Unlike the Amazon images above, these are **not** product detail page photos and are not tied to any ASIN. Source records are in the `thumb-*` rows of `MANIFEST.csv`.

Every photo comes from Unsplash (Unsplash License, free tier, not Unsplash+) or Pexels (Pexels License). Both licenses allow free commercial use and don't require attribution, but StackSpan credits them anyway. Each photo page was checked on 2026-10-01 (PT). The Unsplash pages showed "Free to use under the Unsplash License". The Pexels pages listed `license: https://www.pexels.com/license/`. No page had a premium, editorial-only, or restriction note. No Wikimedia Commons file was used: the only CC0/PD candidate (a white adhesive tape roll) was rejected, see MANIFEST.csv.

Edits: cropped to the product, background removed (rembg isnet-general-use), product contained on a pure #FFFFFF square with 6% padding, resized to 800/168/112, and saved as WebP with metadata stripped. Other changes: on the foam roller, a mat-shadow wedge was masked out by hand. On the wood blocks, out-of-focus loose blocks were removed and the edge was eroded. The dowel was rotated 45 degrees. Nothing else was retouched.

### Credits

- **thumb-spinlock-dumbbell**, `public/images/products/thumb-spinlock-dumbbell.webp` (+ -168/-112): Photo by [Zacharias Korsalka](https://www.pexels.com/@zacharias-korsalka-21691965/) on [Pexels](https://www.pexels.com/photo/black-dumbbell-on-white-background-for-fitness-38721839/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-tennis-balls**, `public/images/products/thumb-tennis-balls.webp` (+ -168/-112): Photo by [icon0 com](https://www.pexels.com/@icon0/) on [Pexels](https://www.pexels.com/photo/two-green-lawn-tennis-balls-226563/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-liquid-chalk**, `public/images/products/thumb-liquid-chalk.webp` (+ -168/-112): Photo by [Denio Rodríguez](https://unsplash.com/@deniosrphoto) on [Unsplash](https://unsplash.com/photos/a-white-bottle-on-a-blue-background-D12uIjOuNlM). License: Unsplash License (https://unsplash.com/license) - free, not Unsplash+.
- **thumb-cast-iron-kettlebell**, `public/images/products/thumb-cast-iron-kettlebell.webp` (+ -168/-112): Photo by [Jonathan Borba](https://www.pexels.com/@jonathanborba/) on [Pexels](https://www.pexels.com/photo/a-kettlebell-on-a-black-background-with-two-balls-27810157/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-foam-roller**, `public/images/products/thumb-foam-roller.webp` (+ -168/-112): Photo by [kasia kurosz](https://www.pexels.com/@kasia-kurosz-2150104848/) on [Pexels](https://www.pexels.com/photo/home-gym-equipment-on-yoga-mat-34213999/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-wood-blocks**, `public/images/products/thumb-wood-blocks.webp` (+ -168/-112): Photo by [Valery Fedotov](https://unsplash.com/@imlst) on [Unsplash](https://unsplash.com/photos/white-wooden-blocks-on-black-surface-CxE1H2_9B9s). License: Unsplash License (https://unsplash.com/license) - free, not Unsplash+.
- **thumb-wood-dowel**, `public/images/products/thumb-wood-dowel.webp` (+ -168/-112): Photo by [Maggie Zhan](https://www.pexels.com/@maggie-zhan-144531/) on [Pexels](https://www.pexels.com/photo/white-brushes-and-mops-on-white-surface-1676037/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-portable-speaker**, `public/images/products/thumb-portable-speaker.webp` (+ -168/-112): Photo by [Caleb Oquendo](https://www.pexels.com/@caleboquendo/) on [Pexels](https://www.pexels.com/photo/speaker-in-white-background-7772558/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-wood-gym-rings**, `public/images/products/thumb-wood-gym-rings.webp` (+ -168/-112): Photo by [Ivan S](https://www.pexels.com/@ivan-s/) on [Pexels](https://www.pexels.com/photo/pair-of-gymnastic-rings-4162441/). License: Pexels License (https://www.pexels.com/license/).
- **thumb-gymboss-timer**, `public/images/products/thumb-gymboss-timer.webp` (+ -168/-112): Photo by [Wolfgangus Mozart](https://commons.wikimedia.org/wiki/User:Wolfgangus_Mozart) via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:%C3%84ggklocka_Nilsjohan.jpg). License: public domain (PD-self). No attribution required.

The thumb-gymboss-timer image is a public-domain Wikimedia Commons file (`{{PD-self}}`, own work by User:Wolfgangus Mozart, wikitext checked 2026-10-01 PT). It shows a generic twist-dial kitchen timer standing in for the Gymboss. No attribution is required, but it is credited anyway.

Unfilled slots that stay hidden (`data-status="pending"`): thumb-long-loop-bands, thumb-athletic-tape, thumb-practice-ball-diy (to be photographed). The pack's thumb-athletic-tape image (a paper masking-type roll) was not used because it is the wrong kind of tape.
