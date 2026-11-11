# Snaply

A small Instagram-inspired social feed demo that runs as a static website.

## Run locally

Make sure Python is installed. From the repository folder, run:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser. Stop the server with `Ctrl+C`.

You can also open `index.html` directly, but using the local server is recommended.

## GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. GitHub Pages will publish the site.

> Login and registration are browser-only demo features. They do not provide secure production authentication or sync accounts between devices.
