# Lalangue

A local-first, two-page Vite site using HTML and shared CSS. No browser JavaScript, external fonts, or third-party embeds.

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

Vite emits the homepage and `/about/` into `dist/`. Preview serves the production build locally. Nothing is deployed automatically.

## Editing

- Homepage: `index.html`; About: `about/index.html`.
- Shared styles and palette: `src/style.css`.
- The lowercase text wordmark is temporary. Replace both header wordmarks with the final logo while retaining an accessible home link.
- Recommended final font: [Neue Haas Grotesk](https://fonts.adobe.com/fonts/neue-haas-grotesk). The initial stack uses locally available Helvetica/Arial. Add an Adobe Web Project embed or appropriately licensed self-hosted web fonts when ready, then update `--font`.

## Artwork

The supplied original artwork is used as a decorative background on both pages, encoded as an optimized PNG without cropping or changing its composition. CSS adds a light wash to keep text readable.
