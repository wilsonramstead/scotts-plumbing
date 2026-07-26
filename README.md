# Scott's Plumbing — demo site

Single-page demo for **Scott's Plumbing**, a residential plumber in Seminole, FL.
Built demo-first (no contract, no contact yet) for a text-first pitch.

- **Business:** Scott's Plumbing — plumber
- **Address:** 8843 117th St N, Seminole, FL 33772
- **Phone:** (727) 399-0194 → `tel:+17273990194` / `sms:+17273990194`
- **Rating:** 4.8★ from 61 Google reviews
- **Current web presence:** none (no website listed)
- **Live demo URL (target):** https://wilsonramstead.github.io/scotts-plumbing/

## Pitch angle
The husband-and-wife-feel local plumber: **Scott** does the work, **Brittany** runs
scheduling with same / next-morning responsiveness (the Sunday-night voicemail → Monday
9 AM install from Eddie Oakie's review). Jobs are **priced as quoted**, and Scott
**improves the setup** rather than just swapping parts. Team framing throughout — both
named once each in the body copy, no owner-shrine section.

## Services shown
Water heaters · garbage disposals · shower valves & fixtures · drain clearing ·
leaks & faucet repair · general residential plumbing. (No invented specialties,
licenses, hours, 24/7 claims, emails, or founding year.)

## Reviews used (real names, all 5★)
- **Eddie Oakie** — Sunday-night disposal breakdown; Brittany called Monday morning; Scott arrived 9 AM on time.
- **Michelle Anderson** — disposal + water heater; priced as quoted; very reasonable.
- **Cari McKenzie** — water heater rescue; Scott improved the setup; quick to respond.

## Design
- **Fonts:** "Yeseva One" (display) + "Heebo" (body), Google Fonts.
- **Palette:** brick-clay `#B84A2E` + steel-slate `#33505C` + warm cream `#F7F2EA`,
  with a brass-gold accent `#C1863A` for stars. Chosen to be unique against every other
  site in `websites/` (the plumbing set clusters around teal/copper/brass/yellow/plum).
- Single self-contained `index.html`, inline CSS + minimal JS, works from `file://` and
  with JS disabled. `noindex` until the client goes live.

## Images (Unsplash, all globally unique across `websites/`)
- Hero: `photo-1611776575292-bec10cc1a906` (warm kitchen faucet/sink)
- Work: `photo-1646592491489-ebdf758b9d11` (chrome kitchen faucet + sink)
- Work: `photo-1627008952471-a0339ea450c7` (chrome shower valve on tile)
- Work: `photo-1637665609537-26857a32f6cd` (black faucet, undermount marble sink)

Work-gallery photos are labeled as representative placeholders — swap in real photos of
Scott's work after the sale.

## Domain note
- `scottsplumbingfl.com` — **TAKEN**.
- `scottsplumbingseminole.com` — **AVAILABLE** (~$11/yr). Recommended if the client wants
  their own domain; otherwise the site lives at the GitHub Pages URL above.

## Deploy (when the client says yes)
Not deployed yet. When ready: `git init` in this folder →
`gh repo create wilsonramstead/scotts-plumbing --public --source . --push` →
enable Pages (master branch, `/` path). Then remove the `noindex` meta, swap in real
photos, and point the domain.

---
Website by [Wilson Innovations](https://wilsoninnovations.net).
