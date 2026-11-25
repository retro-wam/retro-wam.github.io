# RetroWAM project page

Source for https://retro-wam.github.io, the project page for
**RetroWAM: World Action Models Self-Calibrate Their Robots by Reading, Not Imagining**.

Plain static HTML, no build step. GitHub Pages serves `index.html` from the `main` branch.

- `index.html`: page content (author, links, text, tables, BibTeX)
- `static/css/style.css`: styles
- `static/images/`: figures from the paper, the favicon and the link thumbnail (`thumbnail.png`, 2400x1256)
- `static/videos/`: the teaser video and its poster
- `site/`: a short seamless loop and its poster (light and dark, 912x512) for linking to this page from other sites

To preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
