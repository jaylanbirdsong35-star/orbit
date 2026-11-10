# Orbit — Visual Identity Website

A responsive static visual identity site for Orbit, ready for GitHub Pages. No build tools required.

## Publish to GitHub Pages
1. Create a new **public** GitHub repository named `orbit-identity`.
2. Upload **index.html**, **style.css**, **script.js**, and the **assets** folder to the repository root. Commit changes.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then **Save**.
6. Wait for deployment. Your website URL will be `https://YOUR-USERNAME.github.io/orbit-identity/`.

## Add your approved artwork
- `assets/orbit-logo.svg`: approved Orbit wordmark (automatically replaces the text preview in Logo section).
- `assets/photo-1.jpg` through `photo-3.jpg`: Photography section.
- `assets/app-1.jpg` through `app-6.jpg`: Applications section.

Files must use these exact names, or update the paths in `script.js`.

## Update brand colors
In `style.css`, edit the `:root` values for `--cream`, `--ink`, `--pink`, and `--pale`. Current colors are placeholders until confirmed against the official palette.

## Edit copy
Edit headings and paragraphs in `index.html`. Keep the HTML tags intact.

## Optional custom domain
In GitHub **Settings → Pages → Custom domain**, enter a domain you control. Configure DNS records with your domain registrar using GitHub's current Pages instructions. Do not change an existing live domain until you are ready to point it at this site.

## Notes
The logo in the top navigation is a temporary text rendering. Replace it with approved artwork if exact fidelity is needed. This site is an independent student concept, not an official service.
