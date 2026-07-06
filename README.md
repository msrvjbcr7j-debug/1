# 🌴 Cassia Bintan Holiday Companion

A pocket-sized web app for your holiday at **Cassia Bintan** (Laguna Bintan estate, Bintan Island, Indonesia). Everything you need for the best time — no accounts, no internet required once loaded.

## What's inside

- **🏝️ Home** — live countdown to the trip (then "Day N of M" while you're there), today's plan, and a trip snapshot.
- **🗓️ Days** — a day-by-day itinerary, pre-filled with a great plan (arrival, beach day, adventures, spa day, departure) and fully editable: add, edit, tick off and delete activities.
- **🧭 Explore** — a curated guide to the resort and island: Kelong Seafood, Banyan Tree Spa, the Sebung mangrove tour, Treasure Bay lagoon, Tanjung Pinang day trips and more — each with an insider tip and an "add to itinerary" button.
- **🧳 Pack** — a tropical packing checklist grouped by category, with progress bar and your own custom items.
- **💰 Budget** — expense tracker with SGD/IDR totals, per-traveller split, and a quick currency converter with an editable rate.
- **🛟 Info** — the essentials: ferry logistics (Tanah Merah ⇄ BBT), time zone, visa on arrival, money & tipping, plugs, health, emergency numbers, and handy Bahasa Indonesia phrases.

All your edits (dates, itinerary, checklist, expenses) are saved on the device via `localStorage`.

## Running it

It's plain HTML/CSS/JS — no build step.

```bash
# any static server works, e.g.
python3 -m http.server 8000
# then open http://localhost:8000
```

Or deploy the repo to **GitHub Pages** (Settings → Pages → deploy from branch) and open it on your phone. It's a PWA: use *Add to Home Screen* and it installs like a native app and works fully offline — handy on the ferry and around the island.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire app (markup, styles, logic) |
| `manifest.webmanifest` | PWA manifest for home-screen install |
| `sw.js` | Service worker — cache-first, full offline support |

*Ferry times, prices and opening hours change — double-check anything time-critical before relying on it. Selamat berlibur!* 🌺
