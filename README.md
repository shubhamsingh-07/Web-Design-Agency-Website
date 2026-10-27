# Creative Design Agency Landing Page

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A responsive, static landing-page exercise for a fictional creative design agency. Built with **HTML and CSS**, the page introduces two service areas—beauty and construction—with supporting imagery and short descriptions.

## Overview

The project focuses on presenting agency services through a simple editorial layout: a prominent headline, two content cards, supporting images, and a footer. The layout adapts for smaller screens using a CSS media query.

This repository includes two HTML/CSS pairs:
- **`index.html` + `style.css`** — the main implementation.
- **`solution.html` + `solution.css`** — a second/reference implementation kept in the repository.

## Features

- Responsive two-card landing page.
- Distinct service sections for Beauty and Construction.
- Local logo and image assets.
- Typography loaded from Google Fonts (Poppins).
- Mobile layout adjustments for screens at or below 680px.
- No JavaScript, package installation, or build step required.

## Tech Stack

- **HTML5** — semantic page content and layout structure.
- **CSS3** — styling, card positioning, typography, and responsive behavior.
- **Google Fonts** — Poppins font family.

## Run Locally

1. Clone or download the repository.
2. Open the project folder in your editor.
3. Open `index.html` in a modern browser, or launch it with VS Code Live Server.

No build tools or npm dependencies are required. Keep the `assets/images/` directory alongside the HTML files so the logo and card images can load correctly. An internet connection is needed to fetch the Google Font unless you change the font setup.

## Project Structure

```text
Web-Design-Agency-Website/
├── index.html              # Main page
├── style.css               # Styles for the main page
├── solution.html           # Alternate/reference HTML implementation
├── solution.css            # Alternate/reference stylesheet
└── assets/
    └── images/
        ├── logo.png
        ├── beautiful.jpg
        └── construction.jpg
```

## Responsive Layout

The main stylesheet uses a flexible page layout with service cards arranged side by side on wider screens. At viewport widths of 680px or less, the heading and cards are adjusted for a narrow screen and the cards stack vertically.

## Current Scope and Possible Improvements

This is a **static front-end demonstration**, not a complete agency website. The service cards are presentational; the repository does not implement forms, navigation flows, a backend, or a content-management system.

Potential improvements:
- Correct the non-standard `</br>` element in `index.html` to a proper `<br />` line break.
- Use semantic `<main>` and `<section>` elements where appropriate.
- Improve image sizing and spacing across intermediate screen widths.
- Add meaningful alt text for the logo.
- Decide whether to keep both the main and reference versions or clearly label the reference files.
- Verify that all image assets may be redistributed under the intended licensing terms.

## License

**MIT License** — see [`LICENSE`](LICENSE) for the full terms.

The repository includes image assets whose original source and redistribution terms are not documented in the project files. Confirm those terms before redistributing the images; do not assume the MIT license overrides third-party rights. The Poppins font is loaded from Google Fonts and is subject to its own license.

## Author

**Shubham Singh** · [GitHub Profile](https://github.com/shubhamsingh-07)
