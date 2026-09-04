# Publishing the portfolio on GitHub Pages

This folder is the whole site. Three pages + one `assets` folder. Nothing else is needed.

```
site/
  index.html                 ← home
  feature-driven-flow.html   ← case study 1
  order-page-admin.html      ← case study 2
  assets/                    ← images and videos (27 files, ~10 MB)
```

## Upload (about 5 minutes)

1. Open your repository on github.com.
2. Click **Add file → Upload files** (top right of the file list).
3. In Finder, open this `site` folder, select **everything inside it** (`index.html`, the two other `.html` files and the `assets` folder) and drag them onto the GitHub upload area. Dragging the `assets` folder keeps its files inside it — that's what you want.
4. Wait for the green ticks next to every file (the two videos take a moment).
5. At the bottom, in "Commit changes", leave the message as it is and click **Commit changes**.

## Turn on the website (1 minute)

6. In the repository, click **Settings** (top tab) → **Pages** (left menu).
7. Under "Build and deployment": Source = **Deploy from a branch**; Branch = **main**, folder **/ (root)** → **Save**.
8. Wait 1–2 minutes and reload that page. A box at the top says "Your site is live at …" — that's your address:
   `https://<your-username>.github.io/<repository-name>/`

## Updating later

Repeat steps 2–5 with only the changed file(s). Same file name = it replaces the old one. Every version is kept in the repo's history.

## Before sending the link to anyone

- The **CV**, **LinkedIn** and **Get in touch** buttons still point to `#`. Open each `.html`, search for `href="#"`, and replace with your links (CV as a PDF in `assets/`, or a Google Drive link; LinkedIn profile URL; `mailto:` for Get in touch).
- Open all three pages once on your phone.
