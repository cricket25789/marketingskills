# Nutral — Landing page mockups

Two self-contained landing-page variants for Nutral, both in a premium / natural / editorial direction with rich motion.

Open either `index.html` directly in a browser — no build step, no dependencies (Google Fonts loaded from CDN).

## Brand brief

> Nutral enhances the effectiveness of temporary workforce procurement by optimising relationships with recruitment agencies and payroll intermediaries — delivering visibility, control, and value.

Audience: procurement, HR and finance leaders in mid-market and enterprise UK organisations.

## Variant 1 — `variant-1/index.html`

Editorial Aesop-style. Bone / moss / terracotta palette, Fraunces serif headlines, asymmetric two-column hero with floating organic blob illustration and a rotating SVG mark.

Animations:
- Blurred blob "lava lamp" hero composition (CSS keyframes)
- Rotating SVG type on a circular path
- Marquee of industry verticals (CSS animation, pauses on hover)
- Scroll-pinned parallax on hero visual and process backdrop
- Count-up stats on viewport entry
- Reveal-on-scroll for all major blocks
- Pillar hover state with background fill
- Animated arrow on every CTA

## Variant 2 — `variant-2/index.html`

Calm Earth / Daily Harvest-style. Paper / sage / clay palette, Cormorant Garamond italic headlines, centred hero with an animated supply-chain network diagram showing agencies → Nutral → client outputs.

Animations:
- Hero headline animates in word-by-word
- Animated SVG network diagram with dashed connection flow
- Pulsing node markers
- Horizontal scroll-snap "principles" strip on dark green
- Vertical timeline with line-draw animation and per-row marker state change
- Editorial figure with parallax
- Count-up stats, reveal-on-scroll, hover lift on testimonial cards
- Concentric-circle animated CTA backdrop

## Differences at a glance

| | Variant 1 | Variant 2 |
|---|---|---|
| Headline serif | Fraunces (variable) | Cormorant Garamond |
| Hero layout | Asymmetric 2-col | Centred, full-width |
| Hero visual | Organic blobs + circular type | Network diagram |
| Process viz | 2×2 grid | Animated line-draw timeline |
| Principles | Static 3-col pillars | Horizontal scroll cards on dark |
| Testimonial | One large pull-quote | 3-up grid |
| Footer | 4-col on dark ink | Light, with hero tagline restated |

Both files respect `prefers-reduced-motion`.

## To iterate

Tell me which variant you want to push further (or merge the two), plus anything to tighten:

- Headline copy
- Palette adjustments (e.g. less terracotta, more sage)
- A specific section to expand (case study, pricing, FAQ, team)
- Real imagery (will need URLs / files — currently using SVG illustration)
