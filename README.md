# CoreCraft

Public product website for a Minecraft plugin platform.

## Overview

Static multi-page website presenting the CoreCraft product line: landing page, about, terms, and plugin catalog.

## Architecture

Static site (HTML / CSS / JavaScript). No application server is required for the public pages. Optional IIS hosting via `web.config`.

```
Visitor → static files (HTML/CSS/JS/assets)
```

## Features

- Landing page
- About and terms pages
- Plugin listing scripts
- Basic SEO files (`robots.txt`, `sitemap.xml`)
- Custom 404 page

## Tech stack

- HTML5
- CSS
- JavaScript
- Optional IIS (`web.config`)

## Project structure

```
corecraft/
├── index.html
├── about.html
├── terms.html
├── 404.html
├── style.css
├── script.js
├── plugins.js
├── Images/
└── web.config
```

## Getting started

```bash
python -m http.server 8080
# or: npx serve .
```

Open `http://localhost:8080`.

## Roadmap

- [ ] Enable GitHub Pages for a public demo URL
- [ ] Keep large binary archives out of the main branch (or use Releases)
- [ ] Tighten SEO and accessibility metadata

## License

Proprietary / all rights reserved unless otherwise stated by the author.
