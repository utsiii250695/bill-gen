# Petrol Receipt Generator

A live receipt generator styled after the MESCO PETROLEUM (Hindustan Petroleum) thermal printer receipts.

## Run locally
Open `index.html` in any modern browser. No build step.

## Deploy on GitHub Pages
1. Create a new public repo (e.g. `petrol-receipt`).
2. Upload **all files in this folder** preserving structure:
   ```
   index.html
   colors_and_type.css
   assets/hp-logo.jpg
   fonts/*.ttf
   ```
3. In the repo: **Settings → Pages → Source:** "Deploy from a branch" → **Branch:** `main` / **Folder:** `/ (root)` → Save.
4. Wait ~1 minute, then visit `https://<your-username>.github.io/<repo-name>/`.

## Use
Fill in date, time, rate (₹/L), and litres on the left — the receipt updates live on the right.
- **PRINT / PDF** opens the browser print dialog (form is hidden, only the receipt prints).
- **PNG** downloads a 2× resolution PNG of the receipt.
