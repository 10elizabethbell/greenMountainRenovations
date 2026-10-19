---
name: Green Mountain Renovations
description: Phone-first single-page pitch site for a one-person drywall business; deep logo green and dry joint-compound white, with the gold taping knife doing the work.
colors:
  green: "#0f402d"
  green-950: "#082a1d"
  green-700: "#1a5a40"
  gold: "#deac39"
  gold-deep: "#a8771a"
  gold-bright: "#ebbd4f"
  mud: "#f1f0ec"
  board: "#d3ccbe"
  joint-tape: "#ece5d4"
  ink: "#16271f"
  ink-soft: "#3c4f45"
  cream: "#f6f1e4"
  cream-soft: "#e6e0c8"
  fresh-coat: "#fffdf8"
  seam-line: "#ddd6c6"
  field-edge: "#8a8069"
  arrow-disc: "#e6dfcf"
  seal-white: "#ffffff"
  error-ink: "#9b2c1c"
  error-edge: "#b3412c"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(3rem, 15vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title-row:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.35rem, 6vw, 2rem)"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  statement:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.3rem, 5.5vw, 1.8rem)"
    fontWeight: 800
    lineHeight: 1.25
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(1.02rem, 4.4vw, 1.2rem)"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1.55
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  photo: "3px"
  pin: "6px"
  field: "10px"
  button: "12px"
  panel: "14px"
  full: "50%"
spacing:
  xs: "8px"
  sm: "10px"
  md: "16px"
  lg: "22px"
  xl: "28px"
  gutter: "20px"
  gutter-wide: "32px"
  section: "72px"
components:
  button-gold:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.green-950}"
    typography: "{typography.button}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "56px"
  button-gold-hover:
    backgroundColor: "{colors.gold-bright}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.cream}"
    typography: "{typography.button}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "56px"
  button-line-hover:
    backgroundColor: "rgba(222,172,57,.14)"
  button-green:
    backgroundColor: "{colors.green}"
    textColor: "{colors.cream}"
    typography: "{typography.button}"
    rounded: "{rounded.button}"
    padding: "0 22px"
    height: "56px"
  button-green-hover:
    backgroundColor: "{colors.green-700}"
  header-contact:
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    padding: "0 4px"
    height: "44px"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title-row}"
    padding: "12px 2px"
    height: "76px"
  service-row-arrow:
    backgroundColor: "{colors.arrow-disc}"
    textColor: "{colors.green}"
    rounded: "{rounded.full}"
    size: "46px"
  service-row-arrow-hover:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.green-950}"
  step-numeral:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.green-950}"
    rounded: "{rounded.full}"
    size: "52px"
  photo-pin:
    backgroundColor: "{colors.seal-white}"
    rounded: "{rounded.pin}"
    padding: "8px"
  proof-link:
    backgroundColor: "{colors.green}"
    textColor: "{colors.cream}"
    rounded: "{rounded.panel}"
    padding: "18px 20px"
  proof-link-hover:
    backgroundColor: "{colors.green-700}"
  text-field:
    backgroundColor: "{colors.fresh-coat}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "54px"
  chip:
    backgroundColor: "{colors.fresh-coat}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "0 18px"
    height: "48px"
  chip-checked:
    backgroundColor: "{colors.green}"
    textColor: "{colors.cream}"
  sent-panel:
    backgroundColor: "{colors.fresh-coat}"
    rounded: "{rounded.panel}"
    padding: "20px"
  sent-message:
    backgroundColor: "{colors.mud}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "14px"
  copy-button:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.field}"
    height: "48px"
  footer:
    backgroundColor: "{colors.green-950}"
    textColor: "{colors.cream}"
    padding: "70px 0 40px"
---

# Design System: Green Mountain Renovations

## Overview

**Creative North Star: "The Finished Wall"**

The page is a freshly finished room. Deep logo green and dry joint-compound white take turns as the ground, each section joined to the next by a moving skim-coat edge, and the gold taping knife from the owner's logo is the only thing that works on the page. The hero holds one live drywall wall: paper tape over the seams, screw dimples down the studs, and the knife skimming wet grey mud that dries to the page's own white. Everything outside that wall is quiet: heavy uppercase headings, plain first-person copy, flat grounds, and physical objects (photos, tape) only where the trade would have them.

The world is joint compound skimmed over taped drywall seams: paper tape, screw dimples, wet mud drying to flat white, feathered knife edges. Photos are taped up with the same paper joint tape. The system is phone-first and built for Facebook's in-app browser; desktop is the phone layout given more room, never a different site.

**Key Characteristics:**
- Two grounds only, strictly alternating: logo green and dry mud white.
- One signature interaction (the hero wall); every other surface is still or barely moving.
- Heavy (900) uppercase display in the system sans; no display webfont.
- Gold is the knife: it marks the primary action and answers hover, it is not decoration.
- Depth belongs to physical objects pinned to the wall, never to sections or panels.

## Colors

A two-ground, one-accent palette sampled from the logo. Green and mud alternate as section grounds; gold appears where the knife would.

### Primary
- **Deep Logo Green** (`green`): the hero ground, the "How it works" and "Where I work" grounds, every h2 on light sections, the submit button, checked chips, and the Facebook proof slab. Also the focus-ring color inside light sections.
- **Night Green** (`green-950`): the footer ground and the text color on every gold fill (buttons, step numerals, arrow discs on hover, selection).
- **Lit Green** (`green-700`): hover state for green fills only (submit button, proof slab).

### Secondary
- **Taping-Knife Gold** (`gold`): the primary button, step numerals, the gold half of the hero headline, the service-area statement, footer tagline, header and footer icons, the arrow disc on row hover, and the global focus ring on green grounds.
- **Knife Gold Deep** (`gold-deep`): the gold that reads on mud. Hover and focus borders on fields, chips and the copy button; hover/focus outlines on buttons inside the form; the arrow focus ring.
- **Bright Knife Gold** (`gold-bright`): hover fill for the gold button, mouse only.

### Neutral
- **Dry Mud** (`mud`): the light section ground and body background. It is also the dry-coat color in the wall canvas (`DRY_RGB` in the first script); the two must change together.
- **Drywall Paper** (`board`): the wall's base and the placeholder behind photos and video before they load.
- **Joint Tape** (`joint-tape`): the paper-tape strips holding photos up and the tape drawn over the canvas seams.
- **Fresh Coat** (`fresh-coat`): fill for text fields, chips and the sent-message panel; a half-step brighter than mud so form surfaces read as new work.
- **Seam Line** (`seam-line`): the 2px rules between service rows and the sent panel's border.
- **Field Edge** (`field-edge`): 2px resting border on fields, chips and the copy button (held at 3:1 against mud).
- **Arrow Disc** (`arrow-disc`): resting fill of the service-row arrow.
- **Wall Ink** (`ink`) and **Ink Soft** (`ink-soft`): text on mud; soft for ledes, "(optional)" hints and the copy note.
- **Cream** (`cream`) and **Cream Soft** (`cream-soft`): text on green; soft for the promise, step body copy and the footer name.
- **Seal White** (`seal-white`): the disc behind the logo mark and seal, and the photo mat on each pin.
- **Error Ink** (`error-ink`) / **Error Edge** (`error-edge`): field error text and the invalid field border; nowhere else.

The neutrals from `fresh-coat` down through `seal-white` and the error pair are currently literal hex values in the stylesheet rather than `:root` custom properties. Promote them before adding new surfaces; the values above are normative.

**The Knife Gold Rule.** Gold is the knife. It fills the primary action, numbers the steps, and answers a pointer; it never tints a section ground, a border at rest, or a body paragraph.

**The Deep Gold on Mud Rule.** Bright `gold` lives on green. On mud and fresh-coat surfaces, any gold line or outline uses `gold-deep`.

## Typography

**Display Font:** system sans stack (`-apple-system`, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

One family, carried by weight and case. Display tiers are 900, uppercase, tight (-0.02em) and nearly solid-leaded (0.98), with `text-wrap: balance`. The ramp is fluid on phones and steps down in big jumps: display (hero) about 1.7x headline, headline about 1.8x the service rows, then a flat band of 1 to 1.5rem UI and body sizes. The hierarchy lives in the display tiers; the UI band is deliberately flat.

### Hierarchy
- **Display** (900, `clamp(3rem,15vw,6rem)`, 0.98): the hero headline only. The second phrase ("to last.") is gold, upright, never italic. In short landscape viewports it drops to `clamp(2.4rem,9vh,3.4rem)`.
- **Headline** (900, `clamp(2rem,9vw,3.6rem)`, 0.98): one h2 per section, green on mud, cream on green.
- **Title Row** (900 uppercase, `clamp(1.35rem,6vw,2rem)`): service rows; the list is set as type, not as cards.
- **Title** (900 uppercase, 1.5rem, 1.1): step headings and the sent-panel heading (at 1.25rem).
- **Statement** (800, `clamp(1.3rem,5.5vw,1.8rem)`, 1.25, 24ch max): a single gold sentence on green, used for the service area. The footer tagline is the same voice in 900 uppercase at `clamp(1.6rem,7vw,2.4rem)`.
- **Promise** (400, `clamp(1.02rem,4.4vw,1.2rem)`, 1.45, 34ch max): the hero's one-line promise in cream-soft; 1.25rem from 1024px.
- **Body** (400, 17px, 1.55): all running copy; 40 to 44ch measures. Inputs use the same 17px so iOS never zooms.
- **Label** (800, 1rem): field labels, legends, header contact, footer links, the proof link (at 1.25rem).
- **Button** (800, 1rem, uppercase, +0.02em, line-height 1): every button; 0.9rem in the two-up hero pair.

**The System Stack Rule.** Every pitch site uses the system font stack by the owner-designer's mandate. Weight 900 and uppercase do the display work; do not add a webfont without that mandate changing.

**The Upright Accent Rule.** Emphasis inside a heading is a color change to gold, never italic or a second family.

## Layout

Phone first, single column, one container: `max-width: 1160px`, centered, with a 20px gutter (`gutter`) that widens to 32px (`gutter-wide`) from 760px. Section bands run full-bleed with vertical padding between 56px and 80px (about `section`, 72px); the lighter Area band uses 56/60px, the form and footer the most.

Inside sections, rhythm comes from a short set of gaps: 8 to 10px between chips and controls, 14 to 16px from heading to lede and between step columns, 22px between form fields, 26 to 28px from h2 to its content, 34 to 40px around the photo board.

### Breakpoints
- **Below 380px:** tighter header (40px mark, 12px gutters).
- **Below 430px:** the "Where quality matters" line under the brand name hides so it never crowds the contact link.
- **760px:** wider gutters; photo board goes to three columns; steps go to three columns with the numeral stacked above.
- **1024px:** the hero becomes two columns (copy left, wall right at min 540px tall, hero up to `min(760px,100svh)`); the estimate section splits heading left, form right (0.9fr / 1.1fr, 64px gap).
- **Landscape under 500px tall:** hero type and spacing compress; the wall drops to 220px.

**The Alternating Coat Rule.** Section grounds alternate strictly: green hero, mud services, green steps, mud work, green area, mud estimate, night-green footer. A new section takes the opposite ground of the one above it.

**The Skim Edge Rule.** Every section after the hero opens with a 28px skim-coat edge: an SVG wave filled with that section's own ground, overlapping the section above by 27px. It is a smooth swept curve, never a torn or zigzag line.

**The Header Contact Rule.** The contact action sits in the header, top right, opposite the brand. There is no sticky bottom bar and no floating contact button.

## Elevation & Depth

Sections and panels are flat; depth is tonal (green against mud). Shadows exist only on physical objects the world would actually hold against a wall: the taped photo pins, the tape strips themselves, and the Facebook proof slab. Inside the wall canvas, the knife casts a soft drop shadow that lengthens when it lifts off between passes.

### Shadow Vocabulary
- **Pinned photo** (`0 14px 30px -12px rgba(22,39,31,.35), 0 2px 6px rgba(22,39,31,.12)`): a photo held off the wall by tape.
- **Tape** (`0 1px 3px rgba(22,39,31,.18)`): paper tape lying on the photo edge.
- **Proof slab** (`0 14px 28px -14px rgba(15,64,45,.7)`): green-tinted lift under the Facebook link.
- **Field focus halo** (`0 0 0 3px rgba(168,119,26,.28)`): a gold-deep ring on focused fields and chips; a state, not elevation.

**The Pinned Object Rule.** A shadow means something is physically fixed to the wall. Sections, text, rows, form fields and the sent panel never cast one.

## Shapes

Gently rounded, tool-made corners that grow with the object's size: 3px on the photo inside its mat, 6px on the pin mat and focus rings, 10px on fields, chips, the copy button and the composed message, 12px on buttons, 14px on the larger slabs (proof link, sent panel). Circles (`full`) are reserved for discs: the logo mark and seal, step numerals, the service-row arrow, the Facebook disc. On desktop the hero wall alone takes a 22px top-left corner where it meets the copy column.

Borders are 2px everywhere they exist. Photo pins sit slightly off true (-1.2deg, 1deg, -0.6deg) with two strips of joint tape crossing their top corners at roughly ±37deg; the tape carries a faint centre crease like real paper tape.

**The Hand-Hung Rule.** Pinned photos are always slightly rotated and always held by two strips of tape. Nothing else on the page is rotated.

## Components

### Buttons
- **Shape:** 12px corners, 56px minimum height, 0 22px padding, 2px border matching the fill, uppercase 800 label.
- **Gold (primary):** gold fill, night-green text. The primary action in the hero and the "Open Messenger" handoff. Hover (mouse only): `gold-bright`.
- **Line (secondary, on green only):** transparent with a gold 2px border and cream text. Hover: a faint gold wash.
- **Green (form submit):** green fill, cream text. Hover: `green-700` plus a 3px `gold-deep` outline offset 2px; the same outline marks keyboard focus.
- **Press:** 1px downward nudge on active; removed under reduced motion.
- **Hero pair:** the two hero buttons sit in an equal two-column grid (max 440px), so neither wraps on a phone.

### Header contact
"Message me" with the Messenger glyph in gold, cream 800 text, 44px tall target, top right. Hover underlines the label in gold. It is the only header action.

### Service rows
Full-width links set as large uppercase type, 76px minimum, separated by 2px `seam-line` rules above the first and under each row. The only affordance is the 46px arrow disc at the right end: resting `arrow-disc` with a green arrow; on hover it turns gold, the arrow goes night green, and it slides 3px right. Keyboard focus does the same and adds a 3px `gold-deep` ring around the disc. Each row links to the estimate form and pre-ticks its service.

**The Arrow-Only Rule.** A service row never gains an outline, box, background or shadow on hover or focus. The arrow disc carries the entire state; the row text and rules stay put.

### Steps
A numbered list on green: 52px gold discs with the counter in 900 night green, a title and a short cream-soft paragraph (40ch). On phones the disc sits left of the text (52px column, 16px gap); from 760px three columns with the disc on top.

### Taped photo pins
A white 8px mat with 6px corners, the photo or clip inside at 3:4 (the lead still at 4:5 full width on phones), pinned-photo shadow, slight rotation, two tape strips. Photos are not draggable or selectable. The walkthrough clip is muted, looped and inline, and plays only while on screen.

**The No Caption Rule.** Pinned photos carry no visible caption, label or overlay; descriptions live in alt text and aria-labels only.

### Facebook proof link
A green slab (14px corners, 18px 20px padding, proof-slab shadow) under the photo board: a 44px gold disc with the Facebook mark, an 800 1.25rem line, and a gold arrow pushed to the far right. Max 560px wide on desktop. Hover: `green-700`.

### Estimate form
- **Text fields:** fresh-coat fill, 2px `field-edge` border, 10px corners, 54px minimum (textarea 110px, vertical resize), 17px body text. Hover border `gold-deep`; focus border `gold-deep` with the field focus halo and no outline.
- **Chips:** visually hidden checkbox/radio inside a label; the visible face is a 48px fresh-coat rectangle (10px corners, 2px `field-edge`, 700 weight). Hover border `gold-deep`; keyboard focus adds the halo; checked fills green with cream text and keeps the `gold-deep` hover border.
- **Labels:** 800 weight above each field; "(optional)" and "(pick any)" in 500 `ink-soft` inline.
- **Errors:** an `error-ink` 700 line under the field and an `error-edge` border, shown only after a failed submit, tied to the field by `aria-describedby`.
- **Submit:** full-width green button.

### Sent-message panel
Appears under the form after submit: fresh-coat fill, 2px `seam-line` border, 14px corners, 20px padding. Green title, the composed message in a mud well (10px corners, 14px padding, pre-wrap, always selectable for press-and-hold copy), a full-width transparent copy button (2px `field-edge`, hover/focus border `gold-deep`), an `ink-soft` note, and a full-width gold "Open Messenger" button.

### Footer
Night-green ground, centered. The full 150px circular logo seal on a white disc, the tagline in gold 900 uppercase, the business name in cream-soft, then Facebook and Messenger links (44px targets, gold glyphs, gold underline on hover).

**The Footer Email Rule.** An email address may appear only in the footer, and only once the business publishes one. None exists, so none is shown.

### The wall (signature)
A drywall panel in the hero, `clamp(230px,36svh,320px)` tall on phones, 340px from 760px, filling the right column from 1024px. The canvas draws drywall paper with raking light and fibre, tapered sheet edges, two taped seams (vertical at 40% on phones, 48% wider; horizontal at 52%) and screw dimples on a stud grid. The gold knife (gold to gold-deep gradient blade, wet-mud leading edge, ferrule and handle) runs an unattended route: a first pass down each seam, then a wider feathering pass beside it, lifting between passes. Each pass stamps a blade-shaped quad with a feathered edge, lap ridges and drag streaks; wet grey mud (`rgb(204,201,193)`) dries toward `mud`. After two full routes the coat fades and the wall starts over. Touch or mouse takes the knife (the wall blocks page scroll and hides the cursor); control returns to the route after 2.2s idle. A bottom-right hint ("Drag to finish the wall") fades on first touch and returns as "Ready for paint." after about 600px of dragging. Tunables (`KNIFE`, `DRY`, `WET`, `FEATHER`, `AUTO_SPEED`, `RESET_LOOPS`, `IDLE_MS`, `LIFT_PX`, `REWARD_PX`) sit at the top of the first script; a CSS fallback paints taped seams if the canvas never runs.

### Motion
- State transitions: 0.2s on button and arrow colors, 0.15s on field and chip borders, 0.5s on the wall hint's opacity.
- Skim-coat edges: a 16-point smoothed double sine (amplitude 7, speed 0.9) per edge, phase-offset per section.
- Hover accents sit inside `@media (hover:hover)` so a tap never leaves an accent stuck on.

**The Still Frame Rule.** Under reduced motion the wall renders one still picture (the horizontal seam finished and dry, the knife resting on the vertical seam), the edges draw once and stop, the clip shows controls instead of autoplaying, and transforms and smooth scrolling are removed. Colors may still change state.

**The Off-Screen Rule.** Nothing animates off screen. The wall pauses when out of view or the tab is hidden, each edge animates only while intersecting, and the clip pauses when scrolled away.

## Do's and Don'ts

### Do:
- **Do** alternate green and mud grounds and open every new section with a skim-coat edge in its own ground color.
- **Do** keep the contact action in the header, top right.
- **Do** use `gold-deep` for any gold line, border or outline on mud or fresh-coat surfaces.
- **Do** put hover accents inside `@media (hover:hover)`.
- **Do** hold every photo up with two strips of joint tape, slightly rotated, with no caption.
- **Do** keep form inputs at 17px or larger and controls at 44px or taller.
- **Do** change the canvas `DRY_RGB` whenever `mud` changes.
- **Do** give every new animation a reduced-motion still frame and an off-screen pause.

### Don't:
- **Don't** add a sticky bottom bar or floating contact button.
- **Don't** show an email anywhere but the footer, and never an invented one.
- **Don't** add captions, labels or overlays to photos.
- **Don't** outline, box, fill or shadow a service row on hover or focus; the arrow disc carries the state.
- **Don't** use gold as decoration at rest on interactive elements in light sections; on mud it appears as a hover or focus response (the gold "Open Messenger" button is the one resting gold action there).
- **Don't** add a second interactive or animated set piece; the wall is the only one.
- **Don't** put shadows on sections, panels, rows or fields.
- **Don't** add a display webfont or italic emphasis.
