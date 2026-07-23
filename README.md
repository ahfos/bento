# BENTO

A single-page, fully client-side bento grid generator.

Drop in a few images and it instantly lays them out on a fixed-column grid
(6 columns desktop, 2 mobile) with `grid-auto-flow: dense`, using a small,
deliberate tile vocabulary — Hero (2x2), Wide (2x1), Tall (1x2), Standard
(1x1) — assigned from each image's aspect ratio. Drag to reorder, click a
tile's size chip to cycle/pin its shape, then export the result as a PNG
or a self-contained SVG.

Everything runs in the browser: reading files, classifying aspect ratios,
laying out the grid, cropping for export. Nothing is uploaded, stored, or
sent anywhere — closing the tab clears it all.

Live: https://ahfos.github.io/bento

Made by [ahfos](https://www.ahfos.com).
