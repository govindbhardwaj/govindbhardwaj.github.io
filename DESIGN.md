---
name: Govind Bhardwaj
description: A career drawn as a metro network, set in black bilingual signage on a white map ground.
colors:
  ground: "#ffffff"
  ink: "#141414"
  ink-hover: "#33373c"
  ink-2: "#4b5057"
  rule: "#e1e3e6"
  wash: "#f3f4f6"
  sign: "#141414"
  sign-2: "#c9cdd2"
  blue: "#1263b5"
  red: "#d42a2a"
  violet: "#7b2d8e"
  yellow: "#f2b705"
  yellow-case: "#a87a00"
  green: "#1c7c38"
typography:
  display:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "clamp(34px, 5vw, 72px)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  display-devanagari:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0"
  headline:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "clamp(34px, 4vw, 52px)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "26px"
    fontWeight: 800
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "\"tnum\" 1"
  button:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1
  label:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.3
  caption:
    fontFamily: "Mukta, Noto Sans, Segoe UI, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
  mono:
    fontFamily: "ui-monospace, Cascadia Mono, Consolas, monospace"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  photo: "4px"
  control: "6px"
  sign: "8px"
  panel: "10px"
  capsule: "999px"
spacing:
  2xs: "4px"
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  section-mobile: "72px"
  section: "112px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ground}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "3px 20px 0"
    height: "48px"
  button-primary-hover:
    backgroundColor: "{colors.ink-hover}"
  button-secondary:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "3px 20px 0"
    height: "48px"
  button-secondary-hover:
    backgroundColor: "{colors.wash}"
  button-primary-on-sign:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "3px 20px 0"
    height: "48px"
  title-sign:
    backgroundColor: "{colors.sign}"
    textColor: "{colors.ground}"
    rounded: "{rounded.sign}"
    padding: "16px 26px 10px"
  nameplate:
    backgroundColor: "{colors.sign}"
    textColor: "{colors.ground}"
    typography: "{typography.title}"
    rounded: "{rounded.control}"
    padding: "13px 18px 9px"
  station-code:
    backgroundColor: "{colors.sign}"
    textColor: "{colors.ground}"
    rounded: "{rounded.control}"
    padding: "3px 8px 0"
    height: "34px"
    width: "46px"
  interchange-capsule:
    backgroundColor: "{colors.ground}"
    rounded: "{rounded.capsule}"
    height: "28px"
  line-key:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
  line-key-item-active:
    backgroundColor: "{colors.wash}"
    rounded: "{rounded.control}"
    padding: "4px 6px"
  callout:
    backgroundColor: "{colors.ground}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sign}"
    padding: "16px 20px"
---

# Design System: Govind Bhardwaj

## Overview

**Creative North Star: "The Metro Network Map"**

The site reads as a diagrammatic metro map and its station signage. A career is drawn as a network: disciplines are coloured lines, employers and projects are stations, and anything still ahead is drawn dashed. The grammar is borrowed from Delhi Metro maps and DMRC bilingual signage: a white map ground, thick flat strokes with 45-degree bends and rounded joins, tick stations, white interchange capsules ringed in black, and black signboards set in Mukta with a strip of line colour beneath.

The world is flat, high-contrast and information-dense in the way a transit diagram is dense: every colour carries a meaning, every rule separates something, and nothing is ornamental. Depth comes from black signs sitting on white, not from shadows. The same grammar carries a Persuade page (the homepage, with the full network map) and Read pages (the legal pages), where it narrows to a black title sign, ruled directories, a strip-map contents list and black station-code plates on section numbers.

Motion is limited to what a real map display would do: the lines draw on once, the dashed extensions fade in after them, and the next-station ring blinks a few times like a carriage LED. Choosing a line in the key lights that line and dims the rest.

**Key Characteristics:**
- White map ground, black ink, black signs; colour reserved for the five lines.
- Five line colours, each with a fixed meaning; dashed means under construction / next.
- Interchange capsules: white fill, black ring.
- Black signboards and nameplates carry a stripe of the lines they belong to.
- Ruled directories (2px ink rules) instead of cards.
- Devanagari and English get equal billing wherever both appear.
- Flat: no drop shadows anywhere.

## Colors

A white ground and near-black ink do all the structural work; the five line colours are a code, not a palette, and appear only where they mean a line.

### Primary
- **Signboard Black** (`ink` / `sign`): body text, 2px directory rules, capsule rings, the primary button, and every black sign surface (name sign, nameplates, title sign, station-code plates, the closing contact sign). `ink` and `sign` share a value but name two roles: text and sign surface.
- **Pressed Graphite** (`ink-hover`): hover state of the primary button only.

### Secondary: the line colours
Each colour is a line and always means the same thing. Use them for map strokes, sign stripes, key swatches, rail stubs, nav hover underlines and language/line markers, never as general accents.
- **Platform Blue** (`blue`): Platform & DevOps. Also the system's link and focus colour (focus ring 3px, offset 3px) and the default single line of a strip-map contents list.
- **Backend Red** (`red`): Backend.
- **Reliability Violet** (`violet`): Reliability & security.
- **Mobile Yellow** (`yellow`) with **Yellow Casing** (`yellow-case`): Mobile. Also the text-selection highlight.
- **Foundations Green** (`green`): Foundations (education, early training).

### Neutral
- **Map White** (`ground`): page ground, interchange capsule fill, line key and secondary button fill.
- **Signal Grey** (`ink-2`): secondary text: ledes, dates, summaries, map sub-labels, meta lines (8.1:1 on white).
- **Platform Rule** (`rule`): 1px hairlines: hero bottom edge, table row dividers, legal footer top.
- **Concourse Wash** (`wash`): hover and pressed fill for secondary buttons and key items; scrollbar track.
- **Sign Silver** (`sign-2`): secondary text on black signs (role line, Devanagari on nameplates, plate sub-lines).

### Named Rules
**The Line Means Something Rule.** A line colour appears only where it denotes its line. Blue doubles as the link and focus colour; no other line colour takes a non-line job.

**The Cased Yellow Rule.** Mobile yellow is 1.8:1 on white, so on the white ground it is always drawn with its darker casing (`yellow-case`): a 17px casing under a 12px yellow stroke, a 2px casing on yellow ticks, a 1.5px inset ring on the key swatch. On black signs it needs no casing.

**The Dashed Future Rule.** Dashed strokes, dashed capsules and dash-masked rails mean "under construction / next". Nothing that already happened is ever dashed.

## Typography

**Display Font:** Mukta 800 (with Noto Sans, Segoe UI, sans-serif)
**Body Font:** Mukta 400 (same stack)
**Label/Mono Font:** Mukta 600 for labels; the system monospace stack (ui-monospace, Cascadia Mono, Consolas) only for repository paths.

**Character:** One signage family in three weights (400, 600, 800), loaded with both Devanagari and Latin, so Hindi and English set side by side from the same design. Heavy, tight-tracked headings read like platform signs; open 17px body reads like a timetable note. Numerals are tabular throughout.

### Hierarchy
- **Display** (800, clamp(34px, 5vw, 72px), 1.05, -0.02em): the closing contact sign. The legal title sign uses the same voice at clamp(36px, 5vw, 60px); the hero name sign at clamp(26px, 3cqw, 52px) inside the map stage.
- **Display, Devanagari** (600, same size as its English partner, 1.2 to 1.25, no negative tracking): the Hindi line of a bilingual sign, set above the English.
- **Headline** (800, clamp(34px, 4vw, 52px), 1.05, -0.02em): homepage section titles. The hook under the hero sign is 800, clamp(22px, 2.15cqw, 37px), 1.12.
- **Title** (800, 26px, 1.25, -0.01em): strip-map station names and nameplates (22px under 760px). Legal section headings use 28px/1.2 (23px under 640px); legal sub-heads 19px.
- **Body** (400, 17px, 1.6): running text; legal prose runs at 1.7 with a 58ch measure; homepage summaries cap at 60 to 62ch.
- **Lede** (400, 18 to 19px, ink-2): section intros and legal ledes, capped at 52 to 54ch.
- **Label** (600, 15px): nav, line key, rail key, contents list; 14px for meta, breadcrumbs and footers.

### Named Rules
**The Equal Billing Rule.** Where Devanagari and English both appear, they share the same size, Hindi first, as on DMRC signs; Devanagari is set at 600 with looser leading so it carries the same visual weight as the 800 Latin. Neither script is a subtitle.

**The Optical Baseline Rule.** Mukta sits high in its box, so filled labels (buttons, plates, signs, station codes) take about 3px more top padding than bottom (buttons `3px 20px 0`, plates `13px 18px 9px`).

## Layout

The homepage hero is a full-bleed stage at the map's own aspect ratio (1440 x 800), sized to fit one viewport, with the name sign pinned top-left and the line key top-right, both positioned in container units. Below 1100px the sign stacks above the map, which becomes a horizontally pannable 1100px-wide strip cropped to its busy band and opened on the main interchange.

Content sections sit in a 1240px wrap with 48px gutters (16px under 760px) and 112px vertical padding (72px on mobile). Experience is a two-column grid (320px sticky aside, 64px gap) whose right column is a vertical strip map: rails in fixed slots, one per line, with a capsule at each stop. Directories are three-column ruled rows (name 5fr, description 6fr, actions 180px, 32px gaps) that stack below 760px.

Legal pages use a 1180px measure with 48px gutters: a 250px sticky strip-map contents column beside a 720px prose column, 64px gap. Below 900px the contents becomes a collapsible bordered box above the prose; below 640px tables stack into labelled rows.

Spacing steps through 4, 8, 12, 16, 24, 32, 48 and 64px, with 112px between homepage sections.

## Elevation & Depth

The system is flat. There are no drop shadows. Depth is conveyed by black sign surfaces on the white ground, 2px ink rules and rings, and the overlap of capsules on line strokes. The only inset rings are functional: the 2px ink ring on a pressed line-key item and the 1.5px casing on the yellow swatch.

### Named Rules
**The Signs Not Shadows Rule.** Anything that needs to stand forward becomes a black sign or gets a 2px ink border; nothing floats.

## Shapes

Corners are modest and consistent: 4px on the portrait and focus ring, 6px on buttons, nameplates, station codes and key items, 8px on signs and callouts, 10px on the line key. Stations are full capsules (fully rounded ends) or tick bars. Map strokes are 14px with round caps and joins and bend at 45 degrees through short radii; dashed strokes use butt caps at 24/10. Swatches and rail stubs are rounded bars. Rules are 2px ink for structure and 1px `rule` grey for row dividers.

## Components

### Buttons
Solid, square-shouldered and plain, like a ticket-machine key.
- **Shape:** gently rounded (6px), 2px ink border, 48px tall (40px in the header, 44px in directory rows).
- **Primary:** ink fill, white text, Mukta 600 16px, `3px 20px 0` padding; hover shifts to `ink-hover`.
- **Secondary:** white fill, ink text and border; hover fills with `wash`.
- **On a black sign:** primary inverts to white fill and ink text; secondary becomes transparent with a mid-grey border that turns white on hover.
- **Icons:** inline 18px stroke SVGs (envelope, copy, outbound arrow), never glyph characters.
- **Focus:** 3px blue outline, 3px offset (white on black signs).

### Navigation
A sticky white header bar (62px, 58px on mobile) with the line-and-capsule brand mark, Mukta 600 15px links and an Email primary button. Each link hovers (and, on legal pages, marks the current page) with a 3px underline in its own line colour. The five-colour stripe (6px, equal segments blue, red, violet, yellow, green) runs directly beneath the bar. Under 760px (640px on legal pages) the text links hide and only the brand and Email button remain.

### Signs and Nameplates
- **Name sign / title sign:** black, 8px corners, white Mukta 800. On the homepage the name sign holds the portrait and the bilingual name, with the five-colour stripe along its foot.
- **Nameplate:** a black plate (6px top corners) carrying a project name in 26px Mukta 800, any Devanagari name in Sign Silver beside it, and a 7px stripe of only the lines that project sits on.
- **Station code:** a 46 x 34px black plate with a two-digit section number in front of each legal section heading.
- **Contact sign:** the closing section is a full-width black sign with the five-colour stripe along its top, a dashed terminus mark and a bilingual heading.

### Directories (Cards / Containers)
There are no cards. Lists of things are ruled directories: a 2px ink rule above each row and a closing 2px rule below the list, no fill, no radius, no shadow. Legal at-a-glance grids, delete-account options and tables follow the same rule (tables add 1px `rule` row dividers).

### Line Key (Signature Component)
A white panel with a 2px ink border and 10px corners listing the five lines as buttons: a rounded colour swatch, the line name, and a short stack note. Hovering previews and clicking pins a line; the stage then dims every line and station not on it to 13% opacity over 0.35s. Pressed items take a `wash` fill and a 2px inset ink ring and expose `aria-pressed`; Escape clears the selection.

### Strip Map
The vertical form of the network, used for the experience route and for the legal contents list. Rails are rounded colour bars (one fixed slot per line); each stop is a white capsule with a 4px black ring (3px dashed for a planned stop); legal contents use a single 6px blue rail with 14px ringed stations and leading-zero numbers. Delete-account steps use the same form with numbered ringed stations on a blue or violet rail.

### Motion
One entrance sequence, all inside `prefers-reduced-motion: no-preference`: solid strokes draw on over 1.5s with `cubic-bezier(.16, 1, .3, 1)`, staggered per line; dashed extensions fade in over 0.7s after them; the next-station ring blinks four times (1.1s). State changes (hover fills, underlines, isolation dimming) are 0.2 to 0.35s on the same curve.

## Do's and Don'ts

### Do:
- **Do** give every line colour a single meaning and keep that meaning on every surface: blue Platform & DevOps, red Backend, violet Reliability & security, yellow Mobile, green Foundations.
- **Do** draw anything still ahead (next role, extensions, planned stops) dashed, and nothing else.
- **Do** draw stations as white capsules with black rings (4px, 6px for the major interchange) or as line-coloured ticks.
- **Do** put titles on black signs and project names on black nameplates with a stripe of their own lines.
- **Do** separate lists with 2px ink rules, and stack tables into labelled rows under 640px rather than hiding columns.
- **Do** set Devanagari and English at equal size, Hindi first, wherever both appear.
- **Do** case yellow with `yellow-case` whenever it sits on white.
- **Do** keep all entrance motion behind `prefers-reduced-motion: no-preference`.

### Don't:
- **Don't** use a line colour as a generic accent, background tint or decorative fill.
- **Don't** repeat the full five-colour stripe as a section divider or ornament; it belongs under the header and along the homepage's black name and contact signs.
- **Don't** wrap content in cards, add drop shadows, or float panels.
- **Don't** put a kicker or eyebrow label above a heading; a heading stands on its own or on its sign.
- **Don't** draw completed history dashed, or a future stop solid.
- **Don't** add motion beyond the single draw-on sequence, the next-station blink and short state transitions.
- **Don't** shrink the Devanagari line into a subtitle under the English.
