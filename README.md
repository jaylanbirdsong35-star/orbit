# Orbit — Visual Identity Website

A responsive static website for Orbit's visual identity system. No build tools or installation required.

## Preview
Open `index.html` in a browser. Navigation uses hash links so it works locally and on GitHub Pages.

## Add images
Put your photos in `assets/` with these names:
- `photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg` for Photography
- `app-1.jpg` through `app-6.jpg` for Applications

Images automatically appear when files with those names are present. Until then, editable placeholders remain visible. Keep image proportions consistent (4:5 photography; 4:3 applications).

## Update branding
- Change color values at the beginning of `style.css` under `:root`.
- Replace demonstration logo elements in `index.html` with your approved SVG artwork; do not redraw the original logo from type.
- Edit headings, paragraphs, and section labels directly in `index.html`.
- The font is Space Grotesk loaded via Google Fonts.

## Publish with GitHub Pages
1. Create a public GitHub repository named `orbit-identity`.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder to the repository root.
3. Open Settings > Pages. Under Build and deployment select Deploy from a branch, `main`, `/(root)` and Save.
4. Visit `https://YOUR-USERNAME.github.io/orbit-identity/` after the deployment completes.

## Notes
This is a functional identity-system website template, not a replacement for the approved artwork. Logo demonstrations and starter palette should be updated against final brand assets.
