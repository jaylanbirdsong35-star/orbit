# Orbit — Website (updated November 10, 2026)

## Upload the entire website to GitHub Pages

1. Unzip `orbit-website-gallery-update.zip`.
2. Open https://github.com/jaylanbirdsong35-star/orbit and select **Add file → Upload files**.
3. Open the unzipped folder on your computer, select **all the files inside** (Command+A / Ctrl+A), and drag them onto GitHub. **Do not drag the ZIP itself.**
4. Include `index.html`, `style.css`, `script.js`, **this updated `README.md`**, and every `.png`, `.jpg`, and `.mp4` file. **There is no assets folder**: all files belong at the repository root.
5. Click **Commit changes**. Check Settings → Pages is configured to deploy from the main branch / root.
6. Visit https://jaylanbirdsong35-star.github.io/orbit/#home and hard refresh after GitHub Pages deploys.

## What's changed

- Homepage artwork fills the full hero area, with the original full image shown without cropping and a blurred edge-to-edge background to fill any extra space.
- Strategy accent cards use lime rather than pink.
- Photography images span the entire grid without gaps and use `object-fit: contain` to preserve every part of the images.
- Applications have working previous/next arrows for projects with multiple supplied images, plus full descriptions visible on hover or keyboard focus.
- Application images are edge-to-edge by default; on hover the full image is shown without cropping.
- The application text is taken from `Applications information.pdf`. The interactive-floor image wasn't supplied, so that project has a placeholder.
- Original logo layout, navigation and overall site structure are retained.

## Troubleshooting

If photos do not appear, open a photo URL directly, for example: https://jaylanbirdsong35-star.github.io/orbit/home-background-landing.png . If that URL is missing, the image file wasn't uploaded to the repository root. README files do not upload images automatically.
