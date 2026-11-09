# Md Shifat Hamidi — Portfolio

Personal portfolio site built with plain HTML, CSS and JavaScript. No build step.

Live: https://sifathamidi.github.io

## Deploy on GitHub Pages

1. Create a public repo named **`SifatHamidi.github.io`**.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/SifatHamidi/SifatHamidi.github.io.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source: Deploy from a branch → main / (root)** and save.
4. The site will be live at `https://sifathamidi.github.io` in a minute or two.

## Structure

- `index.html` — homepage
- `case-studies/` — project case studies (offline POS, barcode scanning)
- `og-image.png` — social link preview image (1200×630)

## Customize

- **Accent color:** change `--accent` (and `--accent-soft`, `--accent-glow`) at the top of `style.css`.
- **Projects / experience:** edit the matching sections in `index.html`.
- **Résumé:** add `resume.pdf` to the repo and link it from the hero buttons.
