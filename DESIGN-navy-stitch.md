---
version: alpha
name: paya-design-analysis
description: >
  Pearl of Africa Youth Alliance (PAYA) — a proud, luminous identity born from
  Uganda's night sky. Deep navy cosmos arenas lit by constellation and circuit
  lines, crowned by regal gold lettering and the holographic grey crowned
  crane. Crimson red carries Uganda's flag and the alliance's fight for youth
  dignity. The overall atmosphere is Africa at night connected by light:
  hopeful, optimistic, tech-forward yet culturally rooted.
colors:
  canvas: "#0A1A2F"
  canvas-deep: "#071321"
  surface: "#102B4A"
  primary: "#D9A441"
  primary-light: "#F3CE7A"
  on-primary: "#0A1A2F"
  ink: "#F8F6F0"
  ink-dim: "#A8B8C8"
  accent: "#A11F3E"
  accent-light: "#D6385C"
  signal: "#3DC6F5"
  signal-soft: "#7FD9FA"
  holo-pearl: "#E8F4EC"
typography:
  display-xl: {fontFamily: Playfair Display, fontSize: 72px, fontWeight: 800, lineHeight: 1.05, letterSpacing: -0.02em}
  display-lg: {fontFamily: Playfair Display, fontSize: 52px, fontWeight: 800, lineHeight: 1.1, letterSpacing: -0.01em}
  display-md: {fontFamily: Playfair Display, fontSize: 36px, fontWeight: 700, lineHeight: 1.15}
  headline-xs: {fontFamily: Manrope, fontSize: 13px, fontWeight: 700, letterSpacing: 0.22em, textTransform: uppercase}
  body-lg: {fontFamily: Manrope, fontSize: 19px, fontWeight: 400, lineHeight: 1.6}
  body-md: {fontFamily: Manrope, fontSize: 16px, fontWeight: 400, lineHeight: 1.65}
  body-bold: {fontFamily: Manrope, fontSize: 16px, fontWeight: 700, lineHeight: 1.4}
  eyebrow: {fontFamily: Manrope, fontSize: 12px, fontWeight: 700, letterSpacing: 0.28em, textTransform: uppercase}
components:
  button-primary: {backgroundColor: "{colors.primary}", textColor: "{colors.on-primary}", rounded: "{rounded.md}", fontWeight: 800, hover: "background {colors.primary-light}"}
  button-secondary: {backgroundColor: "transparent", borderColor: "{colors.primary}", textColor: "{colors.primary-light}", rounded: "{rounded.md}", hover: "background {colors.surface}"}
  button-crimson: {backgroundColor: "{colors.accent}", textColor: "{colors.ink}", rounded: "{rounded.md}", hover: "background {colors.accent-light}"}
  product-card: {backgroundColor: "{colors.surface}", rounded: "{rounded.lg}", border: "1px solid rgba(217,164,65,0.25)", hover: "border {colors.primary}"}
  stat: {number: "{colors.primary-light}", numberFont: display-lg-multi}
spacing: {section: 96px, stack: 24px, grid: 32px, tight: 12px}
rounded: {none: 0px, sm: 6px, md: 10px, lg: 18px, pill: 999px}
---
## Overview
PAYA's visual identity glows like Uganda at night seen from orbit. Backgrounds
are deep navy cosmos (#0A1A2F) layered with thin cyan (#3DC6F5) constellation
and circuit lines, orbited by a warm gold (#D9A441) horizon arc — a nod to the
rising sun of a united Africa. The grey crowned crane sits at the heart of
storytelling, usually with a holographic pearl above it. Headings use regal
serif gold; body text is a calm, high-readability sans-serif in pearl white.
Crimson (#A11F3E) is the voice of urgency and pride: donate buttons, campaign
tags, "Join" moments. Never let crimson outnumber gold; gold leads, cradles,
crowns.

## Do's and Don'ts
- DO keep large sections navy-dark; merchandise cards may lift to lighter
  surfaces for product photography clarity.
- DO use gold only on: headings, primary buttons, key lines/arcs, product
  crown marks.
- DO use cyan strictly as thin connecting detail (lines, dots, network maps,
  focus rings).
- DON'T place the full-color crest over busy photography without a navy
  scrim at 60%+.
- DON'T glow text other than the pearl/crane emblem hero; glow is earned.
- DON'T mix more than two fonts. Playfair Display for display, Manrope for
  everything else.
- DON'T use pure black (#000) or pure white (#FFF) backgrounds.

## Responsive Behavior
Desktop is authoritative. At tablet, the programs grid drops from 3 to 2
columns; merch grid from 4 to 2. At mobile, nav collapses into a menu sheet
with the crest alone as wordmark; the hero stacks crest above headline;
section padding reduces to 48px; touch targets minimum 48px; the horizon arc
hides below 768px. Product cards keep the crest centered and legible at every
size.
