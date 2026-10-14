# Lift Library

Static site: `index.html` reads `videos.csv`. Host it with GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/`).

## Add your videos
Replace `videos.csv` with your file. Header: `category,title,url,date,sets,reps,weight,notes`
(`sets`, `reps`, `weight`, `notes` are optional). Dates like `2026-10-14` sort best.

## Add videos from the site
Click **Add a video**, then under **Publishing** paste a fine-grained GitHub token limited to this repo with Contents: Read and write. Saving the form then commits a new row to `videos.csv`. The token stays in your browser only. Without a token, entries are kept on that device and can be copied as CSV rows.

Only you should use a token. Anyone can view the site, but only token holders can change the repo.
