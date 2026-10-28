Author of website: Junwei (Ivy) Sun  
Link to the website: https://ivysun14.github.io/Personal-Website/

Personal academic website built with [Quarto](https://quarto.org) and deployed with GitHub Pages.

Pages:
- **Home** – short introduction and links (LinkedIn, GitHub)
- **About** – background, education, and experience
- **Publications** – preprints and peer-reviewed articles

Repository layout:
- `website/` – Quarto source (`_quarto.yml`, `index.qmd`, `about.qmd`, `styles.css`, photo)
- `docs/` – rendered site served by GitHub Pages (do not edit by hand)

To update the site:
1. Edit the `.qmd` files in `website/`
2. Run `quarto render` inside `website/` (output goes to `docs/`; `docs/.nojekyll` tells GitHub Pages to skip Jekyll)
3. Commit and push `website/` and `docs/`

GitHub Pages is configured to publish from the `docs/` directory of the `main` branch.
