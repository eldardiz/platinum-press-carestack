# Platinum Press — CareStack-style Homepage

## V2 — structural 1/1 clone (`v2.html`) ← CURRENT
`v2.html` is a section-for-section structural clone of carestack.com's live homepage (captured 2026-07-06), re-branded to Platinum Press. Same section order, layouts, grids and proportions; all copy is original PP content, all photos are PP's own, PP palette (navy `#0A1A33` bands, blue `#064FBC` CTAs, ice-blue `#BFD9FF` accents on dark) and Geist + Inter type.

Sections (matching the reference order): announcement topbar → dark nav → split hero with Watch Overview media → Markets accordion + photo card → single-source economics stats band → dark industry-guide band → Our Work story carousel + mini CTA card → Capabilities (sticky rail + 5 image/link-list cards with scroll-spy) → Innovations gradient band (Combination Carton + 2x2 tiles) → Why Platinum Press stacked cards (formats grid, proof rows, supply-chain diagram, HQ expansion, certification badges) → client marquee → What's New 3x3 → big CTA band → certifications row → deep footer.

**Placeholders to note before showing a client:** marquee "CLIENT ONE…EIGHT" tiles are generic stand-ins (no real client logos yet); quotes are attributed to PP's own teams (no invented client testimonials); phone number `(817) 555-0100` is a placeholder; the "Industry Guide" report is a stand-in concept. View at `http://127.0.0.1:8080/v2.html` when the local server is running.

## Subpage templates (added 2026-07-07)
Three template exemplars cloned from CareStack's subpage structures, matching the 3-core-template client deliverable. Same design system as v2, all-original PP copy, fully interlinked with v2.html:
- **`pharma.html`** — Market template (Pharma / Prescription): breadcrumb hero + video-quote card, why-accordion, dark stat banner, products rail with link-list cards, split deep-dive, services tabs, stakeholder section, ice CTA card, FAQ with sticky topics.
- **`labels.html`** — Product/Capability detail template (Labels): prev/next sibling sub-nav, sticky intro with link-rich paragraphs, 3 alternating image + checklist blocks, dark mini-CTA, dark quote band with video slot.
- **`about.html`** — Content/Company template (About / Our Story): dark hero + facility photo, ice stats band ($15M / 2 / 100+ / 2-Day), two-column story, 2x2 link cards, big CTA, FAQ.

These three templates power the full sitemap: Market template → all 6 market pages; detail template → all products + capability children; content template → About, Quality, News, Careers.

## Second wave (added 2026-07-08)
Four more template exemplars, same rules (CareStack structure, all-original PP copy, PP imagery, shared design system), fully interlinked with all prior pages:
- **`quality.html`** — Quality & Compliance template (from carestack.com/why-carestack): dark hero, centered statement, 6-card proof carousel, 3-pillar sticky rail (Certifications / 100% In-Line Inspection / Sustainability), 6-item compliance-stack accordion, trust band, big CTA. Anchor `#pillars` is the target for cross-links.
- **`contact.html`** — Contact Sales template (from carestack.com/demo): centered H1 + info strip, scheduler-style booking card (navy info panel + request form with thank-you state), "What Happens Next" steps. This is the site-wide Contact Sales destination.
- **`insights.html`** — Insights & Resources hub (from carestack.com/support/resources): dark "Platinum Insights" sub-brand with its own nav, Latest list + featured card, 3 gradient download cards, quote band, article + case-study grid, newsletter signup, compact footer.
- **`innovations.html`** — Innovations spotlight (from carestack.com ai-suite page): all-dark orbit hero, sticky 5-tab strip with scroll-spy (Combination Carton / EasyCode / CodeShield / Flatsert / Source Tags), one deep-dive block per innovation with caption tiles, big CTA.

**Additional placeholders in these pages:** trust-band logo tiles are generic; quotes remain PP-team attributed (Quality Systems, Serialization Team, Press Operations); article dates/read-times on insights.html are stand-ins; the contact form does not submit anywhere (front-end thank-you state only).

## Third wave (added 2026-07-08) — mapping complete
The last three unbuilt rows of the CareStack template mapping. Every template family now has a PP exemplar:
- **`products.html`** — Products &amp; Capabilities hub (from carestack.com/dental-software/features): breadcrumb hero with photo collage + floating stat chips, sticky icon rail with scroll-spy, six stacked family cards (light image header + dark 2-col variant link list, Patented/New badges), dark "Beyond the Formats" services band, capability tile grid, FAQ accordion, big CTA. This hub layout also powers the future Capabilities hub. Nav "Products" now lands here site-wide.
- **`work.html`** — Our Work / Case Studies index (from carestack.com/dental-software/case-studies), under the Platinum Insights sub-brand: dark hero with three overlapping tinted stat cards, two-column case list (8 program stories), masonry quote wall, compact footer. Nav "Our Work" button now lands here site-wide.
- **`case-study.html`** — Case Study detail (from a CareStack customer-story page): split hero (dark text left, full-bleed image right), long-form body with sticky Contents TOC (scroll-spy), author chip and share rail, pull-quote bands, figure with caption, certification badge strip, navy outcome stat tiles, PDF download form (front-end only), related tag chips.

**Placeholders in these pages:** case studies are anonymized program stories ("national Rx brand" style descriptors, no invented client names or logos); hero stat cards on work.html carry generic CLIENT ONE/TWO/THREE marks; all case-list entries currently link to the single case-study.html exemplar; dates/read-times are stand-ins; the download form does not submit anywhere.

## Fourth wave (added 2026-07-15)
- **`article.html`** — Blog article detail (from a CareStack resources article): split hero, sticky Contents TOC with scroll-spy, definition table, navy numbered checklist box, pull quote, Key Takeaways block (AEO), tag chips, Keep Reading row. Exemplar article: "DSCSA Aggregation Is Not Optional Anymore." This template powers the whole Blog branch.
- **`news.html`** — News & Press index (from carestack.com/company/events layout): breadcrumb, cream two-column intro band, chip/title/date card grid, navy press-kit band. Populated with PP's REAL public press history: $15M expansion, K&B Rapida presses, VOC-free digital platform (titles verbatim from platinumpress.com/press-releases), plus the 2016 serialization-ready release and the 2015 Walgreens certified-supplier announcement (both link to their real third-party coverage). NOTE: only 2015/2016 dates are verified; other years are stand-ins pending client confirmation. "Platinum Insights Launches" is a stand-in item.
- **`capabilities.html`** — Capabilities hub (reuses the products.html hub layout per the template model): hero collage, sticky 5-item rail (Printing / Finishing / Serialization & DSCSA / Warehousing & Fulfillment / Value-Added Services) with dark link-list cards, cross-links band (Products / Markets / Quality per the sitemap hub card), FAQ, big CTA. Nav "Capabilities" now lands here site-wide; footer capability links point to its anchors.

## Fifth wave (added 2026-07-18)
Template-reuse round proving the extend-the-templates model:
- **`markets.html`** — Markets hub (hub layout): six market cards with relevant product/capability link lists, cross-links band, FAQ. Nav "Markets" now lands here site-wide.
- **`medical-device.html`** — Medical Device market page (market template variant): UDI-ready labeling, instructions for use, device cartons, tamper evidence. FDA UDI labeling framed as printer-scope claims only.
- **`cartons.html`** — Folding Cartons product page (product detail template variant): constructions, the patented Combination Carton block, finishing and tamper evidence. Subnav: Labels ← → Literature.
Also: article/news/capabilities captured into Figma (pages: Capabilities, News & Press, Blog Article, matching the file's new no-emoji Drafts convention).

## Sixth wave (added 2026-07-18) — full sitemap coverage
All 27 remaining sitemap nodes built as template variants (validated against CareStack sibling pages before the run):
- **Products ×4**: literature, lidding, flexible, security (product detail template; full prev/next sibling chain across all 6 products)
- **Markets ×4**: otc, wellness, animal-health, personal-care (market template; claims kept category-appropriate and printer-scoped)
- **Capabilities ×12**: printing, finishing, serialization, warehousing, value-added (parents) + offset, flexo, digital, cold-foil, embossing, ablation, coating (children), all chained via sibling subnavs
- **Innovations ×5**: combination-carton, easycode, codeshield, flatsert, source-tags (detail template + expanded spotlight content; the innovations.html spotlight now links each block to its full page). No one-page CareStack source exists for these; documented deviation.
- **careers.html** — the ONE page composed from our own system (CareStack no longer has a careers page): job cards are representative stand-in roles, no invented people.
- **downloads.html** — Platinum Insights library page; download links route to Contact (request-based) pending real files.
Every sitemap node (44/44) now has a draft; every footer/nav link resolves to a real page (no v2.html#anchor stand-ins remain).

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
