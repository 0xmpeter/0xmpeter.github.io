# Personal website

Minimal, no-build, single-page website.

## Local preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy (recommended)

Create a GitHub repo named `0xmpeter.github.io` and push these files to its default branch.

Then in GitHub:

1. Repo → **Settings** → **Pages**
2. **Build and deployment** → **Source**: “Deploy from a branch”
3. **Branch**: select your default branch and `/ (root)`

## Deploy (alternative)

Use any repo and enable GitHub Pages. The site will be served at `https://0xmpeter.github.io/<repo>/`.
