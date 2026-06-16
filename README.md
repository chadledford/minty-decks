# Minty for Business — Sales Decks (GitHub Pages)

Self-contained HTML decks. No build step, no dependencies.

## Publish in ~2 minutes
1. Create a new GitHub repo (e.g. `minty-decks`).
2. Upload everything in this folder (`index.html`, the two deck `.html` files, this README).
3. Repo **Settings → Pages → Build and deployment → Deploy from a branch**, pick `main` / `/ (root)`, Save.
4. Wait ~1 min. Your site:
   - Landing page: `https://<user>.github.io/minty-decks/`
   - Master deck: `.../Minty-Proactive-Commerce-Deck.html`
   - Macy's example: `.../Minty-for-Macys-Deck.html`

## Notes
- Each deck is one file — fonts, logos, and images are all inlined, so links never break.
- To make a deck the site's homepage instead of the landing page, rename it to `index.html`.
- For a private/internal link, use a private repo + an org-restricted Pages site, or a host like Netlify/Vercel (drag-and-drop the same folder).
