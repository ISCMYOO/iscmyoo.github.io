# iscmyoo.github.io

Repository for the personal homepage.

Refactor notes:
- `index.html` remains at the repo root as the landing page.
- All detail pages were moved under the `html/` folder: open `html/*.html` pages or use the root links in `index.html`.
- Root copies of the moved files remain as small redirect pages to avoid breaking old links.

Quick local preview:
- From the repo root run (Python 3):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser. The `index.html` will load and links point to pages in the `html/` subfolder.
