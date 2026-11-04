# Junhan Zhu's homepage

Personal academic website: https://alrightlone.github.io/

This is a static HTML/CSS site. No dependency installation or build step is needed.

## Preview locally

From this repository's root, run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open http://localhost:8000. You can also open `index.html` directly in a browser.

## Edit

- `index.html`: biography, profile links, news, publications, projects, education, awards, and services.
- `css/academic.css`: layout, typography, mobile styles, and print styles.
- `images/` and `work/`: existing images and PDFs.
- `images/home/`: smaller homepage copies of the portrait and research figures; original images are retained.

News appears between the biography and publications in a scrollable window. All entries are available using the mouse wheel, touch gestures, or keyboard when the window is focused. No JavaScript is required; printing expands the window to include all entries.

Publication backgrounds indicate authorship: yellow for first author (including co-first listed first), light blue for co-first listed second, and white for other collaborations. Each highlighted paper also includes a text label. The site does not depend on external font/icon libraries.

The design and styles are adapted from [Yanchen Huang's website](https://github.com/02hyc/02hyc.github.io). The original MIT notice is preserved in `LICENSES/academic-pages-MIT.txt`.

## Publish

Commit and push the changes to the branch configured for this repository's GitHub Pages deployment. Keep the existing images and PDFs in the repository. The separately hosted blog and research project pages retain their existing URLs.
