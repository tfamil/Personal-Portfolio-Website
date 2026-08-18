# Personal Portfolio Website

A responsive single-page software engineering portfolio built with HTML, CSS, and vanilla JavaScript. The site showcases projects, experience, technical skills, education, and contact links through a custom interactive design.

## Live Site

**https://tfamil.com/?utm_source=github.com&utm_medium=readme&utm_campaign=git-readme&utm_id=tfamil&utm_term=git-readme&utm_content=readme**

## Highlights

- Fully custom single-page layout with no frontend framework.
- Responsive CSS Grid/Flexbox layouts.
- Interactive project archive with modal details.
- Scroll progress indicator.
- IntersectionObserver-powered reveal animations.
- Config-driven project, experience, social, and contact content.
- Keyboard-close support for modals.
- Reduced-motion support through `prefers-reduced-motion`.
- Responsive navigation and section scrolling.
- Downloadable CV integration.
- GitHub Pages deployment.
- SEO/social metadata and favicon/app-icon support in the current deployed repository.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages
- GitHub Actions

## Design Approach

The portfolio uses a custom editorial/archive-inspired visual system rather than a component library. Most content can be updated through a JavaScript configuration object while the surrounding layout and interactions remain reusable.

Key UI patterns include:

- hero typography and animation
- project "folder" archive
- modal project previews
- interactive experience presentation
- responsive skill/technology displays
- scroll-based navigation state
- accessibility-oriented reduced-motion fallback

## Run Locally

This is a static site, so no build process is required.

You can open `index.html` directly, or serve the folder locally.

With Python:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

The site can be deployed directly to GitHub Pages with a static Pages workflow.

Recommended repository structure:

```text
.
├── .github/
│   └── workflows/
│       └── static.yml
├── assets/
├── index.html
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── site.webmanifest
├── robots.txt
├── sitemap.xml
└── CNAME
```

## What I Practised

- Semantic HTML
- Responsive interface design
- Advanced CSS layout/animation
- DOM manipulation
- Accessible interaction patterns
- Configuration-driven frontend content
- Static-site deployment
- GitHub Actions / GitHub Pages
- SEO and social-sharing metadata

## Before Publishing

The attached portfolio archive is an older single-file version and contains older experience/project copy. The current GitHub Pages repository should be treated as the source of truth.

For a polished public repository:

- Keep the current `index.html`, favicon files, manifest, sitemap, robots file, and assets.
- Keep project descriptions consistent with the actual technologies in each repository.
- Use the real portfolio URL (`https://tfamil.com/?utm_source=github.com&utm_medium=readme&utm_campaign=git-readme&utm_id=tfamil&utm_term=git-readme&utm_content=readme`) everywhere instead of older placeholder domains.
- Make sure CV links point to an existing file/URL.
- Avoid embedding large base64 images when normal optimized image files can be used.
