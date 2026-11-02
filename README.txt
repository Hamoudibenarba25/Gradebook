GradeBook Pro v9 — Live Evaluation + Shared Student Roster

Includes:
- Existing Term 1 marks/data preserved using the same storage key.
- Student names/roster shared across Term 1, Term 2, and Term 3.
- Student additions, removals, and name edits synchronize across terms.
- Marks remain term-specific; adding/editing roster entries does not copy marks between terms.
- Evaluation subtotal updates immediately while entering criteria. Partial subtotal is labeled “partial”.
- Existing report export, backup, and app features retained.

GitHub Pages update:
1. Export a JSON backup from the current app before updating.
2. Extract this ZIP.
3. Replace index.html and service-worker.js in the root of your GradeBook GitHub repository.
4. Commit the changes and wait for GitHub Pages to deploy.
5. Open the website in Chrome and hard-refresh (Ctrl+Shift+R), then reopen the installed app.

Important:
- Keep student records in local browser storage; do not upload student backups to GitHub.
- Term 1 data remains in the existing Term 1 storage key.
- The shared roster is local to the same browser/device. This update does not sync records between devices.
