# PRIMAVINO — Redesign Concept

Konverzný + vizuálny redesign landing page pre [primavino.sk](https://primavino.sk/) — premium e-shop s Proseccom a curated vínami z rodinných vinárstiev.

🔗 **Live preview:** https://adamkropacek.github.io/primavino-demo/

---

## Čo je v tomto repe

- [`index.html`](./index.html) — single-file landing (Tailwind CDN + Cormorant Garamond + Inter)
- [`AUDIT.md`](./AUDIT.md) — audit aktuálneho webu, top 10 konverzných problémov, brand systém, tier 1/2/3 implementačný plán

---

## TL;DR redesignu

**Aktuálny web:** silný brand, slabá konverzná architektúra (6/10).

**5 najväčších zmien:**

1. **Hero má 2 CTA** (browse + wine kvíz) — current nemal žiadne
2. **Free shipping threshold** v stickom strip — driver AOV +15 %
3. **Wine kvíz s -10 % off** — lead magnet (engagement + email capture)
4. **Trust bar pod hero** — overený eshop, 48h doručenie, garancia chuti
5. **Bestsellery s ratingmi a hover Add-to-cart** — krátí cestu k checkoutu o 1 klik

---

## Brand systém

| Token | Hex | Použitie |
|---|---|---|
| Burgundy | `#5B1A2B` | Top strip, ceny, primary buttons |
| Antique Gold | `#C8A86B` | Stars, kvíz CTA, accents |
| Cream | `#F5EFE6` | Sekcie, product backgrounds |
| Charcoal | `#1F1B1A` | Body text, dark sekcie |

**Fonty:** Cormorant Garamond (display, italic akcenty) + Inter (body)

**Voice:** elegantný, tichý, sebavedomý — žiadne výpredaje, žiadne urgency timery

---

## Štruktúra landing (13 sekcií)

```
1.  Trust strip (sticky)         → "Doprava zdarma nad 60 € · 4,9/5 · 48h"
2.  Sticky nav                   → 4 menu links + logo center + cart
3.  Hero                         → Vineyard + 2 CTA + scroll indicator
4.  Trust bar (4 col)            → Overený eshop · 48h · Free ship · Garancia
5.  Bestsellery                  → 4 produkty s tagmi, ratingmi, hover Add-to-cart
6.  Kolekcie                     → 4 kategorie ako image cards s overlay
7.  Prečo my                     → Editorial: sticky title + 4 USP cards
8.  Wine kvíz                    → Burgundy CTA + 4 occasion buttons + email gate
9.  Reviews                      → 3 testimoniály + agregátne 4,9 / 5
10. Editorial príbeh             → Dark sekcia: foto + storytelling
11. Newsletter                   → -10 % off form
12. FAQ                          → 6 collapsible objection-busters
13. Final CTA                    → Dark vineyard + serif headline + tlačítko
14. Footer                       → 5-column nav + payment methods
```

---

## Tech stack

- HTML5 + Tailwind CSS (CDN)
- Google Fonts: Cormorant Garamond + Inter
- Vanilla JS (žiadny framework)
- Single-file, zero build step
- Responsive (mobile-first)

---

## Implementačný plán (ak klient schváli)

### Tier 1 — Quick wins (1–2 dni)
Free shipping bar app · Email popup -10 % · Rating widget · Hero copy + CTA

### Tier 2 — Theme refactor (1 týždeň)
Rebuild homepage Liquid sections · Globálna paleta · Cormorant font · Product card refactor

### Tier 3 — Net-new features (2–3 týždne)
Wine pairing kvíz (Octane AI) · Editorial blog · Loyalty Klub PRIMAVINO · WhatsApp chat

---

## Disclaimer

Toto je **discovery prototype**, nie production-ready Shopify theme. Fotky sú Unsplash placeholder, kvíz UI je bez backend logiky, testimoniály sú illustrative (1 z 3 je z aktuálneho Google widgetu). Pred implementáciou treba potvrdiť reálne čísla (delivery, threshold) a doplniť reálne assety.

---

**Author:** Adam Kropáček · [scaleyourinfo](https://github.com/adamkropacek)
**License:** MIT (concept demo)
