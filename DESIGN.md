---
name: Steady
description: La fiche d'entraînement imprimée, remplie au marqueur, rangée dans un casier anthracite.
colors:
  rack: "#1c1c1e"
  rack-ink: "#c9c6c0"
  orange: "#f3a26e"
  white: "#eef0f2"
  blue: "#a9cbe8"
  ink: "#141414"
  ink-soft: "#3a3633"
  marker: "#1b3aa8"
  change: "#8a0f0a"
  steel: "#8b8f96"
  muted-on-orange: "#4a2a17"
  muted-on-white: "#4b4f55"
  muted-on-blue: "#213a52"
typography:
  display:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "clamp(3.25rem, 8.4vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 68"
  headline:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "clamp(2.25rem, 5vw, 3.75rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 68"
  body:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 92"
  lead:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "clamp(1.125rem, 1.6vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.45
    fontVariation: "'wdth' 92"
  label:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "0.08em"
    fontVariation: "'wdth' 80"
  hand:
    fontFamily: "Kalam, Bradley Hand, cursive"
    fontSize: "1.1875rem"
    fontWeight: 700
    lineHeight: 1.1
  hand-display:
    fontFamily: "Kalam, Bradley Hand, cursive"
    fontSize: "clamp(2.75rem, 6vw, 4rem)"
    fontWeight: 700
    lineHeight: 1
  note:
    fontFamily: "Kalam, Bradley Hand, cursive"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.35
rounded:
  none: "0px"
  hole: "50%"
  mark: "10px"
  screen: "26px"
spacing:
  s1: "4px"
  s2: "8px"
  s3: "12px"
  s4: "16px"
  s5: "24px"
  s6: "32px"
  s7: "48px"
  s8: "72px"
  gutter: "clamp(16px, 4vw, 48px)"
  card: "clamp(24px, 4vw, 56px)"
components:
  card-orange:
    backgroundColor: "{colors.orange}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(40px, 5vw, 64px) clamp(24px, 4vw, 56px) clamp(24px, 4vw, 56px)"
  card-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(40px, 5vw, 64px) clamp(24px, 4vw, 56px) clamp(24px, 4vw, 56px)"
  card-blue:
    backgroundColor: "{colors.blue}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "clamp(40px, 5vw, 64px) clamp(24px, 4vw, 56px) clamp(24px, 4vw, 56px)"
  button-step:
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    size: "56px"
  tick-box:
    textColor: "{colors.marker}"
    rounded: "{rounded.none}"
    size: "28px"
  option-chip:
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0 16px"
    height: "44px"
  option-chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.orange}"
  grid-cell:
    textColor: "{colors.marker}"
    typography: "{typography.hand}"
    rounded: "{rounded.none}"
    padding: "8px 12px"
  grid-cell-up:
    textColor: "{colors.change}"
    typography: "{typography.hand}"
  load-chip:
    textColor: "{colors.marker}"
    typography: "{typography.hand}"
    rounded: "{rounded.none}"
    padding: "8px 12px"
  phone-shot:
    backgroundColor: "#000000"
    rounded: "{rounded.screen}"
    width: "300px"
---

# Design System: Steady

## Overview

**Creative North Star: "La fiche d'entraînement"**

Every surface is a printed gym workout card, filled in by hand, filed in a charcoal card rack. The card stock carries everything: a black printed grid, condensed printed headings and field labels, and entries written in blue marker. The page does not decorate the card; it is the card. Content that the program writes (loads, reps, verdicts, ticks) is handwritten; the frame that holds it (headings, column heads, labels, rules) is printed.

The system is flat and dense like a real form: hard 1.5 to 2px black rules, square corners, generous card padding, and no shading of any kind. Depth exists only because one card physically overlaps the edge of the previous one. Colour is rationed: the stocks are pale and quiet, the ink is black, the marker is blue, and a single dark red is reserved for whatever progresses.

Motion is ink, not interface: entries write themselves in from left to right, ticks are drawn rather than toggled, and one row is held at a time while the rest dim. Nothing floats, slides or bounces. All motion stops under `prefers-reduced-motion`.

**Key Characteristics:**
- Charcoal rack ground with square card stocks in orange, bristol white and pale blue, stacked by overlap.
- Two hands: condensed Archivo for everything printed, Kalam marker for everything written.
- One change colour, used only on what progresses, lightens or breaks a record.
- Black printed grids and boxes as the main structure; impossible values shown as barred empty cells.
- A perforated filing hole punched at the top centre of every card.

## Colors

A quiet paper palette on a near-black rack, with blue marker for entries and one dark red that means "this changed".

### Primary
- **Blue Marker** (marker): every handwritten entry: grid values, ticks, notes, verdicts, header field values, the stepper readout. Also the focus outline and text selection, because focus is the pen pointing at a line.

### Secondary
- **Progress Red** (change): only what progresses or changes state: the circled week-4 value, the next notch after « technique propre », the lightened-session verdict, the "Entouré" legend. Never decorative, never a heading, never a button.

### Tertiary
- **Orange Stock** (orange): the lead card stock (hero and closing card) and the selected-option text on an ink fill.
- **Bristol White Stock** (white): alternate card stock.
- **Pale Blue Stock** (blue): alternate card stock; selected segment text on ink.

### Neutral
- **Card Rack Charcoal** (rack): page ground, the filing hole (the rack seen through the card), theme colour. Matches the app icon ground.
- **Rack Label Grey** (rack-ink): footer text on the rack.
- **Print Black** (ink): printed rules, grid lines, box borders, headings and body text on stock; fill of selected options.
- **Soft Print** (ink-soft): lead paragraphs and secondary table text.
- **Staple Steel** (steel): staples on photos only.
- **Muted per stock** (muted-on-orange, muted-on-white, muted-on-blue): small print, column sub-heads, captions and barred-row labels. Each stock carries its own muted ink so small text stays legible on that paper; never reuse one stock's muted ink on another.

### Named Rules
**The One Change Colour Rule.** Progress Red marks change and nothing else. If an element is red, the reader must be able to say what progressed, lightened or broke. A screen with no change shows no red.

**The Stock Is The Surface Rule.** Every content surface is one of the three card stocks on the rack. No fourth stock, no tinted panels inside a card; inside a card, structure comes from black rules and boxes.

## Typography

**Print Font:** Archivo variable (with Arial Narrow, sans-serif), self-hosted, width axis 62 to 125%.
**Hand Font:** Kalam 400 and 700 (with Bradley Hand, cursive), self-hosted.

**Character:** A condensed industrial print face for the form, a loose felt-tip hand for what is written on it. The contrast between the two is the whole typographic idea.

### Hierarchy
- **Display** (Archivo 800, width 68%, clamp 3.25 to 6rem, 0.95): the one H1 on the lead card, and the closing wordmark.
- **Headline** (Archivo 800, width 68%, clamp 2.25 to 3.75rem, 0.95): one per card, balanced wrap.
- **Lead** (Archivo 400, width 92%, clamp 1.125 to 1.3rem, 1.45, Soft Print, max 36em): the purpose line under a display or headline.
- **Body** (Archivo 400, width 92%, 1.0625rem, 1.5; 1rem on phones): card copy, max 34em.
- **Label** (Archivo 700, width 80%, 0.8125rem, 0.08em, uppercase): printed field labels, legends and column heads (0.75rem in grids).
- **Hand** (Kalam 700, 1.1875rem, 1.1, Blue Marker): grid entries, load chips, notch values.
- **Hand Display** (Kalam 700, clamp 2.75 to 4rem, 1): a single large written value such as the stepper load.
- **Note** (Kalam 400, 1.125rem, 1.35, Blue Marker): a short handwritten aside under a control.

### Named Rules
**The Two Hands Rule.** Printed means the form; handwritten means the data. Headings, labels and instructions are Archivo; values the program or the user writes are Kalam in Blue Marker. Never set a heading in Kalam or a written value in Archivo.

**The Field Label Rule.** Uppercase printed labels name a field, a box or a column, the way a printed form does. They never sit above a headline as a kicker.

## Layout

A single centred column of cards (max 1360px) on the rack, with a fluid gutter (clamp 16 to 48px). Cards alternate an inset of up to 96px on the right then the left, so the stack reads as cards filed slightly askew; the lead card spans the full width. Spacing follows a 4/8 scale (s1 to s8: 4, 8, 12, 16, 24, 32, 48, 72px).

The lead card is a two-column grid: the card header across the top, the headline and grid on the left, the equipment box on the right (240 to 300px). Feature cards split copy and proof about 5:6 and flip side from card to card.

At 960px and below, every card collapses to one column. At 600px and below, card padding becomes 40px top, 16px sides, overlap shrinks to 12px with a 10px alternate inset, the equipment list goes two-up, and the exercise grid reflows into a row per exercise with a full-width name cell over four week cells.

## Elevation & Depth

No shadows, no shading gradients, no blur. Depth is physical: each card sits 18px over the bottom edge of the previous one (12px on phones), and photos are stapled on top of the card with a steel staple. The filing hole is the rack showing through the card.

### Named Rules
**The Overlap Only Rule.** Something is above something else only because it overlaps it. If a layer needs a shadow to read as raised, it is the wrong layer.

## Shapes

Square paper. Cards, boxes, grid cells, buttons, chips and tick boxes all have square corners and 1.5px (grid) or 2px (boxes and controls) black borders. Round shapes are reserved for real round objects: the 18px filing hole, the hand-drawn circle around a progressing value (irregular elliptical radius), app screens (26px, they are phones) and the app mark (10px small, 20px large, the icon's own corners).

Lines are drawn, not filled: a barred cell is a single diagonal black hairline across an empty box; rule bullets are 16 x 4px black dashes.

## Components

### Cards
Square stock, no border, no shadow.
- **Background:** Orange, Bristol White or Pale Blue stock; text in Print Black.
- **Padding:** clamp 40 to 64px top (room for the hole), clamp 24 to 56px elsewhere.
- **Filing hole:** 18px circle in rack charcoal, 14px from the top, centred.
- **Header (lead card):** mark and wordmark left, printed fields right (label in caps, value in marker on an underline), 2px black rule beneath.

### Printed Grid
The signature component: the workout card itself.
- **Structure:** collapsed table, 1.5px black borders, 8 x 12px cell padding; column heads in Label style with a muted sub-head.
- **Row heads:** Archivo 600 exercise name over a tiny uppercase muted zone label.
- **Entries:** Hand style in Blue Marker; the progressing value in Progress Red, circled by a 2px hand-drawn ring.
- **Impossible / unavailable:** barred empty cells (one diagonal hairline), row label muted.
- **Hold:** hovering or focusing a row dims the others to 40%.
- **Write-in:** changed rows reveal left to right by clip (0.7s, cubic-bezier(.16, 1, .3, 1), 70ms stagger).

### Tick Boxes
- **Style:** 28px square, 2px black border, transparent; the row is a 48px-tall label in Archivo 600.
- **Checked:** a marker tick drawn in left to right (0.28s clip reveal).
- **Hover:** box lightens with a 25% white wash.

### Buttons (stepper)
- **Shape:** 56px square, 2px black border, transparent, glyph drawn as an inline SVG stroke.
- **Hover / Active:** 6% then 12% black wash. **Disabled:** 30% opacity.
- **Focus:** 3px Blue Marker outline, 3px offset (global).

### Option Chips and Segments
- **Style:** 44px tall, 2px black border, square, Archivo 600 to 700; segments share borders inside one box.
- **Selected:** filled Print Black, text in the card's own stock colour (orange on orange cards, blue on blue cards).
- **Focus:** 3px Blue Marker outline, 2px offset.

### Load Chips
Hand-style values in 1.5px black boxes; impossible loads are barred and muted.

### Stapled Photos
App screenshots at up to 300px, 26px screen radius, 2px black outline, a 46 x 7px steel staple at top centre. Pairs overlap by 6% with the second dropped 72px. Caption small and muted, centred.

### Verdict
A line in Hand style (clamp 1.5 to 2rem) under a 2px printed rule, in Blue Marker; Progress Red only when the verdict is a change (session lightened).

## Do's and Don'ts

### Do:
- **Do** put every content surface on one of the three card stocks, stacked by an 18px overlap with alternating inset.
- **Do** write data in Kalam Blue Marker and print structure in condensed Archivo (width 68% headings, 80% labels, 92% body).
- **Do** reserve Progress Red for what progressed, lightened or changed; circle it by hand in grids.
- **Do** show what cannot be done as a barred empty cell, not as a disabled grey control or a hidden row.
- **Do** keep borders black and square: 1.5px for grid lines, 2px for boxes and controls.
- **Do** use each stock's own muted ink for small print on that stock.
- **Do** keep motion to ink writing in (left-to-right clip) and row holding; disable it under reduced motion.

### Don't:
- **Don't** add box-shadows, blur, glows or shading gradients; hard-stop gradients are only for drawing lines (bars, staples).
- **Don't** round card, box or control corners; round only real round things (hole, phone screens, app mark, the hand-drawn circle).
- **Don't** use Progress Red, or any extra hue, for emphasis, headings, links or buttons.
- **Don't** put an uppercase printed label above a headline as a kicker; printed caps label fields only.
- **Don't** set headings in Kalam or values in Archivo.
- **Don't** tilt or float product screens in a device mockup; they are stapled flat onto a card.
