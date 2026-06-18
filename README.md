Quick local preview

1. Place your image files inside the `assets/` folder (create it next to `index.html`).

The assets folder already contains the uploaded team images. The page now uses these filenames directly:

- `sriram.png` — Sriram
- `praba.jpeg` — Prabavathi
- `abinaya.png` — Abinaya
- `swetha.png` — Swetha (also used as fallback)
- `Dhivyadharshini.png` — Dhivyadharshini
- `kanishka.png` — Kanishka
- `kanchanamala.png` — Kanchanamala
- `Gopinath.jpeg` — Gopinath

Collage/details preview images used:

- `sriram.png` (hero / collage)
- `praba.jpeg` (collage)
- `abinaya.png` (collage + details)

2. To preview locally run a simple HTTP server (Python 3):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

Notes & suggestions

- Filenames with spaces and commas may cause issues when uploading. Consider renaming images to simple names (e.g., `hero.png`, `collage1.png`, `w0.png`).
- If you want, I can rename the image references in `index.html` to `assets/hero.png`, `assets/c1.png`, etc., and create a small `assets/` manifest. Tell me if you'd like me to do that and which images you want used where.