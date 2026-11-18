# Mo Logo Library

The official logo assets of **Mo · My Oilfield · myoilfield.xyz**.
All future Mo logos, headers and brand uses follow the standard in this repo.

## The standard — Mo composite logo (组合 LOGO)

The composite logo = gold coin mark + two lines of wordmark, on a **transparent** background.

| File | Use | Wordmark |
|---|---|---|
| `Mo-Logo-Composite-HD.png` | Light backgrounds (white / light) | "My Oilfield" in **black** |
| `Mo-Logo-Composite-HD-dark.png` | Dark backgrounds (navy / black) | "My Oilfield" in **white** |

- Size: 2152 × 544 px (HD, ~4× the original 263 × 68 master).
- Top line is two-tone: **"Mo" in rich gold** — RGB (233, 172, 10), bright but warm and heavy; **"Connectivity All" in navy blue** — the globe's blue, RGB (12, 56, 122), echoing the blue earth on the coin.
- Coin mark is the real `Mo-Logo-Coin-512.png` — never redrawn.

### Layout rules (finalized 2026-11-18)

These three rules are the standard. Any rebuild must satisfy all three, verified by pixel measurement — not by eye:

1. **Right edges flush** — the right edge of "All" (gold line) and the right edge of "d" ("My Oilfield") are exactly aligned (0 px difference).
2. **Text height = coin height** — the text block (top of "Mo Connectivity All" to bottom of "My Oilfield", descenders included) is exactly the visible height of the gold coin (499 px in the HD build), sharing the same top and bottom edges.
3. **No clipping** — every glyph is complete, including the descender of "y" in "My"; the artwork has a clear margin on all sides (never flush to the canvas edge).

## Other files

| File | Notes |
|---|---|
| `logo.svg` | Legacy vector logo (pre-existing). The HD PNGs above are the current standard for the composite lockup. |

## Links (CDN)

> jsDelivr caches branch files for a while after an update. If a link still shows an older version, use the `raw.githubusercontent.com` link instead — it always serves the latest commit.

- Light: https://cdn.jsdelivr.net/gh/Momyoilfield/logo-files@main/Mo-Logo-Composite-HD.png
- Dark: https://cdn.jsdelivr.net/gh/Momyoilfield/logo-files@main/Mo-Logo-Composite-HD-dark.png
- Light (always latest): https://raw.githubusercontent.com/Momyoilfield/logo-files/main/Mo-Logo-Composite-HD.png
- Dark (always latest): https://raw.githubusercontent.com/Momyoilfield/logo-files/main/Mo-Logo-Composite-HD-dark.png

---
Mo · My Oilfield · myoilfield.xyz — Trust · Saw · Achieve
