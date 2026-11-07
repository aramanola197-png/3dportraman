# Raman — portfolio

Static site for GitHub Pages. No build step.

## Publish
1. Create a public repo named `<your-username>.github.io` and upload everything in this folder (keep the `assets` folder).
2. Repo Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. In `index.html`, replace every `__SITE_URL__` with your site address including the trailing slash,
   e.g. `https://yourname.github.io/` (this makes the og.png link preview show when the link is shared).

## Work thumbnails
Each card first looks for its own image in `assets/`, then falls back to the image on X.
To host them yourself, save these as JPGs into `assets/`:
- work-stbtc.jpg   https://pbs.twimg.com/media/HWW5bfAWoAAu_3-?format=jpg&name=large
- work-bitflow.jpg https://pbs.twimg.com/media/HWBugNzWcAANH28?format=jpg&name=large
- work-bonds.jpg   https://pbs.twimg.com/media/HWIqZ4oWMAAGS6L?format=jpg&name=large
- work-zest.jpg    https://pbs.twimg.com/media/HWQJwitXsAAswVK?format=jpg&name=large
- work-zadao.jpg   https://pbs.twimg.com/amplify_video_thumb/2113572134823849984/img/r9OYKO7qGgMxTShT?format=jpg&name=large
