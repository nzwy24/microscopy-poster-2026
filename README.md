# Fluorescence Microscopy — Poster media page

This package is a static webpage suitable for GitHub Pages or an HTTPS-accessible university web server. All five media sequences came from the supplied GIF.zip. No external JS/CSS dependencies are used.

## Upload with GitHub Pages (web browser)
1. Extract this ZIP. Upload the **contents of the extracted folder**, not the ZIP itself.
2. Create a **public** GitHub repository, for example `microscopy-poster-2026`.
3. In the repository, use **Add file > Upload files** and upload `index.html`, the `media/` and `posters/` folders (select or drag all extracted files so folder structure is preserved). If `.nojekyll` is difficult to upload, it is optional for this site.
4. Open **Settings > Pages > Build and deployment > Source: Deploy from a branch**, choose **main** and **/(root)**, then Save.
5. When published, the URL follows this pattern: `https://USERNAME.github.io/microscopy-poster-2026/`.
6. Verify it on a mobile phone (preferably mobile data, not only campus Wi-Fi). Generate a QR code from the **published URL**, not the repository URL.

## Upload to a university server
Copy all extracted files and folders unchanged to a publicly accessible directory, and open the resulting HTTPS URL ending in `/index.html` (or its parent directory when index files are enabled). Confirm off-campus access without a login.

## Scientific / privacy considerations
Confirm with the laboratory or supervisor that publicly sharing microscopy images is permitted before uploading. Avoid embedding sensitive, unpublished, or personally identifying material. For permanent poster QR codes, make sure the host URL will remain active after the conference or graduation.

## Important
Do not rename files without editing the corresponding relative URLs in `index.html`.

Light version: MP4 files were transcoded for bandwidth-efficient playback (H.264, CRF 22); these files are visually compressed and are not intended for quantitative fluorescence measurements. Original GIF sequences remain available in the separate original-GIF package.
