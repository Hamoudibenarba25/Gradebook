GradeBook Pro v8 — Term separation and report export
Files to replace at the ROOT of the existing GitHub Pages repository:
- index.html
- service-worker.js

Important:
- Existing current GradeBook records are retained as Term 1 (same localStorage key).
- Term 2 and Term 3 use separate local records on the same browser/device.
- Reports show the selected term.
- Each report has Print/Save PDF and Export Word (.doc) buttons below its report content.
- Word export is an HTML-based .doc file, compatible with Microsoft Word and LibreOffice.
- Before updating, export a JSON backup from Settings & Help.
