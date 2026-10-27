# Platinum Backlog

My unfinished PS4/PS5 games, ranked by how hard they are and roughly how long they'll take, using the difficulty and time ratings from each game's PSNProfiles trophy guide.

It's a single static page (`index.html`) with no build step. The data is embedded in the page itself.

## Hosting it on GitHub Pages

1. Create a new repository on GitHub (for example `platinum-backlog`).
2. Upload `index.html` and this `README.md` to the repository (Add file → Upload files), then commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, and click **Save**.
5. After a minute or two, the site will be live at `https://<your-username>.github.io/platinum-backlog/`.

## Notes

- Difficulty and time come from PSNProfiles trophy guides (community ratings for the full platinum). "Est. time left" scales the guide time by the share of trophies not yet earned, so it's a rough estimate.
- Already-platinumed games and PS3/Vita-only games are left out.
- Data collected 27 October 2026. It won't update by itself; the game list lives in the `<script id="data">` block near the bottom of `index.html`.
