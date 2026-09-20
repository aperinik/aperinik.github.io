# Portfolio

Single-page portfolio built with semantic HTML, Tailwind utility classes, and a small custom stylesheet.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static web server:

```bash
python3 -m http.server
```

Tailwind utilities are loaded from the CDN in `index.html` for this prototype. The semantic text groups in `style.css` use `@apply` and can be compiled when moving to a Tailwind CLI/PostCSS build; utility classes are also kept on the markup so the CDN version works without a build step.
