# Eva Zerega – portfolio website

Static site (plain HTML/CSS/JS, no build step).

```
docs/            the website – this folder is what GitHub Pages serves
  index.html
  images/        images used by the site
  .nojekyll
source-images/   original portfolio images not currently on the site (not deployed)
docker-compose.yml   optional local preview
```

## Preview locally

```
docker compose up -d      # http://localhost:8080
docker compose down
```

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Repo **Settings → Pages**.
3. Source: **Deploy from a branch** → Branch: `main`, folder: `/docs` → Save.
4. The site goes live at `https://<username>.github.io/<repo>/`.
