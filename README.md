# haroon.world

My personal website — a simple, fast, no-framework homepage with an about page and a blog (coming soon).

🔗 Live: [haroon.world](https://haroon.world/)

## About

A minimal personal site built with plain HTML, CSS, and JS — no build tools, no frameworks, no dependencies to install. Just open `index.html` in a browser and it works.

- **Homepage** — quick intro with links to my socials and projects
- **About** — the story behind how I got into computer science
- **Blog** — coming soon

## Tech stack

- **HTML/CSS/JS** — hand-written, no framework
- **[Tachyons](https://tachyons.io/)** — utility-first CSS for layout and spacing
- **[highlight.js](https://highlightjs.org/)** — syntax highlighting for code blocks (GitHub Gist theme)
- **[Space Mono](https://fonts.google.com/specimen/Space+Mono)** — Google Font used site-wide
- **Google Analytics** — basic page view tracking

## Project structure

```
.
├── index.html          # Homepage
├── about.html          # About page
├── post.html           # Blog (placeholder)
├── style.css           # Custom styles
├── tachyons.min.css    # Tachyons utility framework
├── github-gist.css     # Code block syntax highlighting theme
├── highlight.min.js    # highlight.js library
└── analytics.js        # Google Analytics
```

All files sit flat in the repo root so it works out of the box with static hosts like GitHub Pages — no build step required.

## Running locally

Just open `index.html` in your browser. No server, no install, no build step needed.

## Deployment

This is a fully static site — deploy it anywhere that serves static files:

- **GitHub Pages** — push to this repo, enable Pages in Settings, done
- **Netlify / Vercel** — drag and drop the folder, or connect the repo

## To do

- [ ] Set up your own Google Analytics property and swap in the tracking ID in each HTML file (currently a placeholder, `UA-XXXXXXXXX-X`) — note Universal Analytics (UA-) properties are deprecated; consider setting up GA4 instead
- [ ] Write and publish first blog post
- [ ] Add a proper blog post template/archive
- [ ] (optional) Add a projects section

## License

Personal project — feel free to peek at the code, but please don't copy the content as your own.
