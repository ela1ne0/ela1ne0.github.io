# Hero visuals (from Figma)

Put images you export from Figma here, then reference them in `index.html` in the hero section.

## Exporting from Figma

1. In Figma, select the frame or elements you want to use.
2. In the right panel, open the **Export** section (or right‑click → **Export**).
3. Choose format:
   - **PNG** or **JPG** – good for illustrations, mockups, photos (use 1x or 2x for retina).
   - **SVG** – good for icons and simple graphics (stays sharp at any size).
4. Click **Export** and save the file into this folder: `assets/hero/`.

## Using them on the site

In `index.html`, inside the `<div class="hero-visuals">` section, add an `<img>` for each export, for example:

```html
<img src="assets/hero/your-figma-export.png" alt="Description" class="hero-visual" />
```

You can add or remove as many images as you like; the layout will adapt.
