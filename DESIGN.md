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
    fontSize: "28px"
    fontWeight: 700
    lineHeight: "42px"
    letterSpacing: "1.4px"
  headline:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "36px"
    letterSpacing: "1.2px"
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
    lineHeight: "31px"
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
  field: "3px"
spacing:
  gutter: "21px"
  edge: "40px"
  xs: "8px"
  sm: "20px"
  md: "30px"
  lg: "40px"
  xl: "50px"
components:
  link-arrow:
    textColor: "{colors.signal-cyan}"
    typography: "{typography.lead}"
  link-arrow-hover:
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
  tool-row:
    backgroundColor: "{colors.paper-white}"
    rounded: "{rounded.none}"
    padding: "40px 0 0"
  sidebar:
    backgroundColor: "{colors.panel-gray}"
    rounded: "{rounded.none}"
    padding: "20px 20px 30px"
---

# Design System: INVITE Research Software

## Overview

**Creative North Star: "The Institute Homepage, With the Tools in It"**

The page mirrors the homepage of invite.illinois.edu, the INVITE Institute's WordPress site on the TheGem theme. It keeps that page's header menu, its two-line title bar, its wide text column beside a gray sidebar, and its footer. The homepage's photo slider is left out on purpose, because the user asked for a light touch. Trust transfers from the institute site because the page looks like one more page of it.

Headings are uppercase Montserrat 700 with tracking, body text is Source Sans Pro in slate gray, and the lead paragraph and launch links are set light (300) and large, the way the homepage sets its intro and its ► links. Corners are square, depth is flat, and color is sparse. Cyan is the link color, lime marks only what is live.

There is no authored motion. Links and icons change color on hover, nothing moves.

**Key Characteristics:**
- The institute's own header menu, linked to invite.illinois.edu, with a search link.
- A dark textured title bar with a light "INVITE Institute" line over the uppercase title, both left-aligned at 40px, and an 18px cyan tab at the right edge.
- A 2/3 text column with the lead and the tools, beside a Panel Gray sidebar with » lists.
- Each tool is a screenshot beside its name, Live label, description and ► launch link, with 1px rules between tools.
- The deep teal footer, with funder logos, the disclaimer, the partner wall, a search box and social links.

## Colors

The homepage's palette. Slate and plum neutrals, one cyan accent, one lime signal.

### Primary
- **Signal Cyan** (signal-cyan): TheGem's link color. Launch links, sidebar links, footer links, the search button icon, the title-bar tab, the focus ring and the input caret.

### Secondary
- **Live Lime** (live-lime): fills the "Live" status label and the text selection background. It means "available now" and nothing else.

### Neutral
- **Heading Ink** (heading-ink): headings, nav links, bold spans in the lead, input text, link hover color, and the solid dialog button fill.
- **Body Slate** (body-slate): running text, descriptions and the ► marks. On white only.
- **Caption Slate** (caption-slate): host lines and the notes under sidebar links (4.65:1 on Panel Gray).
- **Muted Mist** (muted-mist): footer body text and the lock icon beside "Password required".
- **Rule Gray** (rule-gray): the 1px rules between tools, screenshot borders and input borders.
- **Subtle Wash** (subtle-wash): input fills and the scrollbar track.
- **Panel Gray** (panel-gray): the sidebar ground.
- **Quiet Steel** (quiet-steel): scrollbar thumb and the quiet button's hover border.
- **Title-Bar Plum** (title-bar-plum): base under the lined title texture image.
- **Footer Deep Teal** (footer-deep-teal): footer ground and the browser theme color.
- **Paper White** (paper-white): page, header and dialog ground, title-bar and footer headings.
- **Error Red** (error-red): inline form error text only.

### Named Rules
**The Lime Means Live Rule.** Lime fills only a status that is actually live, and text selection. It is never decoration.

**The Inherited Link Rule.** Cyan link text on white (2.3:1) and on Panel Gray (2.0:1) is below WCAG AA. The institute site sets its links this way, and this page mirrors it on purpose. Do not spread cyan text to anything that is not a link.

## Typography

**Display Font:** Montserrat 700 (with Helvetica Neue, Arial)
**Body Font:** Source Sans Pro 300/400/700 (with Helvetica Neue, Arial)
**Footer Heading Font:** Montserrat UltraLight (with Montserrat, Helvetica Neue, Arial)

All faces are self-hosted copies of the ones TheGem ships on the institute site.

### Hierarchy
Breakpoints are 1180px (tablet), 1000px (menu folds), 900px (sidebar drops below) and 767px (phone).
- **Title excerpt** (300, 24px/37px, white; phone 20px/30px): the "INVITE Institute" line in the title bar.
- **Display** (700, 28px/42px, 1.4px tracking, uppercase, white; phone 24px/36px at 1.2px): the page title.
- **Headline** (700, 24px/36px, 1.2px tracking, uppercase; phone 22px/32px at 1.1px): a tool name.
- **Title** (700, 19px/30px, 0.95px tracking, uppercase): sidebar and dialog headings.
- **Footer Title** (UltraLight, 19px/30px, 0.95px tracking, uppercase, white): footer headings.
- **Lead** (300, 24px/37px; phone 20px/31px): the intro paragraph. Bold spans switch to Heading Ink 700.
- **Launch link** (300, 24px/37px, cyan; phone 21px/32px): the ► link under each tool.
- **Body Large** (400, 17px/27px; phone 16px/25px): tool descriptions.
- **Body** (400, 16px/25px): sidebar links and default text.
- **Host** (400, 15px): the hostname or lock line under a launch link, and sidebar notes.
- **Legal** (400, 12px/25px): the footer disclaimer and copyright line.
- **Label** (Montserrat 700, uppercase): nav 14px untracked, status 11px/18px at 0.08em, dialog labels 12px at 0.06em.

### Named Rules
**The Five-Percent Tracking Rule.** Every uppercase Montserrat heading tracks at 5% of its font size. Nav and labels use their own values.

## Layout

The homepage's full-width template. The header is 91px tall with 37px side padding, logo left at 132px, menu right. Each menu item has 15px padding inside 3px, and the search icon closes the row. At 1000px and below the header drops to 70px, the logo to 112px, and the menu folds behind a toggle into a white drop-down.

The title bar is full-bleed with 25px vertical padding. The excerpt and the title sit at x=40, 15px apart. The cyan tab is 18px wide, 34px from the top and 45px from the bottom of the bar (12px wide and 30px from both at 900px and below).

The body block is padded 50px top and 120px bottom. The content row runs edge to edge with 40px left and 19px right padding, a 2/3 main column and a 1/3 sidebar with a 21px gap. In the main column, each tool starts 40px below the one before it, after a 1px Rule Gray rule and 40px of padding. A tool is two equal columns, screenshot and body, with a 40px gap. At 1180px and below the screenshot stacks above the body. At 900px and below the sidebar drops under the tools.

The footer is a 1212px grid of 6, 4 and 2 parts: funding (logos, heading, disclaimer, padded 77px left and 78px right), the partner wall (71px squares, 10px gaps, 4 across) and a centered search and connect column. The copyright line sits 70px below, centered. At 1180px the search column moves under the other two, and at 767px everything stacks and centers.

## Elevation & Depth

Flat, like the original. Depth comes from tonal grounds and 1px rules. Two shadows exist. The modal dialog has `0 18px 50px rgba(24, 24, 40, .28)` over a 60% deep teal scrim, and the folded phone menu has `0 12px 24px rgba(28, 57, 71, .12)`.

## Shapes

Square corners everywhere, except the footer search field, which keeps the original's 3px radius. Screenshots have a 1px Rule Gray border and nothing else. The status dot is the only circle.

## Components

### Launch Links
A ► mark in Body Slate, then the link in cyan at the lead's size and weight, the way the homepage sets "Read more about our mission". Hover and focus turn the link Heading Ink. The host line sits under it, indented to line up with the link text.

### Status Labels
Square, 3px by 10px padding, 11px uppercase Montserrat 700 at 0.08em, led by a 6px round dot. Live is Live Lime with Heading Ink text.

### Tool Rows
Screenshot and body, as set out in Layout. No card, ground or shadow. The body stacks the Headline, the Live label (10px below), the description (12px below), the launch link (14px below) and the host line.

### Sidebar
Panel Gray, 20px padding, a Title heading, then a » list. Each item is indented 19px behind a Body Slate » with 11px between items. Links are cyan, with a Caption Slate note under each.

### Navigation
Uppercase Montserrat 700 at 14px (13px at tablet), Heading Ink, cyan on hover. The search icon links to the footer search form.

### Footer
Footer Deep Teal ground. NSF and IES logos, the "Funding and Disclaimer" heading and the verbatim disclaimer at 12px/25px in Muted Mist with cyan links. The partner wall. A "Search" heading over a 162px search field that submits to invite.illinois.edu, then "Connect" over white 20px social icons that turn cyan on hover.

### Inputs and Dialog
The password dialog keeps its square 44px field (Rule Gray border, Subtle Wash fill, cyan caret, cyan border on focus), Error Red message, a solid Heading Ink confirm button and a quiet cancel button.

## Do's and Don'ts

### Do:
- **Do** check every change against a screenshot of invite.illinois.edu at the same width.
- **Do** track uppercase Montserrat headings at 5% of the font size.
- **Do** reserve Live Lime for statuses that are actually live.
- **Do** show focus with the 2px Signal Cyan outline at 3px offset.
- **Do** use screenshots of the real tools, with synthetic data where students would show.

### Don't:
- **Don't** add the homepage slider or other heavy pieces the user did not ask for.
- **Don't** use rounded tiles, pill badges or shadowed cards.
- **Don't** add motion. Hover states change color only.
- **Don't** use cyan text for anything that is not a link.
