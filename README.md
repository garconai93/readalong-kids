# ReadAlong Kids — Landing Page

Static landing page for **ReadAlong Kids**, the AI read-aloud companion for kids 5–10 that turns daily 10-minute practice into visible fluency gains (with weekly parent reports).

## Stack

- **Single-file** `index.html` (semantic HTML + modern CSS, no build tools, no JS framework).
- **Fonts:** Inter (UI) + Fraunces (display) via Google Fonts.
- **Design:** warm parental / educational vibe — dark mode with warm orange + rose + teal accents. Mobile-first, fully responsive.
- **No external images** — all visuals are inline SVG / CSS so the page loads instantly on GitHub Pages.
- **No tracking, no analytics** — privacy-first for a kids' product.

## Sections

1. Sticky nav with brand mark + CTA
2. Hero with phone mockup + floating live chips (streak / score / badge)
3. Trust logo strip
4. Problem statement (stats + comparison card)
5. How it works (3 steps)
6. MVP feature breakdown (6 cards)
7. Sample reading flow (annotated list + live mock screen with word-level highlights)
8. Testimonials (3 quotes)
9. Pricing (Starter / Family / School) with Most-popular ribbon
10. FAQ (7 details/summary, accessible)
11. Final CTA band → waitlist
12. Footer with product / company / legal columns

## Deploy

Deployed via **GitHub Pages** (free, no build):

- Repo: `garconai93/readalong-kids`
- Source: `main` branch, root (`/`)
- URL: <https://garconai93.github.io/readalong-kids/>

### Local preview

```bash
cd readalong-kids
python3 -m http.server 8000
# open http://localhost:8000
```

### Re-deploy after edits

```bash
git add -A
git commit -m "Update copy"
git push origin main
# GitHub Pages rebuilds in ~30s
```

## Notes

- All copy is placeholder, tailored to the ReadAlong Kids idea. Replace with real product info before launch.
- Email `hello@readalongkids.app` is illustrative — wire up a real inbox before going live.
- Pricing is illustrative ($9.99 / $14.99 / School-custom). Founding-family offer: lock early-bird for life via the waitlist.
