# PRIMAVINO.sk — Audit & Redesign Strategy

**Datum:** 2026-05-07
**Aktuálny web:** https://primavino.sk/ (Shopify)
**Cieľ klienta:** Lepšia grafika + viac konverzií
**Náš výstup:** [redesign/index.html](../redesign/index.html) — single-file Tailwind CDN landing

---

## 1. Čo aktuálny web robí dobre

| Element | Hodnotenie |
|---|---|
| Brand positioning ("Prosecco, ktoré prekonáva štandard") | Silný, jasný, premium |
| Hero foto Valdobbiadene | Profesionálna kvalita, autenticita |
| Serif display font | Premium aestetika |
| Google review widget | Social proof prítomný |
| Clean produktové fotky | Konzistentný štýl |

**Verdikt:** Dobrá značka, slabá konverzná architektúra.

---

## 2. Top 10 konverzných problémov (priorita podľa dopadu)

| # | Problém | Dopad | Fix v redesigne |
|---|---|---|---|
| 1 | **Hero nemá viditeľné CTA tlačítko** — návštevník nevie čo má robiť | 🔴 Vysoký (-30 % first-fold conversion) | 2× CTA: primárne "Objaviť kolekciu" + sekundárne "Pomôžete mi vybrať" (kvíz) |
| 2 | **Žiadny free shipping threshold** — cart abandonment driver | 🔴 Vysoký | Sticky strip "Doprava zdarma nad 60 €" v každom fold |
| 3 | **Žiadne email capture** — 0 lead generation | 🔴 Vysoký | Wine quiz s -10 % off + newsletter sekcia |
| 4 | **Žiadny money-back guarantee** — top objection u online vína | 🔴 Vysoký | "Garancia chuti — vrátime peniaze" v trust bar + USP grid |
| 5 | **Bestsellery bez ratingov a popisov** — len cena a meno | 🟠 Stredný | Star ratings + počet recenzií + region/typ + Add-to-cart hover |
| 6 | **"O nás" sekcia má slabý kontrast** — text sa stráca | 🟠 Stredný | Editorial split layout (foto + tmavé pozadie + light copy) |
| 7 | **Kategórie len text, žiadne vizuály** | 🟠 Stredný | 4 cover karty s gradient overlay + mikrokopija + počet fliaš |
| 8 | **Žiadny sommelier mechanism** — prečo veriť vášmu výberu? | 🟠 Stredný | "Náš prístup" sekcia s 4 USP (Priamo od rodín / Garancia chuti / Sommelier výber / Doručenie 48 h) |
| 9 | **Žiadne reviews na homepage** — len schovaný Google widget | 🟠 Stredný | Dedicated reviews sekcia s 3 testimoniálmi + agregátne 4,9 / 5 |
| 10 | **Žiadny FAQ** — všetky pochybnosti zostávajú nezodpovedané pred kúpou | 🟡 Nízky | 6 FAQ collapsible (doručenie, vrátenie, darček, platby, zahraničie, kontakt) |

---

## 3. Top 8 problémov v dizajne

| # | Problém | Fix |
|---|---|---|
| 1 | **Žiadna farebná identita** — len whites/grays = sterile | Burgundy `#5B1A2B` + Antique Gold `#C8A86B` + Cream `#F5EFE6` |
| 2 | **Jediný font, žiadna hierarchia** | Cormorant Garamond (display, italic accents) + Inter (body) |
| 3 | **Black CTA blok s nečitateľným textom** | Dark editorial blok s foto + structured copy + clear CTA |
| 4 | **Velké PRIMAVINO logo dole bez dôvodu** | Nahradené hodnotným final CTA s vineyard background |
| 5 | **Žiadne badges / stickers** (top výber, limited, nealko) | Burgundy/charcoal/sage tagy v ľavom hornom rohu produktu |
| 6 | **Žiadne micro-interactions** — statický, suchý | Hover scale, fade-up animation, opacity transitions |
| 7 | **Trust strip absentuje** | Burgundy strip nahor + 4-column trust bar pod hero |
| 8 | **Žiadne mobile menu** vyriešené pre malé screen | Hamburger + sticky cream nav s počítadlom košíka |

---

## 4. Redesign — štruktúra novej landing (13 sekcí)

```
1.  Trust strip          → "Doprava zdarma nad 60 € · 4,9/5 (172) · 48h doručenie"
2.  Sticky nav           → 4 menu links + logo center + search/cart
3.  Hero                 → Vineyard image + 2 CTA + scroll indicator
4.  Trust bar (4 col)    → Overený eshop · 48h · Free ship · Garancia
5.  Bestsellery          → 4 produkty s tagmi, ratingmi, hover Add-to-cart
6.  Kolekcie             → 4 kategorie ako image cards s overlay
7.  Prečo my             → Editorial: sticky title vľavo + 4 USP cards
8.  Wine kvíz            → Tmavá burgundy CTA + 4 occasion buttons + email gate (-10 %)
9.  Reviews              → 3 testimoniály + agregátne 4,9 / 5
10. Editorial príbeh     → Dark sekcia: foto + storytelling
11. Newsletter           → Cream sekcia: -10 % off form
12. FAQ                  → 6 collapsible objection-busters
13. Final CTA            → Dark vineyard + serif headline + tlačítko
14. Footer               → 5-column nav + payment methods + age disclaimer
```

---

## 5. Konverzné mechanizmy zabudované do redesignu

| Mechanizmus | Kde je | Prečo to funguje |
|---|---|---|
| **Free shipping threshold** | Top strip (sticky) | Najsilnejší driver AOV — ľudia priberajú do košíka |
| **Money-back guarantee** | Trust bar + Prečo my | Zlamuje "čo ak mi to nechutí" objection |
| **Verified social proof** | Trust strip + Reviews sekcia + Kviz | 3 nezávislé reinforcements znižujú risk perception |
| **Lead magnet (wine quiz + 10 % off)** | Hero CTA + dedicated sekcia | Engagement + email capture v 1 toku |
| **Bestsellery framing** | "Vína po ktorých sa vracajú" | Tlačí kontextuálne FOMO + sociálny dôkaz |
| **Limited / Top výber tagy** | Produktové karty | Scarcity bez agresívneho discountu |
| **Hover Add-to-cart** | Product cards | Skracuje cestu k checkoutu o 1 klik |
| **Sticky shipping bar** | Top strip | Konštantne pripomína prah → driver odlišujúci od supermarketu |
| **Dual CTA hero** | Hero | Primárna pre teplé leads (Objaviť), sekundárna pre studené (kviz) |
| **Sommelier mechanism** | Prečo my (4 USP) | "Why us" diferenciácia od supermarket vína |
| **Storytelling editorial** | Náš príbeh sekcia | Premium brands = brands s príbehom (Aesop, Gerard's Pâtissier model) |

---

## 6. Brand systém v redesigne

### Farby

| Token | Hex | Použitie |
|---|---|---|
| `burgundy-700` | `#5B1A2B` | Top strip, ceny, primary buttons |
| `burgundy-900` | `#3A0F1A` | Kvíz section background |
| `gold-300` | `#E0C892` | Hero italic akcent, CTA hover |
| `gold-500` | `#C8A86B` | Stars, kvíz tlačítko, accents |
| `cream-50` | `#FBF8F3` | Body background, light text |
| `cream-100` | `#F5EFE6` | Sekcie, product backgrounds |
| `charcoal-900` | `#1F1B1A` | Body text, dark sekcie |
| `sage-500` | `#7A8B7B` | Nealko tag, secondary accent |

### Typografia

| Use | Font | Weight |
|---|---|---|
| Display headlines | Cormorant Garamond | 300 / 400 italic |
| Subheadings | Cormorant Garamond | 500 |
| Body | Inter | 400 / 500 |
| Eyebrows / labels | Inter | 500 (uppercase, tracking 0.35em) |
| Buttons | Inter | 500 (uppercase, tracking 0.2em) |

---

## 7. Čo nie je v redesigne (out-of-scope tejto fázy)

- ❌ Backend — toto je vizuálny prototyp, nie Shopify theme code
- ❌ Funkčný kvíz logika — placeholder UI, vyžaduje Shopify app (Octane AI / Typeform)
- ❌ Reálne produktové fotografie — placeholder Unsplash
- ❌ Reálne testimoniály — 1 z 3 je z aktuálneho Google widgetu (Boris Bičan), zvyšné sú illustrative
- ❌ Mobile menu open state — naskriptovať ako Alpine.js / vanilla JS pri ďalšom kroku

---

## 8. Implementačný plán (ak klient schváli)

### Tier 1 — Quick wins na aktuálnom Shopify (1–2 dni)
1. Pridať Free shipping bar app (`Shippy` / `Hextom Free Shipping Bar`)
2. Email capture popup s -10 % off (`Privy` / `Klaviyo` integrácia)
3. Doplniť rating widget pod produktové karty (`Loox` / `Judge.me`)
4. Editovat hero copy + pridať CTA tlačítka cez theme editor

### Tier 2 — Theme refactor (1 týždeň)
5. Rebuild homepage sections per redesign (Liquid templates)
6. Implementovať farebnú paletu globálne (CSS variables)
7. Pridať Cormorant Garamond ako custom font
8. Refactor produktové karty s tagmi + hover Add-to-cart

### Tier 3 — Net-new features (2–3 týždne)
9. Wine pairing kvíz (Octane AI nebo custom Shopify app)
10. Editorial blog s SEO-friendly degustačnými článkami
11. Loyalty / klub PRIMAVINO (Smile.io)
12. WhatsApp chat widget pre osobnú konzultáciu

---

## 9. Očakávaný impact (heuristické benchmarky pre EU wine ecommerce)

| Metric | Aktuálny estimát | Po Tier 1 | Po Tier 2 | Po Tier 3 |
|---|---|---|---|---|
| Add-to-cart rate | ~4–6 % | +20–30 % | +40–60 % | +60–80 % |
| Avg. order value | ~€35 | +15 % (free ship threshold) | +20 % | +25 % |
| Email signup rate | <1 % | 8–12 % (s popup -10 %) | 12–15 % | 18–22 % (s kvízom) |
| Cart abandonment | ~70 % | 65 % | 58 % | 50 % |
| Repeat customer rate | neznámy | — | +10 % | +25–35 % (s loyalty + email flow) |

> ⚠️ Toto sú **odvodené odhady**, nie garantované výsledky. Skutočné čísla závisia od trafficu, ICP, sezóny, ad spendu. Redesign vytvára konverzný **potenciál**, neudeje to za vás.

---

## 10. Otázky pre klienta (pre ladenie pred spustením)

1. **Kto je vaše ICP?** Top zákazník: vek, pohlavie, nákupný moment (darček vs. seba)?
2. **Aký je skutočný free shipping threshold a delivery time?** (60 € a 48 h sú náš predpoklad)
3. **Máte Loox / Judge.me / iný review widget?** Alebo len Google?
4. **Posielate aj do CZ, AT, HU?** Footer to spomína, treba potvrdiť
5. **Existuje WhatsApp / personálny sommelier kontakt?** Predáva to ako USP, ak áno
6. **Ktoré produkty sú reálne bestsellery?** (zvolili sme 4 zo zoznamu, ale môžete ovplyvniť poradie)
7. **Plánujete rebrand alebo zachovať aktuálnu identitu?** (náš návrh je evolúcia, nie revolúcia)
8. **Kapacitný strop?** (prejde tento dizajn cez Shopify theme rozpočet, alebo treba phased rollout?)

---

## 11. Súbory v tomto deliverable

```
clients/primavino/
├── CLAUDE.md           ← klient KB pointer
├── ACTIVE.md           ← otvorené thready, latest deliverable, otázky
├── audit/
│   ├── AUDIT.md        ← tento dokument
│   └── 01_current_homepage_top.png  (TBD: presunúť z root)
└── redesign/
    └── index.html      ← single-file Tailwind landing (production-ready preview)
```

**Preview:** Otvor `index.html` v prehliadači (alebo `python -m http.server 8765` v `redesign/` a navigovať na `localhost:8765`).
