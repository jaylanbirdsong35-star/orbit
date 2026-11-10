# ORBIT — WEBSITE PACKAGE (IMAGES INCLUDED)

**This README has been updated for the complete website upload.**

## IMPORTANT: How to publish on GitHub Pages

1. Download and **unzip** `orbit-github-fixed.zip` on your computer.
2. Open your GitHub repository `jaylanbirdsong35-star/orbit`.
3. Choose **Add file → Upload files**.
4. Open the unzipped `orbit-github-fixed` folder. Select **all four items together**: `index.html`, `style.css`, `script.js`, and the `assets` folder. Drag the selected items into GitHub's upload area. **Do not upload only the README or only index.html.**
5. Also upload this updated `README.md` (or select all five items together).
6. Scroll down and click **Commit changes**. Wait for GitHub Pages to deploy, then refresh the site (hard refresh: Cmd+Shift+R on Mac).

**The `assets/` folder must be visible at the repository root next to `index.html`.** Check that GitHub displays `assets/home-background-landing.png`, for example. If `assets` is missing, the images will not show.

Your repository root should look like:

```
index.html
style.css
script.js
README.md
assets/
    home-background-landing.png
    ... other images ...
```

## What was fixed

The previous ZIP used image filenames like `home-background-landing-png` **without a real `.png` extension**. GitHub Pages can serve those with the wrong content type, causing the browser to refuse to display them. This package gives every image its correct extension and updates every image path in the HTML. All supplied images are included.

The original website interface, navigation and image-container sizes remain unchanged. Image fitting uses `contain` so the full image is visible without cropping or stretching. Blank space may appear around differently proportioned images.

## If you still see no images

- Verify that the `assets` folder actually appears in the GitHub repository root.
- Try opening `https://jaylanbirdsong35-star.github.io/orbit/assets/home-background-landing.png` directly. If it shows a 404, the assets folder is not published at the correct location.
- Use a private/incognito window to avoid browser-local editing drafts masking the published version.
- GitHub Pages publishes files from the configured branch/folder in **Settings → Pages**. Make sure it uses the branch where you uploaded these files and `/(root)`.

All copy is based on the supplied PDF. Unfilled project image slots remain unfilled.
