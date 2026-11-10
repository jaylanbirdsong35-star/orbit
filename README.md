# Orbit Visual Identity — Editable Website v4

## What's new
- Dedicated Orbit logomark upload area in Strategy, plus the primary logo and logomark in the Logo tab.
- 12 applications, each with a main image and 3 additional images (48 application image spaces total).
- Fixed published image/text/color loading: exported JSON state is placed **before** script.js, so images load when the published website opens.
- Browser draft saves now use IndexedDB (more capacity than localStorage). Exported index.html embeds images, text and color values.
- Download and restore a JSON backup of edits.

## Editing and publishing
1. Open the site, choose **Edit site**.
2. Click any image area to upload, and click highlighted text to edit. Use the color controls to change hex values.
3. Click **Save on this browser** to keep a local draft. Browser drafts only work on that browser/device and are not published.
4. Click **Download updated website**. Your browser should download a new **index.html** with images embedded. For reliability, keep a copy of the **editable backup (JSON)** too.
5. On GitHub, open your repository, click **index.html**, choose the pencil icon, then paste the updated file contents, OR use GitHub's upload/replace workflow. Commit changes. Keep style.css and script.js in the repository.
6. Wait for GitHub Pages to redeploy, then refresh your public website.

**Important:** The export is a single HTML file with embedded image data; dozens of high-resolution photos can produce a very large file. Uploaded photos are resized in the editor when possible. If the download is blocked, allow downloads for your site in the browser settings. GitHub's web editor can struggle with large HTML files; uploading with GitHub Desktop is preferable for large exports.

## Files
- index.html — site structure
- style.css — design and responsive layout
- script.js — navigation and editor
