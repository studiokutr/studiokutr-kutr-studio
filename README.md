# KUTR Studio website

Static site for kutr.studio, hosted on GitHub Pages (custom domain set in `CNAME`).

- `index.html` is the whole site: layout, styles and scripts.
- `content/*.json` holds the editable content (projects, team, services, contact texts). The page reads these files when it loads.
- `images/` holds every image.
- `admin/` is the content dashboard (Sveltia CMS). Open `https://kutr.studio/admin/` and sign in with a GitHub access token. Saving there commits to this repo, and GitHub Pages republishes within a minute or two.
