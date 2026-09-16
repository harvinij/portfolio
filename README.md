# Isaiah Harvin — Portfolio Site

Personal portfolio homepage: hero section + "Now, the work" project grid
(Verts, Autoplay trailers, Remove from Continue Watching, Experimentation
program, Mentorship & workshops, APTIC).

## Structure

- `index.html` — the page markup
- `styles.css` — all styling
- `assets/` — images (headshot, autoplay preview gif)

## Running locally

No build step needed — it's plain HTML/CSS. Open `index.html` directly in
a browser, or serve it locally:

```
python3 -m http.server 8000
```

then visit http://localhost:8000

## Deploying with GitHub Pages

1. Push this folder to a GitHub repo.
2. In the repo, go to Settings → Pages.
3. Under "Build and deployment", choose "Deploy from a branch", pick
   `main` and `/ (root)`, then Save.
4. GitHub gives you a live URL in a minute or two
   (`https://<username>.github.io/<repo-name>/`).
