# Bungo Website — Replacement Build

A responsive 4-page static website for the Bungo smash-burger brand, built with plain HTML, CSS and JavaScript

## Pages
- `index.html` — homepage
- `menu.html` — interactive menu tabs
- `story.html` — brand story and values
- `visit.html` — location/contact/reservation UI

## Run locally
### VS Code Live Server
Open this folder, right-click `index.html`, then choose **Open with Live Server**.

### Python
From this folder run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Editing
- Main styling: `assets/css/styles.css`
- Interactions: `assets/js/main.js`
- Brand logo: `assets/images/bungo-logo-dark.png` (transparent red + white version for dark backgrounds)
- Food and packaging imagery: `assets/images/`
- Category icons: `assets/icons/`

## Client details to confirm later
The current phone number, email, exact Budapest address and opening hours are placeholders. Update them in `visit.html` and the footers once the client confirms the final details.

The reservation form is front-end only. Connect it to a mail service, Formspree, Netlify Forms, or your own backend when deploying.
