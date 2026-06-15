# Threedii Paint Studio — Case Study

> **Hand-painted, 3D-printed collectible figures** · e-commerce storefront + WhatsApp lead funnel.
> 🌐 **Live:** https://threedii-paint-studio.vercel.app  ·  📍 Colombia

<p align="center"><img src="docs/home.jpg" alt="Threedii Paint Studio — homepage" width="900"></p>

| | |
|---|---|
| **Role** | Solo front-end developer (freelance) |
| **Client** | Threedii — hand-painted, 3D-printed collectible figures |
| **Industry** | E-commerce · collectibles / made-to-order |
| **Stack** | React 19 · Vite 8 · React Router · Playwright · Lighthouse CI · Vercel |
| **Status** | Live in production |

---

## Overview
Threedii is a Colombian studio that turns characters from films, games, comics and anime into **museum-grade collectible figures** — designed, 3D-printed and hand-painted to order. They needed a storefront that feels as premium as the product and turns visitors into real order conversations. I built the whole front-end solo.

## The client & the craft
Every Threedii piece is **made to order**:
- **Printed** in SLA resin or FDM + resin,
- **Hand-finished** with multi-layer airbrushing (plus NMM, OSL and washes for metallics, glows and depth),
- **18–50 cm tall**, some with **removable, interchangeable parts** (jaws, tongues, weapons),
- **~3–6 week** lead times per figure.

So the site isn't a "buy now" cart — it's a **catalog + quote funnel** that has to communicate craftsmanship and make it effortless to start a custom order.

## The catalog
Figures are organised by category — **Bustos · Películas · Cómics · Videojuegos · Anime** — each with its own universe, description and specs:

| Figure | Universe | Category |
|---|---|---|
| Némesis | Resident Evil | Games |
| Spartan | Halo | Games |
| Xenomorfo | Alien | Movies |
| Predator vs Dutch | Predator | Movies |
| RoboCop | RoboCop | Movies |
| Indoraptor | Jurassic World | Movies |
| Jafar | Aladdin (Disney) | Movies |
| Marciano | Mars Attacks! | Movies |
| Bane | Batman (DC) | Comics |
| Venom | Spider-Man (Marvel) | Comics |
| Broly · Cell · Majin Boo | Dragon Ball | Anime / Busts |

## What the site includes
A fast single-page storefront engineered to convert browsing into orders:
- **Hero** — bold brand intro with a clear "Pedir figura" call to action.
- **Catalog** — a **bento-grid gallery** with category filters and **hover image cycling**; clicking a figure opens a **detail view** with its universe, description and specs (material, finish, height, lead time), plus an **Instagram clip** of the real painted piece where available.
- **Quote flow ("Cotizar")** — selecting a figure **prefills a request and opens a pre-written WhatsApp message**, so interest converts straight into a conversation (the studio's main sales channel).
- **Process & "Mira cómo lo hacemos"** — sections showing how the figures are designed, printed and painted.

## Screenshots
<p align="center"><img src="docs/full.jpg" alt="Full storefront — catalog, process and behind-the-scenes" width="640"></p>

## What I delivered (engineering)
- **Performance-first SPA** — build-time responsive images (`sharp`, 400 / 800 / 1200w `srcset`), scroll-reveal animations, and a desktop custom cursor.
- **Lead generation** — the figure → WhatsApp quote flow that turns the catalog into sales conversations.
- **SEO** — rich structured data (Organization, Service, ItemList), Open Graph / Twitter cards, an auto-generated sitemap and a `<noscript>` fallback for AI crawlers.
- **Hardened & measured** — a strict Content-Security-Policy and security headers, with a **Playwright + Lighthouse CI** pipeline enforcing performance, SEO and security budgets on every change.

## Tech stack
React 19 · Vite 8 · React Router v7 · component-scoped CSS · `sharp` · Playwright · Lighthouse CI · Vercel.

---

<sub>Code is proprietary to Threedii; this repository documents my work for portfolio purposes. Built by <a href="https://github.com/johnvergel-dev">John Vergel</a>.</sub>