# Muhammad Usama — Showcase Website

Live at https://muhammadusama96.github.io/my-first/

A free, fast, mobile-friendly site showing all of Usama's work: Anime Valley
Stories (anime films + shorts), Viral Daily (viral reels) and GTA 6 stream
clips (@Gta.Clipper96).

## What this rebuild is (22 Nov 2026)

The old single-page site is replaced by a rebuilt **7-page site in one
self-contained file**, with hash routing — every page is a section inside
`index.html`, switched by JavaScript on the `#hash`:

| # | Page | URL hash |
|---|------|----------|
| 1 | Home | `#home` |
| 2 | What I do | `#overview` |
| 3 | Work | `#work` |
| 4 | Channels | `#channels` |
| 5 | Deeds log | `#log` |
| 6 | How I make it | `#process` |
| 7 | Your story | `#story` |

- **3D hero lantern** — a real Three.js lantern rendered on a canvas on the
  home page (no still image), with a still fallback behind it.
- **SEO / AEO / GEO** — JSON-LD with 27 nodes, including 22 VideoObjects, one
  per film, Short and reel; canonical URL, Open Graph and geo meta included.
- **No frameworks, no tracking.** The only external dependency is Google
  Fonts. All images, CSS and JavaScript are inlined in the single file.

## Files

- `index.html` — the whole site (12.6 MB, self-contained).
- `index-single-file.html` — an identical copy of `index.html`, kept so the
  old "one-step publishing" route still works (paste it on boomurl / Netlify
  Drop exactly as before).
- `README.md` — this file.
- `styles.css` — **no longer used.** The rebuilt file inlines all CSS, so
  the old `styles.css` in the repo is orphaned. It can be deleted from the
  repo, or left in place — it does not affect the site either way.

## Latest content on the site (verified in the file, 20 Nov 2026)

- Green Valley Part 5 — "A Leaf to Carry Home" (newest film):
  https://www.youtube.com/watch?v=8XCGYVnUf0o
- Letters in the Old Tree, Part 12 — "The Bench Is Mended":
  https://www.instagram.com/p/Df-OhAsOs2E/
- Letters in the Old Tree, Part 11 — "The Hollow Is Empty":
  https://www.instagram.com/p/Df8M2yQOgya/
- Buster & Pip Ep. 5 — "He Left Bread Out on Purpose":
  https://www.youtube.com/shorts/PLRYN8M9JtI
- GTA 6 clips — @Gta.Clipper96, launched 20 Nov 2026 (best moments from
  Kai Cenat's GTA 6 streams, four clips live so far — profile links only, no
  individual clip URLs in the file):
  https://www.instagram.com/gta.clipper96/
- Earlier films, Shorts and Viral Daily reels are all listed on the Work page
  with their live links (22 VideoObjects in the JSON-LD).

NOT on this version of the site yet: Green Valley Part 6, Letters Part 13/14,
and Buster & Pip Ep. 6 were not in the exported file — they go in with the
next update, once their live links are known. No video URL was guessed here.

## Channels

- Anime Valley Stories — YouTube: https://www.youtube.com/@animevalleystory
- Anime Valley Stories — Instagram: https://www.instagram.com/animevalleystories/
- Anime Valley Stories — Facebook ("Usama Stories"): https://www.facebook.com/profile.php?id=61596287158561
- Viral Daily — Instagram (@usamabkr85): https://www.instagram.com/usamabkr85/
- GTA clips — Instagram (@Gta.Clipper96): https://www.instagram.com/gta.clipper96/
- GTA clips — Facebook (GtaClipper96): https://www.facebook.com/profile.php?id=61596312286692

## Credit

Films made with Beyond Sumi by Beyond Tahir (@beyondtahir), credited on every
video. The site's "Credit & thanks" section on the Your story page says:
"My films, this website and my GitHub skills collection are all built with
the skills created by Beyond Tahir (@beyondtahir) — his effort and his craft
sit behind every video I publish."

## Publish / update — GitHub Pages (free, permanent, no banner)

The repo is `muhammadusama96/my-first`, branch `main`, Pages deploys from
`main` root. Push via the github.com web UI — see `PUSH-STEPS.md` for the
exact clicks. (The Muse GitHub App cannot write to this repo — it gets 403 —
so do not try to push from here.)

## Updating the site

The site is edited as the Muse artifact and re-exported as one HTML file.
To publish a new version: replace `index.html` AND `index-single-file.html`
with the new export (both files are always identical), update the "Latest
content" list above with the new releases and their verified live links, and
re-publish by the same route. Never guess a video URL — only links verified
live go on the site.
