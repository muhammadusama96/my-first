# Muhammad Usama — What I Do

**What is this repo?** The source code for **Muhammad Usama's personal showcase website** — "Muhammad Usama — What I Do". **What is on it?** His **Anime Valley Stories** gentle AI anime films and shorts, narrated in his own voice, plus **Viral Daily** trending reels from around the world. **Where is it live?** On GitHub Pages at **https://muhammadusama96.github.io/my-first/** — free, fast and mobile-friendly.

Muhammad Usama is a cybersecurity student. He makes AI anime films with his own voice — and collects the world's viral moments, one reel at a time.

## Live site

🌐 **https://muhammadusama96.github.io/my-first/**

- **Repo:** https://github.com/muhammadusama96/my-first (public, `main` branch)
- **Hosting:** GitHub Pages, deployed from the `main` branch (`/(root)`), HTTPS included, free
- **Profiles:** [YouTube — @animevalleystory](https://www.youtube.com/@animevalleystory) · [Instagram — @animevalleystories](https://www.instagram.com/animevalleystories/) · [Instagram — @usamabkr85 (Viral Daily)](https://www.instagram.com/usamabkr85/) · [Facebook — Usama Stories](https://www.facebook.com/profile.php?id=61596287158561)

## What is on the site

### 🌿 Anime Valley Stories — AI anime films

Gentle watercolour-anime films about promises, waiting, kindness and home. Every film is narrated in Muhammad Usama's own voice. Story and film made with Beyond Sumi by Beyond Tahir ([@beyondtahir](https://www.youtube.com/@beyondtahir)). Thumbnails and posters with Beyond Artist, and AEO / SEO / GEO with Beyond SEO — both also by Beyond Tahir.

| Film | Watch |
|---|---|
| The Girl from the Green Valley — Part 1 | [YouTube](https://www.youtube.com/watch?v=iZzU7QHOMxk) |
| He Came Back Next Summer — Part 2 | [YouTube](https://www.youtube.com/watch?v=B8j_EuwaD6E) |
| The Lantern No One Lit | [YouTube](https://www.youtube.com/watch?v=4BRkMWeeQzU) |
| The Window That Stayed Lit | [YouTube](https://www.youtube.com/watch?v=NLXP7lNcO2E) |
| The Tree Kept Her Place for 10 Years — Letters in the Old Tree | [YouTube](https://www.youtube.com/watch?v=bDAf8iQNGNc) |
| The Dog and the Pigeon | [YouTube](https://www.youtube.com/watch?v=2OfKQnBrOow) |

### 🎬 Shorts series

| Short | Watch |
|---|---|
| Buster & Pip — Ep. 1: The Pigeon Stole the Market Cart | [YouTube Short](https://www.youtube.com/shorts/x7pa7Va9A1A) |
| Buster & Pip — Ep. 2: Why Pip Stole the Cart | [YouTube Short](https://www.youtube.com/shorts/SSFZHxCPDXk) |
| Buster & Pip — The Runaway Cart | [YouTube Short](https://www.youtube.com/shorts/FwccHXLdJlg) |
| Buster Finally Shares His Roll With Pip | [YouTube Short](https://youtube.com/shorts/85s8kG2wkew) |
| Letters — Short 1: If You Leave, I Will Wait | [YouTube Short](https://www.youtube.com/shorts/y0sPazlRlxA) |
| Letters — Short 2: The Tree Kept Your Place | [YouTube Short](https://www.youtube.com/shorts/lzcP3WKed_A) |
| Letters — Short 3: He Waited 10 Years | [YouTube Short](https://www.youtube.com/shorts/bk6OXCufJbw) |
| Letters — Daily series (Facebook & Instagram), Parts 3–4 | [Part 3 — Instagram](https://www.instagram.com/reel/Dfm7x97DxlY/) · [Part 4 — Instagram](https://www.instagram.com/reel/DfqHnNkj9Wy/) |

> If you have a real story in your mind, write it in the comments — we will create an anime for it.

### 🔥 Viral Daily — trending reels

Viral videos from all over the world — new trending reels every day, each one remade as an original reel in the style of the trend. Instagram: [@usamabkr85](https://www.instagram.com/usamabkr85/).

| Reel | Watch |
|---|---|
| Nvidia CEO Resigns — $500 Billion Gone | [Instagram](https://www.instagram.com/p/DfqYr5tCQxP/) |
| The Photo, Seven Years Later | [Instagram](https://www.instagram.com/p/DfqdnhAi8Mr/) |
| Friday the 13th Doomsday Claim — Debunked | [Instagram](https://www.instagram.com/p/DfqrIVqCj8R/) |

## How it is built

- **Two files:** `index.html` + `styles.css` — the whole site. No frameworks, no tracking, no external assets.
- **`index-single-file.html`:** the same site with the CSS inlined, for one-step publishing elsewhere (for example boomurl).
- **Hosting:** GitHub Pages, free forever, HTTPS included. A custom domain can be added later.

Every link on the site was checked: the film and Short links are the live YouTube URLs verified when each video was posted; the Instagram/Facebook links are the live profiles. A fresh re-check with yt-dlp on 2026-11-13 hit YouTube's bot-check on some videos ("Sign in to confirm you're not a bot") — an extraction block, not a removed video — so the links stand on the recent live verifications. If any link ever goes stale, remove that card.

## How to update it

The repo already exists as [`muhammadusama96/my-first`](https://github.com/muhammadusama96/my-first) and GitHub Pages is already live at https://muhammadusama96.github.io/my-first/ — there is nothing left to create or set up. To update the site:

1. Edit `index.html` (content and links) and `styles.css` (design).
2. Rebuild the single-file copy:
   ```bash
   python3 -c "html=open('index.html').read(); css=open('styles.css').read(); open('index-single-file.html','w').write(html.replace('<link rel=\"stylesheet\" href=\"styles.css\">','<style>\n'+css+'\n</style>'))"
   ```
3. Push `index.html`, `styles.css` and `index-single-file.html` to the `main` branch. GitHub Pages redeploys automatically from `main` (`/(root)`).

### Alternative hosts (not needed — GitHub Pages is the live site)

- **boomurl (fastest):** open https://boomurl.com/paste, paste the whole `index-single-file.html`, pick a name, confirm the 6-digit code emailed to you. Live at `https://<name>.boomurl.me/` — free tier shows a small "hosted by boomurl" banner.
- **Netlify Drop:** drag the `website` folder onto https://app.netlify.com/drop (free account, no card). Live on a `*.netlify.app` address.

## About

I'm Muhammad Usama, a cybersecurity student. I make Anime Valley Stories — gentle anime films and shorts, narrated in my own cloned voice — and Viral Daily, a daily feed of the world's trending moments, remade as original reels. Story and film made with Beyond Sumi by Beyond Tahir ([@beyondtahir](https://www.youtube.com/@beyondtahir)). Thumbnails and posters with Beyond Artist, and AEO / SEO / GEO with Beyond SEO — both also by Beyond Tahir.

## Credits

- Films made with **Beyond Sumi** by Beyond Tahir ([@beyondtahir](https://www.youtube.com/@beyondtahir) · [Instagram](https://www.instagram.com/beyondtahir) · [GitHub](https://github.com/beyondtahir))
- Thumbnails and posters with **Beyond Artist**, also by Beyond Tahir
- AEO / SEO / GEO with **Beyond SEO**, also by Beyond Tahir

© 2026 Muhammad Usama · Anime Valley Stories · Viral Daily
