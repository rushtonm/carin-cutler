# Carin Cutler, Fractional General Counsel

A single-page marketing website for Carin Cutler's fractional General Counsel practice,
serving private equity and venture-backed companies.

## Stack

Plain static HTML + CSS. No build step, no dependencies. Fonts load from Google Fonts.

- `index.html`: all page content
- `styles.css`: all styling (clean/corporate, navy & slate palette)

## Editing common things

| To change... | Edit... |
|---|---|
| Any text/copy | `index.html` |
| Contact email | the `mailto:` link in the `#contact` section of `index.html` |
| Focus areas | the `.cards` section of `index.html` |
| Colors | the `:root` variables at the top of `styles.css` |
| Headshot | replace the `.portrait-frame` block in `index.html` with an `<img>` |

### Adding a headshot

Drop an image (e.g. `carin.jpg`) in the repo, then in `index.html` replace:

```html
<div class="portrait-frame"><span class="portrait-mono">CC</span></div>
```

with:

```html
<img class="portrait-frame" src="carin.jpg" alt="Carin Cutler" />
```

## Hosting

Published via **GitHub Pages** from the `main` branch. Any push to `main` updates the live site.

To add a custom domain later, add a `CNAME` file containing the domain and configure DNS,
or set it under the repo's **Settings → Pages**.

---

_This site is for general informational purposes and does not constitute legal advice._
