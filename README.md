# Platinum Press — CareStack-style Homepage

## V2 — structural 1/1 clone (`v2.html`) ← CURRENT
`v2.html` is a section-for-section structural clone of carestack.com's live homepage (captured 2026-07-06), re-branded to Platinum Press. Same section order, layouts, grids and proportions; all copy is original PP content, all photos are PP's own, PP palette (navy `#0A1A33` bands, blue `#064FBC` CTAs, ice-blue `#BFD9FF` accents on dark) and Geist + Inter type.

Sections (matching the reference order): announcement topbar → dark nav → split hero with Watch Overview media → Markets accordion + photo card → single-source economics stats band → dark industry-guide band → Our Work story carousel + mini CTA card → Capabilities (sticky rail + 5 image/link-list cards with scroll-spy) → Innovations gradient band (Combination Carton + 2x2 tiles) → Why Platinum Press stacked cards (formats grid, proof rows, supply-chain diagram, HQ expansion, certification badges) → client marquee → What's New 3x3 → big CTA band → certifications row → deep footer.

**Placeholders to note before showing a client:** marquee "CLIENT ONE…EIGHT" tiles are generic stand-ins (no real client logos yet); quotes are attributed to PP's own teams (no invented client testimonials); phone number `(817) 555-0100` is a placeholder; the "Industry Guide" report is a stand-in concept. View at `http://127.0.0.1:8080/v2.html` when the local server is running.

## V1 — carestack-inspired (`index.html`)

A standalone homepage design exploration for **Platinum Press**, cloning the layout and feel of **carestack.com** (enterprise / premium / clean), reskinned with Platinum Press's own palette and imagery.

## What this is
- **Faithful to carestack:** rounded-20 cards, pill buttons, airy sections, single strong accent, tabbed section, scroll reveals, hover-lift.
- **PP palette:** royal blue `#064FBC` (replaces carestack's green), navy `#0A1A33` dark bands, neutral white/grey system.
- **Typography stolen from carestack** (free equivalents): Archivo (display) + Inter (body) + Roboto Condensed (eyebrows / stats). Loaded from Google Fonts.
- **PP imagery:** the 12 real client photos in `images/` (copied from `projects/platinum-press/assets/client-images/`).
- **Copy:** original Platinum Press stand-in copy, no em dashes, Contact Sales as the primary CTA.

## Sections
Sticky nav → hero (press photo + spec strip) → certifications strip → Markets (6 numbered cards) → Capabilities (tabbed) → scale-stats band → Products grid → Innovations (combination carton) → single-source / privately-held story → Contact Sales band + footer.

## View it
Open `index.html` in a browser, or serve locally:
```
cd vibe-coding/mockups/platinum-press-carestack
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy (optional)
Static, no build. Drag the folder to Vercel/Netlify, or `vercel deploy` from here.

## Notes
- Logo is a text lockup placeholder (client logo files not yet delivered; logo is off-limits to redraw).
- Fully responsive (desktop → mobile). Capturable into Figma via the HTML capture recipe for the design deliverable.
