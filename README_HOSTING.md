# Host ALLYDASH Anywhere (Inline Version)

This version has **no external files**. Just open `index.html` in a browser or host it on any static site host.

## Option A — **Open locally** (fastest)
- Double-click `index.html`. It will run entirely in your browser.

## Option B — **GitHub Pages** (free, stable)
1. Create a new repo on GitHub (public). Name it anything.
2. Upload `index.html` to the root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch** → **Branch: main** → **/ (root)** → **Save**.
5. Wait ~1 min. Your site will appear at `https://YOUR-USER.github.io/REPO-NAME/`.

## Option C — **Netlify Drop** (one drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag `index.html` onto the page.
3. Netlify gives you a public URL instantly. Done.

## Option D — **Glitch** (fast editor + live URL)
1. Visit https://glitch.com → **New Project → Hello-webpage**.
2. Replace their `index.html` with this one.
3. Copy the live URL.

## Option E — **CodePen** (quick demo)
1. Open https://codepen.io/pen/
2. Paste everything from `index.html` into the HTML panel.
3. Save → share the pen URL.

## Embedding live metrics
- Publish a Google Sheet or chart (File → Share → Publish to web).
- Insert its `<iframe>` into the **Impact Tracker** section of `index.html`:

```html
<iframe src="PASTE_PUBLISHED_SHEET_URL" width="100%" height="100%" frameborder="0"></iframe>
```

That’s it. This page is self-contained and will work anywhere.
