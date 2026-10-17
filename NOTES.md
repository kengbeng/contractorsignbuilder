# Notes — Contractor Sign Builder

Overview
- Purpose: create entrance signage for contractor work areas with clear hazard, PPE and contact information.
- Implementation: single static `index.html` file contains all HTML, CSS, JavaScript and embedded images (data URIs). No build step required.

Key details
- Print target: A4 portrait. Print styles are in the file and tuned for common browsers.
- Accessibility: semantic markup and ARIA roles are used for key interactive areas. Validate accessibility when making changes.
- Data storage: form data is kept in the browser (export/import available). No server-side storage.

Maintenance checklist
- If adding symbols or images, prefer external files for maintainability and reference them with <img> tags.
- Consider extracting CSS and JS into separate files for easier editing and versioning.
- Add automated tests only if the app grows in complexity.

Potential improvements
- Split out assets to reduce HTML size and improve caching.
- Add localization support for multiple languages.
- Add CI to build/minify and deploy to GitHub Pages for easy sharing.
