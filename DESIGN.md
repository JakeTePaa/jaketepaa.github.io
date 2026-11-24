---
name: Jakes Space, marketing agency
description: Dark, sharp agency look built from the Jakes Space brand sheet. Obsidian base, Electric Indigo accent, the JS mark as the hero.
colors:
  obsidian-black: "#0B0D12"
  off-white: "#F5F5F0"
  electric-indigo: "#5046E5"
  titanium-grey: "#A0A4B0"
  panel: "#12151C"
typography:
  family: "Plus Jakarta Sans, system-ui, sans-serif"
  display: "700, clamp(2.7rem, 5.4vw, 5rem), line-height 1.02, letter-spacing -0.045em"
  headline: "700, clamp(2.1rem, 4.4vw, 3.6rem), line-height 1.04, letter-spacing -0.035em"
  eyebrow: "600, 0.8rem, uppercase, letter-spacing 0.32em, Titanium Grey"
---

# Design System: Jakes Space

## Overview
The site follows the Jakes Space brand sheet: an Obsidian Black page, Off White type,
Electric Indigo for the one thing that matters in each view, and Titanium Grey for
supporting text. The wide-tracked uppercase labels echo "MARKETING AGENCY" under the logo.

## Colours
- **Obsidian Black `#0B0D12`**: page background.
- **Off White `#F5F5F0`**: body text on dark; background of the Work section (the light logo panel).
- **Electric Indigo `#5046E5`**: buttons, the featured service card, highlighted words, the contact panel.
- **Titanium Grey `#A0A4B0`**: secondary text, eyebrows, hairlines (at 18% opacity).
- **Panel `#12151C`**: cards one step above the background.

Rule: one indigo moment per screen. Never put indigo text on indigo.

## Logo files (`images/`)
Cut from the brand sheet with the dark background removed (transparent PNGs).
- `logo-mark.png`: the JS mark (white J, indigo S). Use on dark or indigo; on indigo, invert to white with `filter: brightness(0) invert(1)`.
- `logo-lockup.png`: mark + "Jakes Space / Marketing Agency". Dark backgrounds only.
- `icon.png`: the rounded app-icon tile. Favicon, Apple touch icon, social image.

For crisper logos at large sizes, swap these for the original high-res or SVG logo files using the same names.

## Layout
- Header: mark, a thin rule, then "Jakes Space" with "Marketing agency" in tracked caps.
- Hero: headline left, the app-icon tile right with a soft indigo glow.
- Services: three cards, the first in indigo.
- Work: Off White section with white project cards; each picture window shows the mark until a real image replaces it.
- Process: three columns with outlined step numbers and a short indigo rule.
- Contact: a rounded indigo panel with a faint white mark in the corner.

## Shapes
Rounded but not pill-shaped: 12px buttons, 8px chips, 20px cards, 28px panels, 22% on the icon tile.

## Do / Don't
- Do keep sections dark, with the one Off White Work section for contrast.
- Do use the real logo files, never retyped text in place of the mark.
- Don't add new colours outside the four brand colours and the panel tone.
