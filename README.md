# Orbit — GitHub Pages flat-file upload

This package is specifically designed for GitHub's **Add file → Upload files** workflow when folders do not upload correctly.

## Upload every file (including README.md)

1. Download and **unzip** this package on your computer.
2. Open your GitHub repository `jaylanbirdsong35-star/orbit`.
3. Choose **Add file → Upload files**.
4. Open the unzipped folder, select **ALL files** inside (Command+A / Ctrl+A), and drag them onto GitHub. **There is no assets folder**. Every image, video, HTML, CSS, JS and this README is at the same level.
5. Scroll down and select **Commit changes**. Allow GitHub Pages a few minutes to publish, then hard refresh.
6. If an old `assets` folder remains in GitHub, it is no longer used by this version and can be left alone.

**Important:** Upload the actual files, not the ZIP itself. `index.html` and every image should appear in the **root of the repository**, next to this README. GitHub Pages does not read the README to create or upload files; it only displays instructions.

## What changed

- All image and video references now point to files at repository root; no folder upload required.
- Strategy no longer displays a logomark above the six strategy cards.
- Logo page: two primary logo versions side by side, then scroll to two logomark versions side by side.
- Original interface, page navigation and logo stage sizes are preserved. Images use `contain` to avoid cropping or distortion.

## Troubleshooting

If images are absent, open `https://jaylanbirdsong35-star.github.io/orbit/home-background-landing.png` directly. If you see 404, the file has not been uploaded to the repository root or GitHub Pages has not published yet.

If your browser shows an old draft, test in a private/incognito window. Do not clear browser data unless you have backed up local edits.
