# Bladimir Padilla — Academic Website

Built with [Quarto](https://quarto.org). Clean & minimal, slate blue theme.

## Quick Start

### Prerequisites
- [Quarto CLI](https://quarto.org/docs/get-started/) installed
- RStudio (≥ 2022.07) or VS Code with the Quarto extension

### Run locally
```bash
quarto preview
```
This opens a live preview at `http://localhost:4200` that reloads on save.

### Build for deployment
```bash
quarto render
```
Output goes into the `_site/` folder.

---

## File Structure

```
.
├── _quarto.yml          # Site config: navbar, theme, footer
├── styles.css           # Custom slate blue theme
├── index.qmd            # Home / About page
├── research.qmd         # Research projects & interests
├── teaching.qmd         # Teaching history & philosophy
├── publications.qmd     # Auto-rendered from references.bib
├── references.bib       # ← Add your publications here (BibTeX)
├── cv.qmd               # CV overview + PDF download link
├── contact.qmd          # Contact info & links
└── photo.jpg            # ← Replace with your headshot
```

---

## Customization Checklist

- [ ] Replace `photo.jpg` with your actual headshot (keep the filename, or update `index.qmd`)
- [ ] Edit `index.qmd` — fill in your bio, university, and research interests
- [ ] Edit `research.qmd` — add your working papers and projects
- [ ] Edit `teaching.qmd` — add courses you've taught or TA'd
- [ ] Edit `references.bib` — add real publications (BibTeX format; export from Google Scholar or Zotero)
- [ ] Add `cv.pdf` to the root folder so the CV download link works
- [ ] Update `contact.qmd` with real email, office, and social links
- [ ] Update `_quarto.yml` — set your GitHub/Twitter URLs in the navbar
- [ ] (Optional) Add a `apa.csl` file for citation formatting — download from https://www.zotero.org/styles/apa

## Deploying

**GitHub Pages** (recommended):
1. Push the project to a GitHub repo
2. Run `quarto publish gh-pages`

**Netlify / Quarto Pub**:
```bash
quarto publish netlify
# or
quarto publish quarto-pub
```

---

*Theme color: Slate Blue `#4a6fa5` — edit `styles.css` to change.*
