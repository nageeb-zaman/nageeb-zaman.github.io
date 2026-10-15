# nageeb-zaman.github.io

Source for my personal website: **https://nageeb-zaman.github.io**

I'm a computational astrophysicist finishing my Ph.D. in physics at Louisiana
State University. The site covers my research (supernova simulations with
MESA, STELLA and SuperLite; GPU supernova code at Los Alamos), technical
skills, background, publications and talks.

## Structure

| Path | Contents |
|---|---|
| `index.html` | Home page: about, projects, skills, background, publications, contact |
| `project.html` | Detailed research case studies |
| `components/` | Shared header and footer, loaded by `js/load-components.js` |
| `css/components/` | Styles, one file per section |
| `js/scripts.js` | Navigation, theme toggle, scroll and animation effects |
| `assets/` | Images, project figures and resume |
| `resources/` | Downloadable documents (e.g. M.S. thesis) |

To preview locally: `python3 -m http.server` in this folder, then open
http://localhost:8000.

## Credits

Built on the open-source portfolio template by
[Trần Hữu Đạt](https://github.com/TranHuuDat2004) (MIT License, see
`LICENSE`). Content, figures and research descriptions are my own.
