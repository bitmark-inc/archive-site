# Archive Site

Static archive site for bitmark.com.

## Files

- `index.html` - complete page with inline CSS/JS and interactive 3D footer symbol
- `assets/logo.svg` - Bitmark logo used at top left
- `assets/files/bitmark.pdf` - original paper link target
- `assets/model/scene.gltf` - 3D footer model

## Local preview

You can open `index.html` directly, or run a simple static server:

```bash
python3 -m http.server
```

Then open `http://localhost:8000/`.

## Deploy

Upload this repository contents to any static host:

- DigitalOcean App Platform (static site)
- DigitalOcean Droplet + nginx
- S3 + CloudFront
- Netlify / Vercel static hosting

For production, serve `index.html` as the default document.
