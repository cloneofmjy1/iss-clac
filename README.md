GitHub Pages Deploy Notes

This folder is a publish-ready copy of the calculator for GitHub Pages.

Files:
- `index.html`: hosted entry point copied from `../domestIQ v2.html`

Recommended deploy flow:
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder.
6. Save, then wait for GitHub Pages to publish the site.

Notes:
- This version keeps the full standalone HTML structure, which is better for direct hosting than the Wix embed snippet.
- It still depends on HTTPS CDN resources for Tailwind, jsPDF, Google Fonts, and Material Symbols.
