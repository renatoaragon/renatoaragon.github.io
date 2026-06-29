# Portfolio — Renato Aragón

Personal portfolio site. Static HTML/CSS, no build step. Deployed via GitHub Pages.

## Local preview

Just open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to GitHub Pages

**Option A — user site (served at `https://<username>.github.io`):**

1. Create a public repo named exactly `<username>.github.io`.
2. Push this folder to its `main` branch.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / root**.

**Option B — project site (served at `https://<username>.github.io/portfolio`):**

1. Create any public repo (e.g. `portfolio`) and push.
2. Same Pages settings as above.

The site goes live a minute or two after the first push.

## Structure

```
index.html   — single-page site
style.css     — styles
```
