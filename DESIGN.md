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
  steel-shade: "#6c7077"
  screen: "#000000"
  selection-text: "#ffffff"
  app-plate: "#c8441d"
  app-white: "#f5f5f7"
typography:
  display:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "clamp(3.25rem, 8.4vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 68"
  display-closing:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "clamp(3rem, 8vw, 6rem)"
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
  label-grid:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "0.08em"
    fontVariation: "'wdth' 80"
  row-head:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
    lineHeight: 1.2
    fontVariation: "'wdth' 92"
  small:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 92"
  caption:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 92"
  stamp:
    fontFamily: "Archivo, Arial Narrow, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.06em"
    fontVariation: "'wdth' 75"
  hand:
    fontFamily: "Kalam, Bradley Hand, cursive"
    fontSize: "1.1875rem"
    fontWeight: 700
    lineHeight: 1.1
  hand-aside:
    fontFamily: "Kalam, Bradley Hand, cursive"
    fontSize: "1.25rem"
    fontWeight: 700
    lineHeight: 1.2
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
  staple: "2px"
  mark: "10px"
  mark-lg: "20px"
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
    backgroundColor: "{colors.screen}"
    rounded: "{rounded.screen}"
    width: "300px"
  stamp:
    textColor: "{colors.change}"
    typography: "{typography.stamp}"
    rounded: "{rounded.none}"
    padding: "7px 12px 5px"
  stamp-closing:
    textColor: "{colors.ink}"
    typography: "{typography.stamp}"
  form-foot:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "12px 0 0"
  form-foot-value:
    textColor: "{colors.marker}"
    padding: "0 8px"
  ruled-field:
    textColor: "{colors.marker}"
    typography: "{typography.hand}"
    rounded: "{rounded.none}"
    padding: "8px 0"
---

# Design System: Steady

## Overview

**Creative North Star: "La fiche d'entraînement"**

Every surface is a printed gym workout card, filled in by hand, filed in a charcoal card rack. The card stock carries everything: a black printed grid, condensed printed headings and field labels, and entries written in blue marker. The page does not decorate the card; it is the card. Content that the program writes (loads, reps, verdicts, ticks) is handwritten; the frame that holds it (headings, column heads, labels, rules) is printed.

The system is flat and dense like a real form: hard 1.5 to 2px black rules, square corners, generous card padding, and no shading of any kind. Depth exists only because one card physically overlaps the edge of the previous one. Colour is rationed: the stocks are pale and quiet, the ink is black, the marker is blue, and a single dark red is reserved for whatever progresses.

Motion is ink and paper, not interface. Ink writes: on arrival the ticks are traced, then the grid writes itself row by row; changed entries write in from left to right, a progressing value is circled by a hand loop, a refused notch is struck through then rewritten, the TV address is written letter by letter, and drawn lines (chart, padlock) trace themselves when they come into view. Objects move the way they would on the bench: plates slide on and off the sleeve, a rubber stamp lands, cards settle onto the stack as they scroll in, and the TV capture's rest clock ticks for five seconds per viewing and stops. One row is held at a time while the rest dim. Nothing floats, bounces or loops. All motion sits behind a `motion` class set only when `prefers-reduced-motion` does not ask for less, and every animation and transition is off under reduced motion.

**Key Characteristics:**
- Charcoal rack ground with square card stocks in orange, bristol white and pale blue, stacked by overlap.
- Two hands: condensed Archivo for everything printed, Kalam marker for everything written.
- One change colour, used only on what progresses, lightens or breaks a record.
- Black printed grids and boxes as the main structure; impossible values shown as barred empty cells.
- A perforated filing hole punched at the top centre of every card.

## Colors

A quiet paper palette on a near-black rack, with blue marker for entries and one dark red that means "this changed".

### Primary
- **Blue Marker** (marker): every handwritten entry: grid values, ticks, notes, verdicts, header field values, the stepper readout. Also the focus outline and text selection (white text, selection-text, on marker), because focus is the pen pointing at a line.

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
- **Staple Steel** (steel) and **Staple Shade** (steel-shade): the two hard-stop bands of a staple (top 60% steel, bottom shade); staples only.
- **Screen Black** (screen): behind app screenshots while they load; the phone glass, never a surface.
- **Muted per stock** (muted-on-orange, muted-on-white, muted-on-blue): small print, column sub-heads, captions and barred-row labels. Each stock carries its own muted ink so small text stays legible on that paper; never reuse one stock's muted ink on another.

### Borrowed from the app (not page palette)
- **App Plate Red** (app-plate) and **App White** (app-white): the colours of the Steady icon (the plate and the bar) and of the app's own TV screen. They appear only inside the inline app mark and in the live clock drawn over the TV capture, where they must match the app's pixels. Never use them on stock, type or controls of the page.

### Named Rules
**The One Change Colour Rule.** Progress Red marks change and nothing else. If an element is red, the reader must be able to say what progressed, lightened or broke. A screen with no change shows no red.

**The Stock Is The Surface Rule.** Every content surface is one of the three card stocks on the rack. No fourth stock, no tinted panels inside a card; inside a card, structure comes from black rules and boxes.

## Typography

**Print Font:** Archivo variable (with Arial Narrow, sans-serif), self-hosted, width axis 62 to 125%.
**Hand Font:** Kalam 400 and 700 (with Bradley Hand, cursive), self-hosted.

**Character:** A condensed industrial print face for the form, a loose felt-tip hand for what is written on it. The contrast between the two is the whole typographic idea.

### Hierarchy
- **Display** (Archivo 800, width 68%, clamp 3.25 to 6rem, 0.95): the one H1 on the lead card.
- **Display Closing** (Archivo 800, width 68%, clamp 3 to 6rem, 0.95): the « Steady » wordmark heading the closing card.
- **Headline** (Archivo 800, width 68%, clamp 2.25 to 3.75rem, 0.95): one per card, balanced wrap.
- **Lead** (Archivo 400, width 92%, clamp 1.125 to 1.3rem, 1.45, Soft Print, max 36em): the purpose line under a display or headline.
- **Body** (Archivo 400, width 92%, 1.0625rem, 1.5; 1rem on phones): card copy, max 34em.
- **Label** (Archivo 700, width 80%, 0.8125rem, 0.08em, uppercase): printed field labels, legends, column heads and form footers.
- **Label Grid** (Archivo 700, width 80%, 0.75rem, 1.15, 0.08em, uppercase): column heads inside grids; their muted sub-head is 0.75rem 500 in sentence case.
- **Row Head** (Archivo 600, width 92%, 1rem, 1.2): exercise names heading a grid row. Also the phone body size.
- **Small** (Archivo 400, width 92%, 0.9375rem): small print under a grid (legend line), explanations in the notch table, tick labels on phones; in the stock's muted ink or Soft Print.
- **Caption** (Archivo 400, width 92%, 0.875rem, muted ink, centred): figure captions and image credits.
- **Stamp** (Archivo 800, width 75%, 1.375rem, 1, 0.06em, uppercase): rubber stamps only.
- **Hand** (Kalam 700, 1.1875rem, 1.1, Blue Marker): grid entries, load chips, notch values.
- **Hand Aside** (Kalam 700, 1.25rem, Blue Marker): a written line under a large value (plates per side, the unit beside the stepper load); ruled fields scale it up to 1.5rem.
- **Hand Display** (Kalam 700, clamp 2.75 to 4rem, 1): a single large written value such as the stepper load.
- **Note** (Kalam 400, 1.125rem, 1.35, Blue Marker): a short handwritten aside under a control.

### Named Rules
**The Two Hands Rule.** Printed means the form; handwritten means the data. Headings, labels and instructions are Archivo; values the program or the user writes are Kalam in Blue Marker. Never set a heading in Kalam or a written value in Archivo.

**The Field Label Rule.** Uppercase printed labels name a field, a box or a column, the way a printed form does. They never sit above a headline as a kicker; the printed form footer that names each card closes the card at the bottom.

## Layout

A single centred column of cards (max 1360px) on the rack, with a fluid gutter (clamp 16 to 48px). Cards alternate an inset of up to 96px on the right then the left, so the stack reads as cards filed slightly askew; the lead card spans the full width. Spacing follows a 4/8 scale (s1 to s8: 4, 8, 12, 16, 24, 32, 48, 72px).

The lead card is a two-column grid: the card header across the top, the headline and grid on the left, the equipment box on the right (240 to 300px). Feature cards split copy and proof about 5:6 and flip side from card to card.

At 960px and below, every card collapses to one column. At 600px and below, card padding becomes 40px top, 16px sides, overlap shrinks to 12px with a 10px alternate inset, the equipment list goes two-up, and the exercise grid reflows into a row per exercise with a full-width name cell over four week cells.

## Elevation & Depth

No shadows, no shading gradients, no blur. Depth is physical: each card sits 18px over the bottom edge of the previous one (12px on phones), and photos are stapled on top of the card with a steel staple. The filing hole is the rack showing through the card. Where scroll-driven animation is supported, each card rises 48px into its overlapping place as it enters the viewport; the overlap it lands on is still the only depth.

### Named Rules
**The Overlap Only Rule.** Something is above something else only because it overlaps it. If a layer needs a shadow to read as raised, it is the wrong layer.

## Shapes

Square paper. Cards, boxes, grid cells, buttons, chips and tick boxes all have square corners and 1.5px (grid) or 2px (boxes and controls) black borders. Round shapes are reserved for real round objects: the 18px filing hole, the hand-drawn loop around a progressing value, app screens (26px, they are phones) and the app mark (10px small, 20px large, the icon's own corners). The 2px staple radius is a pen-tip softening, not a corner style: it rounds staples, the struck-through line and the focus outline, nothing else.

Rubber stamps are the one tilted shape: a 3px bordered box rotated -7deg, because a stamp is never set straight.

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
- **Entries:** Hand style in Blue Marker; the progressing value in Progress Red, circled by a hand loop (inline SVG path, pathLength 1, 2.2px Progress Red stroke) traced 380ms after its row writes in.
- **Impossible / unavailable:** barred empty cells (one diagonal hairline), row label muted.
- **Hold:** hovering or focusing a row dims the others to 40%.
- **Write-in:** changed rows reveal left to right by clip (0.7s, cubic-bezier(.16, 1, .3, 1), 70ms per row, 45ms per cell).
- **Intro:** on load the ticked boxes are traced first (110ms apart), then the rows write in from 600ms at 110ms per row, loops at 1s.
- **Footer:** small print in the stock's muted ink; the change legend in Hand, Progress Red.

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

### Loaded Bar
A drawn barbell in Print Black under the stepper. On + or − the changed plates slide onto the sleeve (70px from the outside, 0.45s, cubic-bezier(.16, 1, .3, 1)) or slide off (0.3s, cubic-bezier(.7, 0, .84, 0)).

### Notch Table
A printed grid of progression notches: printed number in Hand, the load in Blue Marker, the explanation in Small. The next notch is Progress Red. Answering « Non » to « technique propre » strikes the notch through with a 3px Progress Red line drawn from the left (0.35s, cubic-bezier(.65, 0, .35, 1)), then the row is rewritten 520ms later.

### Rubber Stamp
Uppercase Stamp type in a 3px box of its own colour, rotated -7deg, landing from scale 1.15 with a fade (0.4s, cubic-bezier(.16, 1, .3, 1)). « Allégée » beside a lightened verdict is Progress Red, because it marks a change; « Séance terminée » on the closing card is Print Black and lands 0.3s after the card comes into view.

### Form Footer
Every feature card closes with a printed form footer spanning the card under a 2px black rule: the form's name in Archivo 800, then label/value pairs in Label style with values in Kalam 700 1.125rem Blue Marker on a 1px underline, like the header fields. Always last in the card, never above the heading.

### Marker Chart
A progress curve on a printed grid: 1px Print Black grid lines at 30% opacity, axis numbers and week heads in 11px Label style in muted ink, the curve and its points in Blue Marker, a record circled by a Progress Red loop with a « Record » note in Hand. The curve traces itself on view; the caption sits left.

### Drawn Lines on View
Any `.ink` path (chart curve, record loop, padlock) is a Blue Marker 3px round-capped stroke with pathLength 1, traced once over 1.4s (cubic-bezier(.65, 0, .35, 1)) when 40% of its block enters the viewport, with per-path delays to draw in order.

### Vault and Ruled Fields
A padlock drawn in 4px marker ink beside a definition list of ruled lines: printed label, value in Kalam 700 Blue Marker (clamp 1.25 to 1.5rem), a 1.5px black rule under each line.

### TV Card
- **Address:** the TV address as a link in Kalam 700 Blue Marker (clamp 1.5 to 2.5rem) on a 2px black underline, under a printed field label; on view it is written letter by letter (one every 40ms).
- **Steps:** a numbered list whose numbers are Kalam 700 1.75rem in Blue Marker in a 28px column.
- **Capture:** the full-width TV screenshot (see Stapled Photos) with a live clock drawn over the app's own rest timer in the borrowed app colours; it ticks once a second for at most five seconds each time the capture is half in view, and never loops.

### Stapled Photos
App screenshots at up to 300px, 26px screen radius, 2px black outline, Screen Black behind, a 46 x 7px steel staple at top centre. Pairs overlap by 6% with the second dropped 72px. A wide (landscape) capture spans the card and takes two staples at 24% and 76%. Caption in Caption style, muted, centred; third-party images carry their credit and licence (CC BY-SA) in the caption with links.

### Verdict
A line in Hand style (clamp 1.5 to 2rem) under a 2px printed rule, in Blue Marker; Progress Red only when the verdict is a change (session lightened), with the « Allégée » stamp beside it.

## Do's and Don'ts

### Do:
- **Do** put every content surface on one of the three card stocks, stacked by an 18px overlap with alternating inset.
- **Do** write data in Kalam Blue Marker and print structure in condensed Archivo (width 68% headings, 80% labels, 92% body).
- **Do** reserve Progress Red for what progressed, lightened or changed; circle it by hand in grids.
- **Do** show what cannot be done as a barred empty cell, not as a disabled grey control or a hidden row.
- **Do** keep borders black and square: 1.5px for grid lines, 2px for boxes and controls.
- **Do** use each stock's own muted ink for small print on that stock.
- **Do** keep motion to ink (clip write-in, traced loops, strikes and lines, letter-by-letter writing), physical objects (plates on the sleeve, stamps landing, cards settling 48px onto the stack, a clock ticking at most 5 s per viewing) and row holding; gate it behind the motion class and disable it under reduced motion.
- **Do** close every feature card with its printed form footer.
- **Do** credit third-party images and their licence in the caption.

### Don't:
- **Don't** add box-shadows, blur, glows or shading gradients; hard-stop gradients are only for drawing lines (bars, staples).
- **Don't** round card, box or control corners; round only real round things (hole, phone screens, app mark, the hand-drawn circle).
- **Don't** use Progress Red, or any extra hue, for emphasis, headings, links or buttons.
- **Don't** put an uppercase printed label above a headline as a kicker; printed caps label fields only.
- **Don't** set headings in Kalam or values in Archivo.
- **Don't** tilt or float product screens in a device mockup; they are stapled flat onto a card.
- **Don't** loop, float or bounce anything; every motion plays once per trigger and stops.
- **Don't** use the borrowed app colours (app plate red, app white) outside the app mark and the TV capture overlay.
