# ExpC0.github.io

Personal portfolio of **Md Raduan Islam Rian** — R&D Engineer (Networking &
Embedded Systems) at Shanghai BDCOM.

🔗 **Live site:** https://expc0.github.io

## Stack

Plain, dependency-free **HTML + CSS + a little JavaScript**, hosted on
**GitHub Pages**. No build step, no framework.

| File | Purpose |
|---|---|
| `index.html` | Page content and structure |
| `styles.css` | Styling (dark-first, light-mode aware, responsive) |
| `script.js` | Mobile nav, footer year, scroll-reveal |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (skip Jekyll) |

## Editing

Just edit the files and push to `main` — GitHub Pages redeploys automatically.

### Things you may want to update

- **LinkedIn URL** — `index.html` currently links to `https://www.linkedin.com/`
  as a placeholder (search for `TODO`). Replace it with your real profile URL.
- **Experience start date** — the BDCOM role shows `2025 — Present`; adjust if needed.
- Add new projects by copying a `<article class="card">…</article>` block.

## Local preview

```sh
# any static server works, e.g.:
python3 -m http.server 8000
# then open http://localhost:8000
```

## License

Content © Md Raduan Islam Rian. Code (HTML/CSS/JS) is free to reuse.
