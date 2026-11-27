---
name: INVITE Research Software
description: The software index of the INVITE Institute, a deep teal tool rail beside full-width screenshots, in the institute site's own TheGem tokens.
colors:
  heading-ink: "#3c3950"
  body-slate: "#5f727f"
  caption-slate: "#5a6c79"
  muted-mist: "#99a9b5"
  signal-cyan: "#00bcd4"
  live-lime: "#e7ff89"
  footer-deep-teal: "#1c3947"
  rail-name: "#e6eaf0"
  rail-body: "#c9d6dd"
  rail-caption: "#9fb3bd"
  rule-gray: "#dfe5e8"
  subtle-wash: "#f4f6f7"
  quiet-steel: "#b6c6c9"
  paper-white: "#ffffff"
  error-red: "#c62828"
typography:
  display:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 700
    lineHeight: "38px"
    letterSpacing: "1.4px"
  display-phone:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "34px"
    letterSpacing: "1.2px"
  headline:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "34px"
    letterSpacing: "1.2px"
  headline-phone:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "21px"
    fontWeight: 700
    lineHeight: "30px"
    letterSpacing: "1.05px"
  title:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 700
    lineHeight: "30px"
    letterSpacing: "0.95px"
  rail-name:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: "24px"
  footer-title:
    fontFamily: "Montserrat UltraLight, Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: "30px"
    letterSpacing: "0.95px"
  intro:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: "26px"
  body-large:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: "29px"
  body-large-phone:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: "27px"
  link-host:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
  body:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "25px"
  body-small:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: "22px"
  caption:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
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
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 700
rounded:
  none: "0px"
  field: "3px"
spacing:
  gutter: "21px"
  rail-edge-tablet: "28px"
  rail-edge: "40px"
  shots-edge-tablet: "36px"
  shots-edge: "56px"
  shot-gap-phone: "44px"
  shot-gap: "64px"
components:
  rail:
    backgroundColor: "{colors.footer-deep-teal}"
    textColor: "{colors.rail-body}"
    width: "380px"
  rail-tool:
    textColor: "{colors.rail-body}"
    typography: "{typography.body-small}"
    padding: "22px 40px 24px"
  button-open:
    backgroundColor: "{colors.paper-white}"
    textColor: "{colors.footer-deep-teal}"
    typography: "{typography.label-button}"
    rounded: "{rounded.none}"
    padding: "0 18px"
    height: "36px"
  button-open-hover:
    backgroundColor: "{colors.signal-cyan}"
    textColor: "{colors.footer-deep-teal}"
  link-host:
    textColor: "{colors.heading-ink}"
    typography: "{typography.link-host}"
  link-host-hover:
    textColor: "{colors.footer-deep-teal}"
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
  input-text:
    backgroundColor: "{colors.subtle-wash}"
    textColor: "{colors.heading-ink}"
    rounded: "{rounded.none}"
    padding: "0 14px"
    height: "44px"
  input-search:
    backgroundColor: "{colors.subtle-wash}"
    textColor: "{colors.heading-ink}"
    rounded: "{rounded.field}"
    padding: "6px 44px 6px 10px"
    height: "39px"
  nav-link:
    textColor: "{colors.heading-ink}"
    typography: "{typography.label-nav}"
    padding: "0 15px"
  nav-link-hover:
    textColor: "{colors.signal-cyan}"
---

# Design System: INVITE Research Software

## Overview

**Creative North Star: "The Tool Rail"**

The page is a launcher first. A sticky deep teal rail on the left holds every tool with its Open button, so all of them stay on screen while the right column scrolls through big screenshots. The rail is the footer's own deep teal carried up the page, which makes the shell one committed color that runs into the footer at the bottom.

The tokens come from invite.illinois.edu, the institute's WordPress site on the TheGem theme. Its header menu and its footer stay as they are, Montserrat 700 sets the uppercase headings, Source Sans Pro sets the text, and the institute's cyan tab now sits on the rail's right edge beside the tool in view. Corners are square, depth is flat, and color is sparse. Cyan marks where you are and what you can follow. Lime is only the text selection and the skip link.

Motion is small and functional. The cyan tab grows in beside the tool in view, the Open button turns cyan on hover, and clicking a rail name scrolls smoothly to its screenshot. All of it goes static under reduced motion.

**Key Characteristics:**
- The institute's own white header menu, linked to invite.illinois.edu, with a search link.
- A sticky 380px Footer Deep Teal rail with the page title, a short intro, one entry per tool and the source code links under the list.
- A plain white Open button with deep teal text in every rail entry.
- An 8px cyan tab on the rail's right edge that follows the screenshot in view.
- Full-width screenshots in a 1px Rule Gray frame, each under its title and followed by a description and a "Live at" line with the underlined host.
- The deep teal footer, with funder logos, the disclaimer, the partner wall, a search box and social links.

## Colors

The institute's palette. Slate and ink neutrals on white, one deep teal shell, one cyan accent, one lime signal.

### Primary
- **Signal Cyan** (signal-cyan): the Open button hover, the rail's current-tool tab, the underline under host links and source links, footer links, the search button icon, the focus ring on white and the input caret.

### Secondary
- **Live Lime** (live-lime): the skip link and the text selection background. On the rail it is also the focus ring color.

### Neutral
- **Footer Deep Teal** (footer-deep-teal): the rail and the footer ground, the browser theme color, and the host link's hover color.
- **Rail Name** (rail-name): tool names and source links on the rail (10.1:1).
- **Rail Body** (rail-body): the rail's one-line intro (8.2:1).
- **Rail Caption** (rail-caption): host lines beside the Open buttons and the "Source code" label (5.6:1).
- **Heading Ink** (heading-ink): screenshot titles, host links, nav links, input text and the solid dialog button.
- **Body Slate** (body-slate): screenshot descriptions and dialog text. On white only (5.0:1).
- **Caption Slate** (caption-slate): the "Password required" note under a host link.
- **Muted Mist** (muted-mist): footer body text (5.0:1 on deep teal). This is the institute footer's own text color, kept as a brand commitment.
- **Rule Gray** (rule-gray): screenshot frames, the rules between screenshots, the line under the header and input borders.
- **Subtle Wash** (subtle-wash): input fills and the scrollbar track.
- **Quiet Steel** (quiet-steel): the page scrollbar thumb and the quiet button's hover border.
- **Paper White** (paper-white): page, header and dialog ground, the rail title and footer headings.
- **Error Red** (error-red): inline form error text only.

Two white tints work on the rail without their own tokens. Hairlines between rail entries are white at 10%, and the current entry gets a white wash at 5%.

### Named Rules
**The No Badge Rule.** Every tool on the page is live, so no tool wears a status badge. The "Live at" line says it in words. Add a status label only when tools differ in status.

**The Cyan On Dark Rule.** Cyan text appears only on deep teal, where it reads at 5.3:1. On white, cyan is a fill, a tab, an underline or a focus ring. The one exception is the header menu's hover color, which the institute site sets that way.

## Typography

**Display Font:** Montserrat 700 (with Helvetica Neue, Arial)
**Body Font:** Source Sans Pro 300/400/700 (with Helvetica Neue, Arial)
**Footer Heading Font:** Montserrat UltraLight (with Montserrat, Helvetica Neue, Arial)

All faces are self-hosted copies of the ones TheGem ships on the institute site. Montserrat is the institute's committed heading face and stays.

### Hierarchy
- **Display** (700, 28px/38px, 1.4px tracking, uppercase, white, phone 24px/34px at 1.2px): the rail title "Research Software".
- **Headline** (700, 24px/34px, 1.2px tracking, uppercase, Heading Ink, phone 21px/30px at 1.05px): a screenshot title.
- **Title** (700, 19px/30px, 0.95px tracking, uppercase): the dialog heading.
- **Rail Name** (700, 17px/24px, sentence case): a tool name in the rail.
- **Footer Title** (UltraLight, 19px/30px, 0.95px tracking, uppercase, white): footer headings.
- **Intro** (400, 17px/26px): the rail's one-line intro, "Built and run by the INVITE Institute."
- **Body Large** (400, 18px/29px, 66ch max, phone 17px/27px): screenshot descriptions.
- **Host Link** (700, 17px): the underlined hostname under a description.
- **Body** (400, 16px/25px): default text and dialog copy.
- **Body Small** (400, 15px/22px): source links and the form error.
- **Caption** (400, 14px): the host line beside an Open button.
- **Legal** (400, 12px/25px): the footer disclaimer and copyright line.
- **Label**: nav in Montserrat 700 uppercase at 14px untracked (13px at tablet), dialog buttons in Montserrat 700 uppercase 13px at 0.04em, dialog field labels 12px at 0.06em. The Open button is Source Sans 700 at 15px in sentence case.

### Named Rules
**The Five-Percent Tracking Rule.** Every uppercase Montserrat heading tracks at 5% of its font size, at every breakpoint. Nav and labels use their own values.

## Layout

The header is the institute's 91px white bar with 37px side padding, logo left at 132px, menu right. At 1000px and below it drops to 70px, the logo to 112px, and the menu folds behind a toggle into a white drop-down.

Under the header, a 1px Rule Gray line opens a two-column grid. The left column is the 380px rail, the right column holds the screenshots. The rail's inner block is sticky at the top and exactly one viewport tall, with 44px top and 32px bottom padding and a thin scrollbar if it ever overflows. Its contents sit 40px from the edges. The tool list starts 36px under the intro, and the source code links follow the list 40px below it.

The screenshot column is padded 56px on the sides, 56px on top and 110px at the bottom. Each section is at most 1100px wide. A screenshot fills the column, its text block starts 26px below, and the next section follows after 64px, a 1px Rule Gray rule and 64px more. Sections keep 32px of scroll margin so a rail click lands them clear of the top.

The footer is a 1212px grid of 6, 4 and 2 parts: funding (logos, heading, disclaimer, padded 77px left and 78px right), the partner wall (71px squares, 10px gaps, 4 across) and a centered search and connect column. The copyright line sits 70px below, centered.

### Breakpoints
At 1180px and below the rail narrows to 320px with 28px edges, the screenshot column pads 36px, and the footer's search column moves under the other two. At 1000px the header menu folds. At 900px and below the grid becomes one column, the rail becomes a static block at the top with 21px edges, the cyan tab and current-tool wash switch off, the screenshot column pads 21px, and sections sit 44px apart on each side of the rule. At 767px the rail title and screenshot titles step down, and the footer stacks and centers.

### Named Rules
**The Every Button Fits Rule.** Above 900px wide, all Open buttons must be on screen without scrolling the rail, down to a 1280x720 screen. Rail entries carry only a name and a launch row so they fit without a special short-screen layout.

## Elevation & Depth

Flat. Depth comes from the one deep teal shell against white, from tonal tints on the rail and from 1px rules. Screenshots carry a frame and no shadow. Two shadows exist, both on elements that float over the page. The password dialog has `0 18px 50px rgba(24, 24, 40, .28)` over a 60% deep teal scrim, and the folded menu has `0 12px 24px rgba(28, 57, 71, .12)`.

## Shapes

Square corners everywhere, except the footer search field, which keeps the institute's 3px radius. Screenshots have a 1px Rule Gray frame and nothing else. The cyan tab is a plain 8px bar the full height of the rail entry.

## Components

### Rail Tool Entry
A tool name in Rail Name type that links to its screenshot, then a launch row 12px down with the Open button and a Rail Caption host line (or "Password required"). Entries are 22px top and 24px bottom, with white 10% hairlines above and below. The name turns white on hover and when its entry is current.

### Current Tool Tab
The entry whose screenshot is in view gets a white 5% wash and an 8px Signal Cyan bar on the rail's right edge. An IntersectionObserver watches the screenshot sections with a `-45% 0px -50% 0px` root margin, so the tab follows whichever section crosses the middle of the viewport, and the current name carries `aria-current="location"`. The bar grows from 0 to 8px over 0.35s and the wash fades in over 0.3s, both on `cubic-bezier(.16, 1, .3, 1)`. Without IntersectionObserver the first entry stays current.

### Open Button
Solid Paper White, 36px tall, square, with Footer Deep Teal text in Source Sans 700 at 15px. It says "Open" and nothing else, with no icon. Hover fills it Signal Cyan. Focus inside the rail is a 2px lime outline at 3px offset.

### Screenshot
The real tool at full column width in a 1px Rule Gray frame. The Headline comes first with 16px under it, then the figure, then the description 18px under the figure and the "Live at" line 14px under that. The text block stops at 66ch.

### Host Link
The line reads "Live at" in Body Slate, then the hostname in Heading Ink 700 at 17px with a 2px Signal Cyan underline at 4px offset, and no icon. For the Toolkit it adds "It asks for a password." Hover turns the text Footer Deep Teal and the underline Heading Ink.

### Source Code Links
Under the tool list, a 14px Rail Caption label in sentence case over the repository links in Rail Name at 15px/24px, underlined in cyan at 60% with 3px offset. Hover turns the text white and the underline full cyan.

### Navigation
Uppercase Montserrat 700 at 14px (13px at tablet), Heading Ink, cyan on hover. The search icon links to the footer search form.

### Footer
Footer Deep Teal ground. NSF and IES logos, the "Funding and Disclaimer" heading and the verbatim disclaimer at 12px/25px in Muted Mist with cyan links. The partner wall. A "Search" heading over a 162px search field that submits to invite.illinois.edu, then "Connect" over white 20px social icons that turn cyan on hover.

### Inputs and Dialog
The password dialog is 420px wide with 30px padding. It keeps its square 44px field (Rule Gray border, Subtle Wash fill, cyan caret, cyan border and white fill on focus), the Error Red message, a solid Heading Ink confirm button that turns cyan with ink text on hover, and a quiet white cancel button with a Rule Gray border.

## Do's and Don'ts

### Do:
- **Do** keep every Open button on screen in the rail at desktop widths, down to 1280x720.
- **Do** carry Footer Deep Teal as the only dark ground, on the rail and the footer.
- **Do** track uppercase Montserrat headings at 5% of the font size.
- **Do** keep icons, badges and arrows off the launch controls. The words carry it.
- **Do** show focus with a 2px outline at 3px offset, cyan on white and lime on the rail.
- **Do** use screenshots of the real tools, with synthetic data where students would show.

### Don't:
- **Don't** add the homepage slider or other heavy pieces the user did not ask for.
- **Don't** shrink screenshots into thumbnails beside text. They take the full column.
- **Don't** use rounded tiles, pill badges or shadowed cards.
- **Don't** set cyan text on white outside the header menu's hover state.
- **Don't** add motion beyond the tab, color fades and smooth scrolling, and keep all of it off under reduced motion.
