# Rachel's Reading Companion

> **Free, evidence-based digital literacy toolkit**
> RTN Communication & Literacy • Rachel Terra Norton, MS, CCC-SLP

⚠️ **All Rights Reserved** — you may view this code but may not copy, modify, distribute, or use it without written permission. See [LICENSE](./LICENSE).

---

## About

A **self-contained** JavaScript web app — no external site dependencies. Every tool runs within the app and navigates back to the toolkit hub via a sticky top nav bar.

## Tools

| Page | File | Description |
|---|---|---|
| Toolkit Hub | `index.html` | Landing page — 6 tool cards + quick-start guide link |
| Quick Guide | `rrcguide.html` | Research-backed how-to for each tool |
| Mystery Letters | `mystery-letters-game.html` | Letter-sound correspondence game |
| Word Collector | `word-collector.html` | A–Z vocabulary word bank |
| Word Scientist | `word-scientist.html` | Structured Word Inquiry cards |
| Pattern Detective | `pattern-detective.html` | Spelling pattern investigation |
| Fluency Lab | `fluency-lab.html` | Flash cards, repeated reading, grids, phrases |
| Phonics Friend | `phonics-friend.html` | Comprehensive phonics reference + practice |

---

## Design System

- **Fonts:** Fraunces (headers) + DM Sans (body) + Nunito Sans + Cormorant Garamond (app-specific)
- **Colors:** Pastel rainbow (rose, peach, yellow, mint, sky, lavender, lilac)
- **Features:** Scroll reveal, floating shapes, confetti, print CSS, accessibility

---

## Running Locally

Each page is standalone HTML — no build step needed.

```bash
git clone https://github.com/traumainformedslp-rachel/rachels-reading-companion.git
cd rachels-reading-companion
python3 -m http.server 8000
# Open http://localhost:8000/index.html
```

## Deployment

Deploy via GitHub Pages from the root directory, or drop the files on any static host. All navigation is relative — no server configuration required.

---

*© 2025–2026 Rachel Terra Norton / RTN Communication & Literacy. All Rights Reserved.*
