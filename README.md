# Sowmya Yadav K — Portfolio

A personal portfolio for a CSE student at Rajalakshmi Institute of Technology, Chennai. Adapted from [sravanyadav-19/portfolio](https://github.com/sravanyadav-19/portfolio).

## Publish on GitHub Pages

Upload the project files to the root of the `main` branch (so `index.html` is at the top level). In the repository's **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save. For this repository, the expected address is `https://sowmyayadav-08.github.io/portfolio/`.

## Edit content

Update `content/portfolio.ts`, then run:

```sh
npm ci
npm run build
```

Commit or upload the changed source and generated files (`assets/js/portfolio.js` and `index.html`) together. Rebuilding is needed for content changes to appear. See `content/README.md` for examples. Projects and achievements are hidden until content is ready.

The contact form opens the visitor's email app; it does not send or store messages itself.
