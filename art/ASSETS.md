# Original prototype assets

Created using the built-in imagegen tool for this MathRider prototype. The user's reference images informed the overall art direction; they are not embedded as game assets.

## coast.png

Prompt: "Use case: stylized-concept. Asset type: production background image for a modern 16-bit pixel art synthwave driving game called MathRider. Wide 16:9 landscape, perfectly horizontal straight rear-view driving camera facing horizon; this is ONLY the scenery layer, NO ROAD, NO CAR, NO TEXT, NO UI. Beautiful carefully crafted crisp square pixel art, midnight navy and violet starry sky upper 58%, large glowing striped pink to peach sunset sun centered at x50%, y47%, mountain silhouettes far left and middle, illuminated futuristic cyan magenta violet city skyline on right quarter, a few silhouetted palms very far left and right edges. The distant coastline/horizon must be a perfectly level line at approximately 60% image height. Bottom 40% consists of flat calm dark violet ocean water with tiny horizontal cyan and magenta pixel reflections, no foreground objects. All foreground elements will be rendered separately in code so there must be no perspective highway, car, railings, interface, logo, typography or watermarks anywhere. Saturated cyan hot pink violet peach accents against dark navy, beautifully atmospheric but retain plenty of dark negative space upper centre for interface overlays. Highly polished original pixel art game background with consistent pixel clusters and attractive layered cloud formations. No photorealism. Original assets."

## car.png

Transparent background enabled.

Prompt: "Use case: stylized-concept. Asset type: production transparent car sprite for MathRider modern 16-bit inspired pixel art synthwave racing browser game. A SINGLE isolated futuristic 1980s wedge sports car shown EXACTLY FROM THE REAR, symmetrical dead-centre straight rear view, camera slightly above the boot/trunk so rear window and roof visible, like a classic behind-the-car arcade racer. Original dark graphite body with sharp angular pixel shapes, cyan contour highlights, bright hot-magenta segmented horizontal taillights, dark rear window with cyan horizontal louvres, low wide body and large black tyres on both sides. Highly polished pixel art with crisp obvious consistent square pixel clusters, approximately 240 pixels of actual detail across the car, nearest-neighbour upscale. Wide rectangular composition, car fully visible and occupies 85% of image width, clear empty transparent margin around all sides. Absolutely transparent background, no landscape, no floor, no ground shadow, no text, no logo, no UI, no other cars, no 3/4 view, no front view. Do not include extensive glows outside car silhouette; those are rendered separately in engine. Original art in navy indigo graphite cyan magenta palette matching a neon coastal highway."


## Second polish dashboard

`dashboard-v1.png`: transparent pixel-art instrument housing generated with built-in image_gen. Exact prompt: `docs/dashboard-prompt.json`. Blank bays are populated with live UI; no numerical information is embedded in the raster. Original generated PNG retained without edits.

- `dashboard-v2.png`: built-in imagegen edit of dashboard-v1, adding an empty recessed timer channel for Arcade. Exact prompt: `docs/dashboard-timer-prompt.json`. Transparent source retained unmodified.

- `question-console-v1.png` and `control-console-v1.png`: original built-in imagegen outputs matching dashboard-v2. Exact prompts in `docs/question-console-prompt.json` and `docs/control-console-prompt.json`; transparent source PNGs retained unmodified.

- `menu-frame-v1.png`: built-in imagegen single-panel frame, dashboard-v2 style reference, retained unmodified. CSS nine-slices the border for menus. Exact prompt: `docs/menu-frame-prompt.json`.

- car-drift-sideways-v1.png: four transparent stronger drift poses, generated with built-in image_gen using car-drift-sixteen.png as identity reference. Exact prompt: ../../docs/drift-sideways-prompt.json. Original generated atlas retained unchanged; runtime crops are in src/game/drift-sideways-frames.json.
