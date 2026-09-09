# Shilalekh — 100 Inscriptions of the World

**Shilalekh** is a single-page epigraphy website for exploring, searching, selecting, and translating a curated collection of 100 deciphered inscriptions.

## Features

- 100 inscription entries.
- 30 entries from India and 70 from the rest of the world.
- Search by inscription name, location, era, or script.
- India / World filtering.
- Selection of multiple inscriptions.
- Translation into 27 target languages.
- Bright, colourful, responsive interface.
- SVG favicon and site icon.
- No build system or framework required.
- Suitable for GitHub Pages.

## Project structure

```text
Shilalekh/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── favicon.svg
    └── site-icon.svg
```

## Run locally

You can open `index.html` directly in a modern browser.

For the most reliable translation requests, use a local web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Make sure `index.html` is in the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`.
7. Save and wait for GitHub Pages to deploy.

Your site will normally appear at:

```text
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
```

## Translation

The translation feature uses online translation services from the browser. Therefore, visitors need an internet connection for live translations.

Translation quality can vary, particularly for ancient, archaic, highly technical, or context-dependent material. The site should not be treated as a substitute for a critical epigraphic edition or specialist scholarly translation.

## Important scholarly note

The website presents inscription information for educational exploration. Some ancient inscriptions have complex textual histories, disputed dates, reconstructed readings, or multiple scholarly interpretations. Important academic work should be checked against specialist editions and epigraphic scholarship.

## License

No license is asserted by this project unless the repository owner adds one. If you publish third-party material, verify the applicable copyright and data-use terms before distributing it.
