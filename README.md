# Tutoring website — Khalil [TODO: nom]

Single-page static site for a math tutoring practice in Rabat. French only. No framework, no build step, no JavaScript.

## Files

- `index.html` — the page
- `styles.css` — mobile-first stylesheet, deep navy accent
- `TODO.md` — every placeholder that must be filled in before going live

## Before deploying

Open `TODO.md` and work through it top to bottom. Most placeholders are find-and-replace: `TODO-NUMBER`, `TODO-EMAIL`, `TODO-UPWORK-URL`, and the visible `[TODO: …]` strings. There's also one image placeholder in the hero (a circular spot) — drop a `portrait.jpg` into the folder and swap the placeholder `<div>` for an `<img>` (see the HTML comment in the hero).

## Deploy — Netlify (drag-and-drop)

Open <https://app.netlify.com/drop>, then drag this folder onto the upload zone. Netlify returns a live URL within a few seconds (something like `random-name.netlify.app`). To use a custom domain, go to **Site settings → Domain management → Add custom domain** and follow the DNS instructions. Subsequent updates can be made by dragging the folder again, or by connecting a Git repository for automatic deploys.

## Deploy — GitHub Pages

Push this folder to a public GitHub repository (`git init`, commit, push to a new repo). In the repo settings, open **Pages**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, then save. The site goes live at `https://<your-username>.github.io/<repo-name>/` after a minute or two. Any subsequent push to `main` redeploys automatically.

## After it's live

Generate the QR code from the final URL (any QR generator works — `qr.io`, `qrcode-monkey.com`, or the `qrencode` CLI). Put the QR on the flyers; nothing else on this page needs to change for QR distribution.
