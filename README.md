# Ocean Light Composition

A small Three.js shader study rendered with `ShaderMaterial`.

It features:

- a contained ocean-like composition on a dark blue background
- procedural light patches, noise, and soft animated motion
- custom inline GLSL vertex and fragment shaders
- a single-file setup that runs in the browser

## Run locally

Because the page uses ES module imports, serve the folder with a local web server instead of opening it directly from disk.

```bash
cd /Users/giangtran/Documents/Codex/2026-04-25-create-a-three-js-scene-with
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Files

- `index.html` – the full scene, styling, and shaders

## Publish to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## GitHub Pages

After pushing:

1. Open your repository on GitHub.
2. Go to `Settings`.
3. Open `Pages`.
4. Set the source to deploy from the `main` branch and `/ (root)`.
5. Save and wait for the site URL.
