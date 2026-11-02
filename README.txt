GradeBook Pro — Safer Marks & Reports (Upgrade v3)

Files:
- index.html: application
- manifest.webmanifest: installable PWA settings
- service-worker.js: offline cache (v3)
- icon-192.png / icon-512.png: app icons

New features:
1. Mark fields use text entry rather than HTML number controls, so mouse wheel / Arrow Up / Arrow Down / Page Up / Page Down cannot accidentally increment/decrement marks while the field is focused.
2. Marks are staged and require clicking Save in that student's row before they are committed.
3. Performance Report includes separate Holistic Average, Test, and Examination report views with mark distribution and summary statistics.

To update an existing GitHub Pages app:
- Download and extract this ZIP.
- In the GradeBook repository, upload/replace index.html, service-worker.js, manifest.webmanifest, icon-192.png, and icon-512.png in the repository root.
- Commit the changes.
- Wait for GitHub Pages deployment.
- Open the site, then reload. If the installed PWA shows the old version, close it completely, open the website in Chrome and reload once; service-worker cache version v3 should update.

Data safety:
This update changes app code only. It does not import or upload student data. Before replacing app files, export a JSON backup from the current app. Do not upload the backup to GitHub.
