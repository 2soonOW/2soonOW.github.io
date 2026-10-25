# Naqui Ahmed — static personal website

This is a plain HTML/CSS GitHub Pages site. No Astro, npm, build step, or GitHub Actions workflow is needed.

## Publish
1. Extract this ZIP.
2. In the `2soonOW.github.io` GitHub repository, choose **Add file → Upload files**.
3. Upload **the contents of this folder**, including `index.html`, `style.css`, `writing/`, `pages/`, and `.nojekyll` (the hidden file is optional). Do not upload the parent folder itself.
4. Commit changes to `main`.
5. Go to **Settings → Pages** and set Source to **Deploy from a branch**, Branch `main`, Folder `/(root)`, then Save.
6. Open https://2soonOW.github.io after GitHub Pages publishes.

## Notes
- Only published WordPress posts and pages were exported. Draft/private items were excluded.
- WordPress XML contains media URLs, not image binary files. Images still point to the old WordPress hosting and may stop displaying if removed.
- Site uses Google Fonts when online, with system fallback fonts.
- To edit a page, edit its `index.html`.
