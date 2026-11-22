---
name: Jake, AI and social media marketing
description: A layered papercut savanna, every section a sheet of flat coloured paper cut and pasted over the last.
colors:
  ochre: "#e3a335"
  sky: "#f6dfa9"
  paper: "#f5e9d0"
  paper-muted: "#d9ceb4"
  olive: "#7d9440"
  green: "#2e4a2b"
  green-deep: "#1f331d"
  red: "#b53a25"
  ink: "#1d1a14"
  ink-soft: "#3d3628"
typography:
  display:
    fontFamily: "Besley, Georgia, serif"
    fontSize: "clamp(2.6rem, 5vw, 4.6rem)"
    fontWeight: 400
    lineHeight: 1.03
    letterSpacing: "-0.026em"
  display-close:
    fontFamily: "Besley, Georgia, serif"
    fontSize: "clamp(2.8rem, 7vw, 6rem)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "-0.026em"
  headline:
    fontFamily: "Besley, Georgia, serif"
    fontSize: "clamp(2.1rem, 4.2vw, 3.6rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Besley, Georgia, serif"
    fontSize: "clamp(1.5rem, 2.4vw, 2rem)"
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  lead:
    fontFamily: "Albert Sans, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Albert Sans, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Albert Sans, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 500
    lineHeight: 1.6
  status:
    fontFamily: "Albert Sans, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 600
    lineHeight: 1.6
rounded:
  focus: "4px"
  plate: "3px"
  sheet: "18px"
  portrait-foot: "20px"
  pill: "999px"
spacing:
  gutter: "clamp(20px, 4vw, 48px)"
  wrap: "1200px"
  sheet-y: "clamp(72px, 10vw, 128px)"
  section-head: "56px"
  strip-overlap: "-18px"
  plate-gap: "40px 32px"
  plate-under-inset: "-7px"
  chip-gap: "8px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "52px"
  button-primary-hover:
    backgroundColor: "{colors.green-deep}"
    textColor: "{colors.paper}"
  button-primary-compact:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0 20px"
    height: "44px"
  button-on-red:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "52px"
  button-on-red-hover:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.ink}"
  strip-ochre:
    backgroundColor: "{colors.ochre}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sheet}"
    padding: "44px clamp(24px, 4vw, 56px) 52px"
  strip-green:
    backgroundColor: "{colors.green}"
    textColor: "{colors.paper}"
    rounded: "{rounded.sheet}"
    padding: "44px clamp(24px, 4vw, 56px) 52px"
  strip-red:
    backgroundColor: "{colors.red}"
    textColor: "{colors.paper}"
    rounded: "{rounded.sheet}"
    padding: "44px clamp(24px, 4vw, 56px) 52px"
  chip-outline:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
  tag-sky:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "3px 10px"
  tag-status:
    backgroundColor: "{colors.red}"
    textColor: "{colors.paper}"
    typography: "{typography.status}"
    rounded: "{rounded.pill}"
    padding: "3px 10px"
  plate:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.plate}"
    padding: "26px 28px 30px"
  plate-under:
    backgroundColor: "{colors.olive}"
    rounded: "{rounded.plate}"
  plate-window:
    backgroundColor: "{colors.sky}"
  portrait:
    backgroundColor: "{colors.green}"
    textColor: "{colors.sky}"
---

# Design System: Jake, AI and social media marketing

## Overview

**Creative North Star: "The Layered Savanna Papercut"**

The page is a stack of flat, unmixed coloured papers. Each section after the hero is a new sheet pasted over the one before, its top edge cut into a silhouette (rolling hills or a grass fringe) with a sliver of a third paper showing beneath the cut. Nothing is shaded, blurred or graded; every sense of depth comes from one opaque shape overlapping another. The palette is a savanna at midday: an ochre field, sky-coloured paper, acacia greens, olive grass and a single vermilion sun.

The signature object is the roundel: a circular papercut scene (ring, sky disc, sun, ridge, twin acacias, grass, birds, cut line) assembled from SVG symbols that each represent one sheet. The scene is cut from a fold, so the acacias and the pair of birds are mirror twins and the ridge and grass are symmetric about the centre. The same layers recur at every scale, from the 34px brand mark to the 520px hero roundel to the plate windows, and the roundel is the only illustration the system uses.

Density is generous and calm. Big Besley headlines with tight negative tracking sit against plain Albert Sans reading text; sections breathe at 72 to 128px vertical padding. Motion is papery: layers drop in from slightly above with a small counter-clockwise tilt, then sit still.

**Key Characteristics:**
- Flat opaque papers only; depth by overlap, never by shadow, gradient or blur.
- Cut silhouette edges between sections, with a contrasting paper visible under each cut.
- One illustration system: the folded-symmetric roundel, built from reusable layer symbols.
- Besley display in regular weight, tight tracking; Albert Sans for everything readable.
- Pill-shaped controls and chips; 18px rounded sheets.
- Motion only where a paper layer lands: hero settle on load, layer-by-layer rebuild in the process section.

## Colors

A small set of saturated earth papers and two warm inks, each used flat and at full strength.

### Primary
- **Ochre Field** (`ochre`): the page ground. The header and hero sit directly on it edge to edge, the process sheet returns to it, the first service strip is cut from it, and it shows as the under-sliver beneath the work and close sheets. Also the browser theme colour.

### Secondary
- **Acacia Green** (`green`): the second major paper. The work sheet, the middle service strip, the portrait backing, the roundel ring and grass, focus selection background and scrollbar thumb.
- **Night Acacia** (`green-deep`): the darkest paper. Footer sheet, acacia silhouettes in the roundel, and the primary button's hover.

### Tertiary
- **Vermilion Sun** (`red`): the sun disc, the close sheet, the third service strip, the under-sliver beneath the process sheet, the fill of the "Coming soon" tag on work plates, and the text caret. Reserved for the sun and the final call to action; it never becomes a general accent for links or icons.
- **Olive Grass** (`olive`): the roundel ridge, the under-sliver beneath the services and footer sheets, and the offset under-sheet pasted beneath every work plate. A supporting paper, never a full section ground.

### Neutral
- **Reading Paper** (`paper`): the reading sheets (services, about), work plates, and light text on green, red and deep-green papers.
- **Sky Paper** (`sky`): the roundel sky disc, plate windows (photo slots), tag chips, the portrait initial, and the hover state of the paper button on red.
- **Faded Paper** (`paper-muted`): secondary text on green papers (work section intro, footer text). A `:root` token like the rest; on green it sits at about 6.3:1.
- **Lamp Black Ink** (`ink`): body text, headlines, the primary button fill, step rules and focus outlines.
- **Worn Ink** (`ink-soft`): supporting text on ochre and paper (lead, section intros, plate descriptions, about body). On ochre it sits at about 5.4:1 and on paper about 9.9:1; it must not get lighter.

### Named Rules
**The Unmixed Paper Rule.** Every colour is used flat at full opacity. No gradients, tints, transparency washes or blend modes between papers; a new shade is a new sheet of paper, added to the token set, not a mix.

**The One Sun Rule.** Vermilion is the sun. It appears as the sun disc, the closing sheet, one service strip and the "Coming soon" tag, and nowhere else as decoration.

**The Under-Sliver Rule.** Each cut sheet shows a sliver of a third paper beneath its edge, chosen to differ from both the sheet and the paper it is pasted over (services: paper over ochre with olive under; work: green with ochre under; process: ochre with red under; about: paper with green under; close: red with ochre under; footer: deep green with olive under). Work plates carry the same idea at small scale: an olive under-sheet shows around each paper plate.

## Typography

**Display Font:** Besley (with Georgia, serif)
**Body Font:** Albert Sans (with system-ui, sans-serif)

**Character:** Besley's soft, slightly bookish serif at regular weight carries the warmth of printed paper ephemera; Albert Sans keeps reading text plain and modern so the papers, not the type, do the decorating. Both load from Google Fonts with weights 400 to 600.

### Hierarchy
- **Display** (400, `clamp(2.6rem, 5vw, 4.6rem)`, 1.03, -0.026em): the hero h1 only, capped at 16ch.
- **Display Close** (400, `clamp(2.8rem, 7vw, 6rem)`, 1, -0.026em): the contact sheet headline, capped at 12ch. The largest type on the page, used once.
- **Headline** (400, `clamp(2.1rem, 4.2vw, 3.6rem)`, 1.05, -0.02em): section h2s.
- **Title** (400, `clamp(1.5rem, 2.4vw, 2rem)`, 1.1, -0.02em): strip, plate and step h3s. The wide lead plate bumps to `clamp(1.9rem, 3vw, 2.6rem)`.
- **Lead** (400, 1.25rem): the hero support line (34ch) and close paragraph (1.2rem, 40ch); the about opener is 1.3rem in full ink.
- **Body** (400, 1.0625rem, 1.6): all reading text, held to 40 to 52ch; about body runs at 1.125rem.
- **Label** (500, 0.875rem): service chips and button text (buttons at 1rem/1, weight 500).
- **Status** (600, 0.8125rem): the "Coming soon" tag, paper on vermilion, first in a plate's tag row after the description.

**The No Kicker Rule.** Nothing sits above a heading: no eyebrows, overlines or status labels. State that belongs to an item goes in its tag row, below the copy.

### Named Rules
**The Regular Weight Rule.** Headlines are Besley 400 with negative tracking (-0.02em, -0.026em at display sizes) and `text-wrap: balance`. Size and tracking carry hierarchy; bold display weights are not used.

**The Plain Reading Rule.** All body copy is Albert Sans, sentence case, with `text-wrap: pretty` and a measure under about 52ch. No uppercase labels, no letter-spaced small caps.

## Layout

A single 1200px wrap (`wrap`) centred with a fluid side gutter (`gutter`, 20 to 48px). Sections are full-bleed sheets; content inside them sits in the wrap.

- **Header:** 84px row; brand mark left, section links centre, compact Email Jake button right.
- **Hero:** fills the first viewport (`100svh - 84px`), two columns at 1.15fr / 1fr: copy left, roundel right (max 520px, aligned to the end).
- **Section head:** two equal columns, headline left and a short intro right, aligned to the baseline end, 56px above the content.
- **Services:** a vertical stack of three strips, each a 1fr / 1.25fr grid (title left; description and chips right), each overlapping the previous by 18px.
- **Work:** a two-column grid of plates with 40px row and 32px column gaps (room for the offset under-sheets), in its own stacking context; the first plate spans both columns and lays out horizontally (window right of body). Plates are added by copying the block; the first is always the strongest project.
- **Process:** two columns; steps on the left (each at least 52vh tall, separated by a 2px ink rule), a sticky stage on the right (top 12vh, 76vh tall) holding the build roundel.
- **About:** 0.8fr / 1.2fr; arched portrait left, text right.
- **Vertical rhythm:** sheets pad `clamp(72px, 10vw, 128px)` top and bottom; the footer uses 56px / 40px.

**Responsive (900px and below):** nav links hide (the header keeps brand and Email Jake); every two-column grid collapses to one; the hero roundel centres at 300px max; the lead plate returns to a vertical 16:10 window; the process stage becomes static, 340px max, ordered above the steps, with every step heading at full opacity and the trees, sun and birds forced visible; the portrait caps at 340px.
**480px and below:** hero action buttons go full width and centred; the header Email Jake button hides, since the hero carries a full-width one.

## Elevation & Depth

This system has no shadows. Depth is built only from opaque layers overlapping: a sheet over the previous sheet, a strip over the strip before it, a paper plate on an olive under-sheet on a green sheet, and, inside the roundel, each symbol drawn over the last. The cut edge between sections is two pseudo-element bands masked by the same silhouette: the sheet's own colour at 39px above its top, and an under-paper band 8px higher behind it, so a thin sliver of a third colour shows along the cut.

### Named Rules
**The Paste, Don't Lift Rule.** Nothing floats. No `box-shadow`, `filter: drop-shadow`, blur or glow. If an element needs to read as above another, it overlaps it with an opaque shape.

**The Cut Edge Rule.** A new section enters with a cut top edge from the silhouette set (`hills`: a soft rolling ridge stretched full width; `grass`: a jagged fringe tiled at 120px) and alternates between them down the page. The hero has no cut edge; it is the base paper.

## Shapes

Shapes are cut, not drawn. Silhouettes are flat filled paths with no outlines, symmetric about a vertical fold wherever they represent the landscape (twin acacias and the two birds are each one path mirrored; ridge and grass are mirror-symmetric). Sheets and strips use generous 18px corners (`sheet`); work plates are nearly square-cut at 3px (`plate`), like a trimmed paper card; controls, chips and tags are full pills (`pill`). The service stack rounds only its top corners until the final strip, which rounds all four, so the three read as one stack of torn-off sheets. The portrait is an arch: fully round top, 20px feet. The roundel ring is a solid disc edged with a row of round dots (a dashed round-cap stroke), reading as a scalloped cut. Outline is used in exactly two places: the outlined service chips and the 4px paper-coloured cut line inside the roundel.

## Components

### Buttons
Solid, quiet and tactile; one filled style and one text link.
- **Shape:** full pill (`pill`), 52px tall (44px compact in the header).
- **Primary:** ink fill, paper text, Albert Sans 500 at 1rem, 26px side padding.
- **Hover / Active:** lifts 2px and darkens to deep green over 0.25s on the page ease; presses down 1px on click.
- **On red (close sheet):** inverts to paper fill and ink text; hover turns sky.
- **Text link:** underlined 500-weight link at the same 52px hit height; hover thickens the underline to 2px. It is the secondary action beside every primary button.
- **Focus:** 3px solid ink outline, 3px offset, 4px radius; switches to paper on red and deep-green sheets.

### Chips
- **Service chips:** pill, transparent with a 1.5px current-colour outline, 0.875rem/500, 6px 14px, never wrapping. They take the strip's text colour, so they read ink on ochre and paper on green and red.
- **Tags:** pill, sky fill, no border, 0.8125rem, 3px 10px. Used on work plates only.
- **Coming soon tag:** the same pill in vermilion with paper text at weight 600, always first in the tag row. Removed once the case study is live.

### Service Strips
The signature list pattern: three full-width paper strips (ochre, green, red), each pasted 18px over the one before, top corners rounded at 18px, the last rounded all round. Title left, description and chips right.

### Plates (work cards)
Each plate is two cut papers: the paper card and an olive sheet pasted beneath it.
- **Corner Style:** 3px (`plate`); the window takes 3px top corners.
- **Background:** paper on the green work sheet; the window above is sky paper holding either a partial roundel (46% wide, max 220px) or a cover photo.
- **Under-sheet:** olive, 7px larger than the plate on every side, slightly rotated so it peeks out unevenly (-1.2deg by default, -0.5deg on the featured plate, +0.9deg on the third). The plates grid isolates stacking so the under-sheet stays behind its plate.
- **Cut edge:** the body's top is cut with the hills silhouette (16px band of paper) where it meets the window, so the copy reads as a paper pasted over the picture. Hidden on the featured plate at desktop width, where window and body sit side by side.
- **Shadow Strategy:** none; depth is the overlap of plate over under-sheet.
- **Internal Padding:** 26px 28px 30px; the wide lead plate uses 40px `clamp(28px, 4vw, 56px)`.
- **Content order:** title, one sentence, then the tag row led by the "Coming soon" tag. Plates present planned project types honestly; they never carry invented clients, results or numbers.

### Navigation
Brand mark (a four-layer mini roundel at 34px plus "Jake" in Besley 500 at 1.25rem), four section links in Albert Sans 500 with no underline until hover, and a compact primary button. Below 900px the links hide; below 480px the header button hides too.

### Roundel
The one illustration. Layer symbols, bottom to top: `ring`, `sky`, `sun`, `ridge`, `trees`, `grass`, `birds`, `cutline`, each a 400 by 400 viewBox clipped to the disc. Any roundel is a `<use>` stack of a subset of these layers in that order; plate windows and the brand mark use partial stacks.
- **Hero settle:** on load, each layer drops from 18px above with a -2deg tilt and fades in over 0.9s on the page ease, staggered 0.1 to 0.78s in stack order. It plays once.
- **Process build:** the process roundel starts with ring, sky, ridge and grass. Reaching step 2 lays the trees on; step 3 adds sun and birds. Hidden layers wait 22px above at -3deg and transparent; they land with a 0.5s fade and a 0.7s transform. Only step headings dim: inactive step titles sit at 0.5 opacity and the active one at full, over 0.5s; step body text stays at full strength. Driven by an IntersectionObserver on the middle 10% of the viewport; with no observer support or reduced motion, everything shows complete.

### Portrait
An arched green panel (4:5) holding a photo, or until one exists, a large sky-coloured Besley "J".

## Do's and Don'ts

### Do:
- **Do** build every new section as a sheet with its own paper, a cut top edge from the silhouette set, and an under-sliver of a third paper (see The Under-Sliver Rule).
- **Do** illustrate only with the roundel's layer symbols, stacked in their fixed order; make a new scene by choosing a subset of layers, not by drawing new art.
- **Do** keep every new shape symmetric about a vertical fold where it represents landscape.
- **Do** use the single page ease (`cubic-bezier(.16, 1, .3, 1)`) for every transition, and animate only layers landing on the stack.
- **Do** honour reduced motion: smooth scroll off, every animation and transition off, every roundel shown complete.
- **Do** keep Worn Ink at or darker than its current value (about 5.4:1 on ochre).
- **Do** add projects by copying a plate; mark unfinished ones with the "Coming soon" tag, never with made-up numbers.

### Don't:
- **Don't** use box shadows, drop shadows, blur, glow, gradients or transparency between papers (The Paste, Don't Lift Rule).
- **Don't** introduce colours outside the token set or tint existing ones; a new colour is a new paper token.
- **Don't** use vermilion for links, icons or general highlights (The One Sun Rule).
- **Don't** put a kicker, eyebrow or status label above a heading (The No Kicker Rule).
- **Don't** set display type in bold weights or in uppercase with letter spacing.
- **Don't** replace the papercut roundel with stock illustration, icon sets or photography-as-decoration; photos belong only in plate windows and the portrait.
- **Don't** make Reading Paper or white the page ground; the base paper is ochre, and reading happens on paper sheets pasted over it.
