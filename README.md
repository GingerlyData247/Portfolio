# Wesley Todd Portfolio Starter

A dependency-free portfolio website built with plain HTML, CSS, and JavaScript.

## Folder structure

```text
portfolio/
├── index.html
├── 404.html
├── .nojekyll
├── README.md
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   └── images/
└── projects/
    ├── tiny-defenders/
    │   └── index.html
    ├── hugging-face-model-analyzer/
    │   └── index.html
    ├── liquid-gold/
    │   └── index.html
    ├── 2d-game-engine/
    │   └── index.html
    ├── furious-rogue/
    │   └── index.html
    ├── root-of-all-evil/
    │   └── index.html
    └── _template/
        └── index.html
```

## Before publishing

1. Replace the placeholder introduction, About section, and Contact links in `index.html`.
2. Replace each project page's placeholder paragraphs and image boxes.
3. Add your screenshots to `assets/images/` or to each project's own folder.
4. When adding a real image, use an `<img>` element with descriptive `alt` text.
5. Keep the site dependency-free unless you intentionally want to add a library later.

## GitHub Pages

This site is intentionally static, so it can be hosted directly with GitHub Pages.

For a personal site, GitHub's recommended user-site repository name is:

```text
YOUR-GITHUB-USERNAME.github.io
```

Put `index.html` in the repository root. In GitHub, open **Settings → Pages** and choose your publishing source. The site can then be served from the GitHub Pages URL.

The included `.nojekyll` file tells GitHub Pages not to run the source through Jekyll, which is useful for a plain static HTML/CSS/JS project.

## Other free hosting options

Cloudflare Pages, Netlify, and Vercel also provide free plans that can deploy a static site from a Git repository. GitHub Pages is the simplest match for this particular project because there is no backend or build system.

## Adding project pages

Copy `projects/_template/` to create another project folder, rename the folder, change the page content, and add a new project card to the main `index.html`.
