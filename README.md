# webviewer-demo

Bundled **Apryse WebViewer** demo with prebuilt `core/` and `ui/` assets for offline PDF viewing and annotation trials.

## What it does

- Static HTML shell that loads the WebViewer UI bundle
- Sample files in `files/` for rendering, annotation, and compare workflows
- Useful as a reference when integrating Apryse into a larger React or vanilla JS app

## Run locally

Serve the folder with any static server, for example:

```bash
npx serve .
```

Then open `index.html` in the browser (or the URL the static server prints).

## Notes

- The `core/` and `ui/` directories contain Apryse proprietary runtime assets.
- Valid **Apryse license** required for production deployments.
- For npm-based integration, see the sibling [`webviewer`](https://github.com/g8z/webviewer) webpack example.

## License

Demo/sample use. Apryse SDK subject to [Apryse terms](https://www.apryse.com/).
