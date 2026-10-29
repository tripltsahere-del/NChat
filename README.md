# NChat

A black-and-green 2009-style anonymous imageboard in one file (`index.html`). No build step, no dependencies.

## Put it on GitHub and make it public (GitHub Pages)

1. On github.com, click **New repository**, name it (for example `nchat`), set it to **Public**, and create it.
2. Click **Add file > Upload files**, drag in `index.html` (and this README if you like), then **Commit changes**.
3. Open the repository's **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/nchat/`.

## Good to know

- Posts are saved in each visitor's own browser (localStorage). GitHub Pages is static hosting, so visitors do not see each other's posts. A shared board needs a server or a database.
- Boards are addressed with a hash, for example `#school`, `#memes`, or any board name a visitor types when posting.
- To use it like an app on iPhone: open the site in Safari, tap Share, then Add to Home Screen.
