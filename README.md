# psycharalabs.com

Static site for [Psychara Labs](https://psycharalabs.com) — mental health × technology.

Plain HTML + one stylesheet, no build step. Served by GitHub Pages.

## Structure

- `index.html`, `portfolio.html`, `services.html`, `connect.html` — the four pages (header/footer duplicated per page by design; editing nav means editing four files)
- `style.css` — the entire design system: paper `#F2EFE9`, ink `#161310`, vermillion `#D93A0F`; Young Serif headlines, Archivo body, IBM Plex Mono labels (Google Fonts)
- `CNAME` — custom domain for GitHub Pages
- `404.html`, `favicon.svg`

## Editing

Edit the HTML, commit, push — Pages redeploys automatically in about a minute. Design rules worth keeping: heavy ink rules instead of cards, no shadows, no pill shapes, no animations, sentence-case serif headlines.
