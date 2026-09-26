---
name: INVITE Research Software
description: The software index of the INVITE Institute, built in the institute site's own TheGem page grammar.
colors:
  heading-ink: "#3c3950"
  body-slate: "#5f727f"
  muted-mist: "#99a9b5"
  signal-cyan: "#00bcd4"
  live-lime: "#e7ff89"
  rule-gray: "#dfe5e8"
  subtle-wash: "#f4f6f7"
  panel-gray: "#ededed"
  caption-slate: "#5a6c79"
  quiet-steel: "#b6c6c9"
  title-bar-plum: "#333144"
  footer-deep-teal: "#1c3947"
  paper-white: "#ffffff"
  error-red: "#c62828"
typography:
  display:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "36px"
    fontWeight: 700
    lineHeight: "53px"
    letterSpacing: "1.8px"
  headline:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 700
    lineHeight: "42px"
    letterSpacing: "1.4px"
  display-phone:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "36px"
    letterSpacing: "1.2px"
  headline-tablet:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "36px"
    letterSpacing: "1.2px"
  headline-phone:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: "32px"
    letterSpacing: "1.1px"
  title:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 700
    lineHeight: "30px"
    letterSpacing: "0.95px"
  title-phone:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: "26px"
    letterSpacing: "0.95px"
  footer-title:
    fontFamily: "Montserrat UltraLight, Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: "30px"
    letterSpacing: "0.95px"
  lead:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 300
    lineHeight: "37px"
  lead-phone:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 300
    lineHeight: "29px"
  body-large:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: "27px"
  body:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "25px"
  body-host:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: "25px"
  caption:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "21px"
  small:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: "24px"
  legal:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: "25px"
  label-nav:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: "25px"
  label-button:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    letterSpacing: "0.04em"
  label-status:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "11px"
    fontWeight: 700
    lineHeight: "18px"
    letterSpacing: "0.08em"
rounded:
  none: "0px"
spacing:
  gutter: "21px"
  xs: "8px"
  subtool: "18px"
  sm: "22px"
  row: "26px"
  md: "30px"
  lg: "40px"
  xl: "60px"
components:
  button-launch:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.heading-ink}"
    typography: "{typography.label-button}"
    rounded: "{rounded.none}"
    padding: "0 22px 0 24px"
    height: "44px"
  button-launch-hover:
    backgroundColor: "{colors.signal-cyan}"
    textColor: "{colors.heading-ink}"
  button-solid:
    backgroundColor: "{colors.heading-ink}"
    textColor: "{colors.paper-white}"
    rounded: "{rounded.none}"
    padding: "0 20px"
    height: "40px"
  button-solid-hover:
    backgroundColor: "{colors.signal-cyan}"
    textColor: "{colors.heading-ink}"
  button-quiet:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.body-slate}"
    rounded: "{rounded.none}"
    padding: "0 20px"
    height: "40px"
  status-live:
    backgroundColor: "{colors.live-lime}"
    textColor: "{colors.heading-ink}"
    typography: "{typography.label-status}"
    rounded: "{rounded.none}"
    padding: "3px 10px"
  status-soon:
    backgroundColor: "{colors.subtle-wash}"
    textColor: "{colors.body-slate}"
    typography: "{typography.label-status}"
    rounded: "{rounded.none}"
    padding: "3px 10px"
  input-text:
    backgroundColor: "{colors.subtle-wash}"
    textColor: "{colors.heading-ink}"
    rounded: "{rounded.none}"
    padding: "0 14px"
    height: "44px"
  input-text-focus:
    backgroundColor: "{colors.paper-white}"
  nav-link:
    textColor: "{colors.heading-ink}"
    typography: "{typography.label-nav}"
    padding: "0 15px"
  nav-link-hover:
    textColor: "{colors.signal-cyan}"
  tool-row:
    backgroundColor: "{colors.paper-white}"
    rounded: "{rounded.none}"
    padding: "26px 0"
  links-band:
    backgroundColor: "{colors.panel-gray}"
    rounded: "{rounded.none}"
    padding: "32px 40px 36px"
  links-band-caption:
    textColor: "{colors.caption-slate}"
    typography: "{typography.caption}"
---

# Design System: INVITE Research Software

## Overview

**Creative North Star: "A Page From the Institute's Own Site"**

This system is a faithful port of invite.illinois.edu, the INVITE Institute's WordPress site on the TheGem theme. Every surface should read as one more inner page of that site: a white header with the logo and a short uppercase menu, a dark lined title bar with a right-aligned title and a cyan tab, a white body of photo-paired rows closed by a full-width gray links band, and a deep teal footer carrying funding and partner logos. Trust transfers from the institute site because nothing here looks like a separate product.

The grammar is documentary, not app-like. Each top-level item sits in a two-column row beside one of the institute homepage's own carousel photos, whose torn paper edges and hex network overlay are baked into the raster; rows alternate the photo's side. Headings are uppercase Montserrat 700 with tracking, body is Source Sans Pro in slate gray, and the single lead paragraph is set light (300) and large. Corners are square everywhere, depth is flat, and color is sparse: cyan marks interaction and structure (button borders, the title tab, focus rings, link underlines), lime marks only what is live.

Motion is nearly absent by design. The one authored movement is the launch button filling cyan from the left while its arrow nudges up and right; everything else changes color at most.

**Key Characteristics:**
- White ground, photo-paired rows that alternate sides, square corners, no cards.
- Institute carousel photos with torn edges baked into the raster, never masked in CSS.
- Uppercase Montserrat 700 headings, letter-spacing equal to 5% of the font size.
- Cyan as the interaction and structure accent; lime reserved for "live" status and text selection.
- Dark textured title bar with an 18px cyan tab at the right edge.
- Full-width Panel Gray links band above a deep teal footer with Montserrat UltraLight headings and a square partner-logo wall.
- One motion: the launch-button fill.

## Colors

A cool, low-saturation slate-and-plum palette with one saturated cyan accent and one acid lime signal.

### Primary
- **Signal Cyan** (signal-cyan): TheGem's accent. Used as the 2px border of launch buttons and their hover/focus fill, the title-bar tab, the 2px focus ring, the input caret and focus border, links-band link underlines, and link text on the dark footer. Never used as text on white.

### Secondary
- **Live Lime** (live-lime): TheGem's highlight. Fills the "Live" status label and the text selection background. It means "available now" and nothing else.

### Neutral
- **Heading Ink** (heading-ink): all headings, nav links, launch-button text, links-band link text, bold spans in the lead, input text, and the solid dialog button fill.
- **Body Slate** (body-slate): running text, descriptions, host lines, the Coming Soon label text. On white only; it falls to 4.27:1 on Panel Gray.
- **Caption Slate** (caption-slate): Body Slate darkened for Panel Gray. Carries the captions under links-band links (4.65:1 on Panel Gray).
- **Muted Mist** (muted-mist): footer body text, the lock glyph beside "Password required", links-band list markers, and the "Coming Soon" dot. Never running text on white.
- **Rule Gray** (rule-gray): every 1px hairline (the rule between sub-items inside a row, the Coming Soon label border, input borders) and the 2px quiet button border.
- **Subtle Wash** (subtle-wash): Coming Soon label fill, resting input fill, scrollbar track.
- **Panel Gray** (panel-gray): the links band ground.
- **Quiet Steel** (quiet-steel): scrollbar thumb and the quiet button's hover border.
- **Title-Bar Plum** (title-bar-plum): base under the lined title texture image; the rendered bar reads near #222431.
- **Footer Deep Teal** (footer-deep-teal): footer ground and the browser theme color.
- **Paper White** (paper-white): page, header, and dialog ground; title and footer headings on dark.
- **Error Red** (error-red): inline form error text only.

### Named Rules
**The Lime Means Live Rule.** Lime fills only a status that is actually live (and text selection). It is never decoration and never a second accent.

**The Cyan Is Structure Rule.** Cyan appears as borders, tabs, underlines, rings, and fills behind dark ink. Text on white stays Heading Ink or Body Slate; cyan text belongs only on the dark footer.

**The Gray Ground Caption Rule.** Secondary text on Panel Gray is Caption Slate, never Body Slate. Every text color is checked against the ground it actually sits on.

## Typography

**Display Font:** Montserrat 700 (with Helvetica Neue, Arial)
**Body Font:** Source Sans Pro 300/400/700 (with Helvetica Neue, Arial)
**Footer Heading Font:** Montserrat UltraLight (with Montserrat, Helvetica Neue, Arial)

**Character:** Geometric, tracked, all-caps Montserrat carries structure and names; humanist Source Sans Pro carries reading. All faces are self-hosted copies of the ones TheGem ships on the institute site.

### Hierarchy
Responsive steps are listed with their breakpoint; tablet is 1100px and below, phone is 767px and below.
- **Display** (700, 36px/53px, 1.8px tracking, uppercase; phone 24px/36px at 1.2px): the page title in the dark title bar, right-aligned, white.
- **Headline** (700, 28px/42px, 1.4px tracking, uppercase; tablet 24px/36px at 1.2px; phone 22px/32px at 1.1px): a top-level tool title in its row, balanced wrapping.
- **Title** (700, 19px/30px, 0.95px tracking, uppercase; sub-items 17px/26px at phone): sub-item, links-band, and dialog headings.
- **Footer Title** (UltraLight, 19px/30px, 0.95px tracking, uppercase, white): footer section headings only.
- **Lead** (300, 24px/37px, max 40em; phone 20px/29px): the single introductory paragraph; bold spans inside it switch to Heading Ink 700.
- **Body Large** (400, 17px/27px, max 34em): tool descriptions; 16px/25px in sub-items and at phone.
- **Body** (400, 16px/25px): default text and links-band links.
- **Host** (400, 15px/25px): the plain hostname or lock line beside a launch button; also the inline form error.
- **Caption** (400, 14px/21px, Caption Slate): the line under each links-band link.
- **Small** (400, 13px/24px, max 460px): footer disclaimer text.
- **Legal** (400, 12px/25px): the footer copyright line.
- **Label** (Montserrat 700, uppercase): nav 14px untracked (13px at phone); buttons 14px at 0.04em (dialog buttons 13px); status 11px/18px at 0.08em; field labels 12px at 0.06em.

### Named Rules
**The Five-Percent Tracking Rule.** Every uppercase Montserrat heading tracks at exactly 5% of its font size (36px gets 1.8px, 28px gets 1.4px, 24px gets 1.2px, 22px gets 1.1px, 19px gets 0.95px). Labels use their own smaller em values; nav is untracked.

**The One Light Paragraph Rule.** Weight 300 is reserved for the lead paragraph. Everything else in Source Sans Pro is 400 or 700.

## Layout

A TheGem inner-page template. The header is full-bleed, 91px tall with 37px side padding (70px and 21px at phone), logo left at 132px wide (112px at phone) and nav right. The title bar is a full-bleed strip with 15px vertical padding (12px at phone) and the title right-aligned, with 62px right padding (34px at phone) clearing the cyan tab.

Content lives in a 1212px max-width container with 21px gutters. The body block is padded 50px top and 80px bottom (34px/60px at phone). The lead sits first; the rows start 30px below it (18px at phone).

Each top-level tool is a row: a two-column grid of equal halves, photo in one and the tool body in the other, vertically centered, with a 60px gap (36px at tablet) and 26px top and bottom padding. Odd rows put the photo first, even rows put it second. Rows are separated by whitespace, not rules. At phone the row collapses to one column with a 14px gap and 18px/26px padding; the photo always comes first and runs full-bleed by pulling out through the gutters.

Inside a tool body, the top-level head stacks the headline above its status label (10px apart). Description follows 8px below; the action line follows 22px below and wraps with 12px by 22px gaps, pairing the launch button with a host line. At phone the action line stacks, button first and host line beneath (10px apart). A tool with sub-items lists them below its head, each preceded by a 1px Rule Gray line with 18px above and below; sub-item heads keep the title and status inline (8px by 18px gaps), and their action line sits 16px below.

The links band closes the content 44px below the last row (30px at phone): full container width, two columns at 1fr to 1.3fr with 30px by 60px gaps and 32px 40px 36px padding; equal columns with 30px 32px 34px padding at tablet; one column with a 28px gap and 26px 22px 28px padding at phone.

The footer is a three-column grid (funding, partner wall, connect) with 40px by 70px gaps, collapsing to two columns at tablet (connect spans below) and to one centered column at phone.

### Named Rules
**The Alternating Photo Rule.** Every top-level tool gets exactly one institute photo at half the row, and the photo's side alternates row by row. At phone the photo leads, full-bleed.

## Elevation & Depth

Flat. Depth comes from tonal grounds (white page, dark textured title bar, Panel Gray links band, deep teal footer), 1px hairlines, and the photographs themselves, not shadows. The only shadow in the system belongs to the modal dialog, which floats above a deep-teal scrim at 60% opacity.

### Shadow Vocabulary
- **Modal lift** (`box-shadow: 0 18px 50px rgba(24, 24, 40, .28)`): the password dialog only.

### Named Rules
**The Ruled Not Raised Rule.** Separate content with whitespace, 1px Rule Gray lines, and tonal grounds. A shadow is permitted only on a modal that sits above a scrim.

## Shapes

Square corners everywhere (0px): buttons, inputs, status labels, the links band, the dialog, partner logos. The only curves are the 6px status dots and the rounded ends of icon strokes. Borders come in two weights: 1px hairlines for structure and fields, 2px for the launch button, dialog buttons, the active nav box, and the focus ring. The title bar's cyan tab is a signature slab: 18px wide (12px at phone), flush to the right edge, inset 28px top and bottom from the bar (21px at phone).

The one irregular silhouette is the photo: the institute's torn paper edge and hex network line art live inside the raster on a near-white ground, so the photo sits on the white page with no frame, radius, mask, or shadow.

### Named Rules
**The Edge Lives in the Raster Rule.** Photo edges and overlays come baked into the institute's own images (800w and 1200w WebP). CSS never masks, clips, rounds, frames, or shadows a photo.

## Components

### Buttons
Outlined, uppercase, and quiet until touched.
- **Shape:** square (0px), 44px tall, 2px Signal Cyan border.
- **Launch (primary):** transparent over white, Heading Ink label (14px Montserrat 700, 0.04em), followed by a 16px up-right arrow stroke icon with a 10px gap. This is a deliberate accessibility adaptation of TheGem's cyan-text outline button.
- **Hover / Focus:** Signal Cyan fills from the left (background-size 0% to 100% over 0.45s on cubic-bezier(.16, 1, .3, 1)) while the arrow translates 2px up and right on the same curve. Label stays Heading Ink. This is the only authored motion in the system.
- **Solid (dialog confirm):** Heading Ink fill, white label, 40px tall, 13px label; on hover fills Signal Cyan with Heading Ink text (0.2s color transition).
- **Quiet (dialog cancel):** white fill, 2px Rule Gray border, Body Slate label; on hover the border shifts to Quiet Steel and the label to Heading Ink.

### Status Labels
- **Style:** square, 3px by 10px padding, 11px uppercase Montserrat 700 at 0.08em, led by a 6px round dot in the label color.
- **Live:** Live Lime fill, Heading Ink text and dot.
- **Coming Soon:** Subtle Wash fill, 1px Rule Gray border, Body Slate text, Muted Mist dot.

### Tool Rows (Signature)
- **Structure:** photo half and body half, alternating sides, as set out in Layout. Not a card: no ground, border, radius, or shadow.
- **Photo:** an institute carousel raster, full column width, served at 800w and 1200w.
- **Head:** top-level heads stack Headline over status; sub-item heads keep Title and status on one line.
- **Sub-items:** divided by a 1px Rule Gray line; descriptions drop to 16px/25px.
- **Action line:** launch button plus a Body Slate host line (15px); a gated tool swaps the hostname for a 13px Muted Mist lock stroke icon and "Password required". Stacks at phone.

### Links Band
- **Style:** Panel Gray ground, square, full container width, two columns, Title-role headings.
- **Lists:** each item is indented 18px behind a Muted Mist » marker, TheGem's own list convention, with 10px between items. Links are Heading Ink with a 1px Signal Cyan underline at 4px offset, thickening to 2px on hover (0.15s), the accessibility adaptation of TheGem's cyan links.
- **Captioned list:** a Caption Slate line under each link.
- **Inline list:** items flow on one wrapping line with 10px by 30px gaps, each keeping its » marker.

### Inputs / Fields
- **Style:** square, 44px tall, 1px Rule Gray border, Subtle Wash fill, Heading Ink text, cyan caret, 14px horizontal padding. Label above in 12px uppercase Montserrat 700.
- **Focus:** border turns Signal Cyan and fill turns white (0.15s); no outline ring on the input itself.
- **Error:** message below in Error Red at 15px.

### Navigation
- **Style:** uppercase Montserrat 700 at 14px (13px at phone), Heading Ink, 15px horizontal padding (2px at phone), 6px between items.
- **States:** hover turns the label Signal Cyan (0.2s); the current page is boxed by a 2px Heading Ink border and does not change color on hover. At phone the current-page item is hidden, leaving only outbound links.

### Title Bar (Signature)
Full-bleed dark lined texture over Title-Bar Plum, white Display title right-aligned, and the Signal Cyan tab at the right edge. Every page opens with it.

### Footer (Signature)
Footer Deep Teal ground, Muted Mist small text, cyan links underlined on hover, white Footer Title headings, funder logos, a grid of 73px square partner logos (64px at phone) with 10px gaps, and white 20px social icons that turn cyan on hover.

## Do's and Don'ts

### Do:
- **Do** track every uppercase Montserrat heading at 5% of its font size.
- **Do** pair each top-level tool with one institute photo at half the row, alternating sides, and lead with the photo full-bleed at phone.
- **Do** use the institute's own photos with their torn edges and hex overlay baked into the raster.
- **Do** separate sub-items with 1px Rule Gray hairlines and keep every corner square (0px).
- **Do** reserve Live Lime for statuses that are actually live.
- **Do** keep Signal Cyan to borders, tabs, underlines, focus rings, and fills behind Heading Ink; on white, text stays Heading Ink or Body Slate.
- **Do** show focus with the 2px Signal Cyan outline at 3px offset.
- **Do** open every page with the white header and the textured title bar with its cyan tab, and close it with the deep teal footer.
- **Do** keep text at 4.5:1 contrast or better against its actual ground; on Panel Gray, secondary text is Caption Slate.

### Don't:
- **Don't** use rounded tiles, pill badges, or shadowed cards; tools are photo-paired rows, not boxes.
- **Don't** mask, clip, round, frame, or shadow a photo in CSS; the edge treatment belongs to the raster.
- **Don't** add motion beyond the launch-button fill and arrow nudge; other state changes are color-only.
- **Don't** set cyan text on white or light grounds.
- **Don't** use weight 300 outside the lead paragraph.
- **Don't** add shadows outside the modal dialog.
