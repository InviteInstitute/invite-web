---
name: INVITE Research Software
description: The software index of the INVITE Institute, a deep teal tool rail beside full-width screenshots, in the institute site's own TheGem tokens.
colors:
  heading: "#3c3950"
  body: "#5f727f"
  muted: "#99a9b5"
  accent: "#00bcd4"
  lime: "#e7ff89"
  border: "#dfe5e8"
  subtle: "#f4f6f7"
  button-quiet: "#b6c6c9"
  footer: "#1c3947"
  rail-name: "#e6eaf0"
  rail-body: "#c9d6dd"
  rail-caption: "#9fb3bd"
  rail-scroll: "#3d5f6e"
  white: "#ffffff"
typography:
  rail-title:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "28px"
    fontWeight: 700
    lineHeight: "38px"
    letterSpacing: "1.4px"
  shot-title:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "34px"
    letterSpacing: "1.2px"
  rail-name:
    fontFamily: "Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: "24px"
  footer-heading:
    fontFamily: "Montserrat UltraLight, Montserrat, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: "30px"
    letterSpacing: "0.95px"
  shot-desc:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: "29px"
  body:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "25px"
  legal:
    fontFamily: "Source Sans Pro, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: "25px"
components:
  button-open:
    backgroundColor: "{colors.white}"
    textColor: "{colors.footer}"
    padding: "0 18px"
    height: "36px"
  button-open-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.footer}"
---

# Design System: INVITE Research Software

Every value here comes from `public/styles.css`, and the color names match its `:root` tokens. When the two disagree, the CSS wins and this file is out of date.

## Look

The page borrows its header, footer, fonts and colors from invite.illinois.edu, the institute's WordPress site on the TheGem theme. Montserrat 700 sets the uppercase headings, Source Sans Pro 400 and 700 set the text, and Montserrat UltraLight sets the footer headings. Corners are square, depth is flat and color is sparse. The deep teal `footer` color is the only dark ground, used by the rail and the footer. Cyan `accent` marks where you are and what you can follow, and `lime` is only the text selection, the skip link and the focus ring on the rail.

Uppercase Montserrat headings track at 5% of their font size. On phones the rail title drops to 24px/34px and screenshot titles to 21px/30px.

## Layout

The header is a 91px white bar with the logo left and the institute menu right. At 1000px and below it drops to 70px and the menu folds behind a toggle.

Below it sits a two-column grid. The left column is the 380px rail and the right column holds the screenshots, padded 56px. At 1180px the rail narrows to 320px and the screenshot column pads 36px. At 900px and below the grid becomes one column, the rail turns into a static block at the top, and everything pads 21px.

## Components

### Rail

A sticky block one viewport tall in `footer` teal. It holds the title, a one-line intro, one entry per tool and the source code links. Each entry has the tool name in `rail-name`, then an Open button and the host in `rail-caption` at 14px. The entry whose screenshot is in view gets a 5% white wash and an 8px cyan tab on the rail's right edge, driven by an IntersectionObserver. Above 900px wide every Open button must fit on screen without scrolling the rail, down to 1280x720.

### Open button

White, 36px tall, square, with teal Source Sans 700 text at 15px. It turns cyan on hover and has no icon.

### Screenshot

The section title, 16px of space, the screenshot at full column width (at most 1100px) in a 1px `border` frame, then the description 18px below it and a "Live at" host link 14px below that. The host link is `heading` 700 at 17px with a 2px cyan underline. Sections are 64px apart on each side of a 1px rule, 44px on phones.

### Footer

Teal ground with the NSF and IES logos, the funding disclaimer at 12px/25px in `muted`, a wall of partner logos, a search box for invite.illinois.edu and social links. On phones it stacks and centers.

## Motion

The cyan tab grows in over 0.35s, the Open button fades to cyan, and rail links scroll smoothly to their screenshot. All of it goes still under reduced motion.
