# Omar Elewa — Portfolio

Copywriter & Brand Strategist · Cairo. Naming, verbal identity, brand strategy and advertising — in Arabic & English.

This is a static website (plain HTML/CSS/JS — no build step, no dependencies). It is designed to be hosted free on **GitHub Pages**.

---

## Structure

```
portfolio/
├── index.html                  ← the portfolio home (the gallery)
├── .nojekyll                   ← tells GitHub Pages to serve files as-is
├── README.md
└── work/                       ← the ten case studies
    ├── tajed.html              · Tajed — Taj City (live & built)
    ├── akleh-shawarma.html     · Akleh — advertising campaign
    ├── ava-rumor.html          · Ava "I Heard a Rumor" — launch campaign
    ├── zahran.html             · Zahran Cookware — brand strategy
    ├── motion.html             · Motion — naming rationale
    ├── sweep.html              · Sweep — naming rationale
    ├── beauty-brand.html       · A Beauty Brand — naming & strategy
    ├── italian-deli.html       · An Italian Deli — naming & strategy
    ├── lebanese-restaurant.html· A Lebanese Restaurant — naming
    └── alexandria.html         · A Destination in Alexandria — naming
```

Each case study keeps its own art direction and has a small "← Omar Elewa" link (bottom-left) back to the home page.

---

## How to publish it free on GitHub Pages

Your site will be live at: **https://omarelewa.github.io/portfolio/**

### Option A — No command line (easiest)

1. Sign in to GitHub. Create a **new repository** named **`portfolio`**. Set it to **Public**.
   (A project repo can be named anything — `portfolio` will serve at `username.github.io/portfolio/`.)
2. On the new repo page, click **"uploading an existing file"**.
3. Drag in **`index.html`, `README.md`, `.nojekyll`, and the whole `work` folder**
   (keep `work/` as a folder — don't flatten it). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source = **Deploy from a branch**,
   Branch = **main**, folder = **/ (root)**. Save.
5. Wait ~1 minute. Your site is live at: **https://omarelewa.github.io/portfolio/**

> Tip: if you don't see `.nojekyll` when dragging files, enable "show hidden files" in your OS,
> or just skip it — the site still works without it.

### Option B — Command line (git)

```bash
# inside the unzipped "portfolio" folder
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/omarelewa/portfolio.git
git push -u origin main
```

Then enable Pages under **Settings → Pages** as in step 4 above.

---

## Adding a contact section later

There's a ready-made, commented-out contact block at the bottom of `index.html`.
To turn it on: remove the surrounding `<!-- -->`, fill in your email / LinkedIn / Instagram,
and add a `Contact` link inside the `<nav>`. No rebuild needed.

---

## Credits

Type: Fraunces · Hanken Grotesk · IBM Plex Mono · Aref Ruqaa (Arabic).
Built as a static site, hosted on GitHub Pages.
