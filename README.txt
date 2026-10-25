MEDIA VAULT
===========

Files
-----
index.html - the complete website. No build tools or dependencies are required.

Run locally
-----------
1. Double-click index.html, or open it in Chrome or Microsoft Edge.
2. Upload images/videos and create folders.
3. Use a folder's ... menu to rename, export, or delete it.
4. To move/share a folder, choose Export. It downloads a .vault.json file.
5. On another browser/device, open Media Vault, choose Import folder, and select that .vault.json file.

Deploy to GitHub Pages
----------------------
1. Create a GitHub repository (for example, media-vault).
2. Upload index.html to the repository root.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish and open the URL it provides.

Important storage and sharing limits
------------------------------------
- Images and videos are stored in IndexedDB in the browser on the current device/profile. Publishing the page does not upload the user's media to GitHub.
- Clearing site data, using a different browser profile, or browser storage eviction may remove local files. Export important folders as backups.
- This local-only version cannot create a true public folder URL that lets another person stream your locally stored media. A real shareable web link requires uploading the exported folder to a hosting/storage service and serving it from there, or adding a backend. The .vault.json export is the portable way to share/import a folder in this version.
- Very large exports may use substantial memory and may exceed browser storage or download limits. Keep exports manageable.
- Browser storage quotas vary. This page intentionally does not promise a fixed storage capacity.
