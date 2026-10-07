# ARCLINE STUDIO — Animation System

## Motion Philosophy
Reveal → Move → Pause → Respond.

Motion should feel architectural, precise, physical and quiet.

## Levels
### Level 1 — Ambient
Opacity, image reveal, text movement, subtle scale and line transitions.

### Level 2 — Interactive
Project hover, services, navigation, material switching and principle switching.

### Level 3 — Signature
Only 2–3 major moments:
1. The Arrival
2. Spatial Reveal
3. Four Principles

## Hero — The Arrival
Image reveal → metadata → headline → CTA.
Approximate total sequence: 1–1.5 seconds.
Never block interaction while animation plays.

## Spatial Reveal
Images enter through masks. Text reveals as groups of lines rather than letter-by-letter typing.

## Scroll Reveal
Typical trigger around 10–20% visibility.
Typical movement 16–32px.
Typical duration 600–900ms.

## Project Hover
Image scale approximately 1.015–1.03. Metadata and arrow shift subtly.

## Material Interaction
Crossfade/masked transition between material images and descriptions, approximately 700ms.

## Principles
FORM / MATERIAL / LIGHT / LIFE. Switching changes image and text with subtle fade/scale transitions.

## Services
Desktop hover can update a related visual. Mobile uses tap/expand behavior instead.

## Navigation
Hero overlay can transition to solid navigation after scrolling, approximately 300–500ms.

## Mobile
Reduce motion. Remove cursor effects and hover-dependent interactions. Keep subtle reveals and transitions.

## Cursor
Default browser cursor is preferred. Optional small contextual desktop cursor only; never a giant custom cursor and never on mobile.

## Audio
None.

## Performance
Prefer transform, opacity and clip-path where practical. Avoid expensive layout animation and unnecessary animation libraries.

## Reduced Motion
Respect prefers-reduced-motion. Remove parallax and large movement; keep content immediately accessible.
