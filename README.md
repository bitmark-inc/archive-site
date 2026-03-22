# Bitmark Archive Site

This repository contains the official archival homepage for `bitmark.com`.

The Bitmark blockchain has been shut down. This site preserves historical context, reference links, and archival materials.

## Live Site

- `https://bitmark.com`

## Repository Contents

- `index.html` - static archive page with interactive footer symbol
- `assets/logo.svg` - Bitmark logo asset
- `assets/files/bitmark.pdf` - original paper
- `assets/model/scene.gltf` - 3D symbol model
- `favicon.ico` - site favicon

## Local Preview

```bash
python3 -m http.server
```

Then open `http://localhost:8000/`.

## Deployment

This site is designed for static hosting.

For GitHub Pages:

1. Go to repository `Settings` -> `Pages`
2. Set source to `Deploy from a branch`
3. Select branch `main` and folder `/ (root)`
4. Set custom domain to `bitmark.com` (optional)

## Contact

- `info@bitmark.com`
