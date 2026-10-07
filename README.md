# Lalangue

A local-first, two-page Vite site using HTML and shared CSS. No browser JavaScript; Big Moore is delivered through an Adobe Fonts Web Project.

## Run

```sh
npm install
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

Vite emits the homepage and `/about/` into `dist/`. Preview serves the production build locally.

Pushes to `main` build and deploy `dist/` to GitHub Pages through `.github/workflows/deploy.yml`. In the repository's **Settings → Pages**, set **Source** to **GitHub Actions** once before the first deployment.

## Editing

- Homepage: `index.html`; About: `about/index.html`.
- Shared styles and palette: `src/style.css`.
- The header uses the supplied logo image inside an accessible home link.
- The site uses Big Moore throughout through Adobe Fonts Web Project `rpw0jqn`, with a Garamond stack as the fallback.

## Artwork

The supplied original artwork is used as a decorative background on both pages, encoded as an optimized PNG without cropping or changing its composition. CSS adds a light wash to keep text readable.
