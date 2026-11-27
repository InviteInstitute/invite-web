---
version: 1
slug: "public-index-html"
primary_target: "public/index.html"
related_targets: []
---

# Surface: inviteai.org tools index (public/index.html)

Mode: Operate (primary: insiders launching a tool) with a Read layer for evaluators.
Job: reach the right tool in one click; understand what exists and what is live.
Constraints: static HTML/CSS, self-hosted assets, the institute's own header menu, PA Toolkit password prompt stays.
World: the institute's TheGem tokens (Montserrat, Source Sans, #3c3950, #00bcd4, #e7ff89, #1c3947) stay. The homepage-mirror layout was rejected ("this layout is bad"). Light touch, no slider.

## Direction contract

THESIS: A tool rail beside big screenshots. All three launch buttons stay on screen the whole time, and the screenshots get room to be read. Refuses the stacked list of small thumbnails beside text.

OWN-WORLD: White ground. A sticky 380px left rail in the footer's #1c3947 deep teal holds the tools, so the shell is one committed color that runs into the footer. Each tool has a Montserrat name, a one-line job and a solid #00bcd4 Open button with dark ink. The tool in view gets the institute's cyan tab (an 8px #00bcd4 bar) on the rail's right edge, where the title bar carried it. Detail column: screenshots at full column width in a 1px #dfe5e8 frame, no shadow, uppercase tracked Montserrat titles, Source Sans body. The #1c3947 footer stays as is.

STORY: Insiders see three Open buttons in the first viewport and leave in one click. Evaluators scroll the right column and read what each tool does from a screenshot they can actually see.

FIRST VIEWPORT at 1440x900: 91px header, unchanged. Below it a 380px rail on the left with "Research Software", a two-line intro, then three tool entries with Open buttons and Source Code links at the bottom. On the right, the dashboard screenshot at about 900px wide, then its title and description.

FORM: tool rail, structure 7 of 7 on the ranked list, seed:c2e8ac98375da308 (user locked it in the terminal, since the decision page could not reach them over SSH).

Signature move: the cyan tab follows the tool in view as the right column scrolls (IntersectionObserver), and clicking a rail name scrolls its section into view. It is static with reduced motion.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance
