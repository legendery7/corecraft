# CoreCraft

Public website for a Minecraft plugins product line.

## Description

Marketing and catalog site for CoreCraft plugins: landing page, about, terms, and plugin listings.

## Architecture

Static multi-page site (HTML/CSS/JS). No server-side runtime required for the public pages.

```
corecraft/
├── index.html      # Landing
├── about.html
├── terms.html
├── 404.html
├── style.css
├── script.js
├── plugins.js
├── Images/
└── web.config      # IIS hosting hints
```

## Tech stack

- HTML5
- CSS
- JavaScript
- Optional IIS (`web.config`)

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server:

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

Then open `http://localhost:8080`.

## Roadmap

- [ ] Keep content and assets in sync with the product line
- [ ] Improve SEO metadata where needed
- [ ] Consider separating marketing content from binary assets (e.g. large archives)

## License

Proprietary / all rights reserved unless otherwise stated by the author.
