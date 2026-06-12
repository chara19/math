# TODO — placeholders to fill in

Work through this list before going live. Most items are find-and-replace in `index.html`.

---

## 1. Personal info

All resolved — `Khalil Bazgour` is in the footer, the portrait alt, and the page title now reads `Khalil math`.

## 2. Visible `[TODO: …]` markers in copy

These show up rendered on the page until you replace them. Search for the exact bracket strings:

- `[TODO: fréquence]` — frequency of written feedback to parents (in the Méthode section, item 02). Example: `tous les quinze jours`
- `[TODO: ajouter un lien si disponible]` — Fullstack Mathematics link, if you want to publish one. If none, just delete that `<p class="project-link-note">…</p>` line entirely
- `[TODO: quartier]` — your neighborhood in Rabat (contact section). Example: `Agdal`
- `[TODO: délai]` — typical response time (contact section). Example: `généralement sous 24 heures`

> Note: the footer's "Dernière mise à jour" date is now filled in automatically by a small inline script that reads `document.lastModified`. Netlify and GitHub Pages both serve the file with a correct `Last-Modified` header based on file mtime, so the date updates by itself every time you redeploy. Nothing for you to fill in there.

## 3. Sanity check before going live

- [ ] All four find-and-replace items from section 1 are done
- [ ] All `[TODO: …]` strings from section 2 are replaced
- [ ] Portrait displays correctly in the hero (already wired to `portrait.jpg`)
- [ ] Tap each WhatsApp button on a phone — it should open WhatsApp with the prefilled message
- [ ] Tap the Upwork link — it should open your profile in a new tab
- [ ] Tap the email link — it should open the user's mail app to a fresh message to you
- [ ] Page renders cleanly at 375px wide (iPhone SE) — the QR scan happens on a phone, so this is the screen that matters most
- [ ] Generate the QR code from the final deployed URL and verify it scans

## 4. Optional polish

- **Open Graph image** for social/WhatsApp link previews. Currently none — link previews will show the page title only. Add `<meta property="og:image" content="…">` in the `<head>` if you want a thumbnail (you can reuse `portrait.jpg`, but a wider 1200×630 image works better for previews).
- **Favicon.** Currently none. Drop a `favicon.ico` into the folder and add `<link rel="icon" href="/favicon.ico">` to the `<head>`.
- **MP\* footnote.** The intro line above the programs ends with `MP*`. If parents won't recognize the prépa abbreviations, consider adding a small definition (e.g. *"MP\* : deuxième année de prépa scientifique, voie d'excellence"*) under the intro line.
