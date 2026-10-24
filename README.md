# One Fox

Marketing site for **One Fox** — an AI answer engine paired with a visual workflow builder. Ask questions against your own data and turn the answers into automations that run themselves.

Static, single-page site. No build step, no dependencies — just HTML, CSS and a little vanilla JS.

## Live

https://s86986762-spec.github.io/onefox/

## Structure

```
index.html            the whole site (markup + styles + minimal JS)
favicon.svg           browser tab icon
apple-touch-icon.png  iOS home-screen icon
og-image.jpg          1200x630 social share card
robots.txt            crawler directives
sitemap.xml           single-URL sitemap
```

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy

Hosted with GitHub Pages from the `main` branch, root folder. Push to `main` and the site updates.

## Editing

Everything lives in `index.html` — design tokens are CSS custom properties in `:root` at the top of the `<style>` block, so colours and fonts can be changed in one place.
