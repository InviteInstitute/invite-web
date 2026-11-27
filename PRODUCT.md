# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Two audiences, weighted equally:

- **Insiders launching a tool.** INVITE researchers and partner-school teachers who arrive to open the Learner Modeling Dashboard, the INVITE Agent, or the Pedagogical Agent Toolkit and leave. Getting to the right link fast matters most.
- **Outside evaluators.** NSF/IES reviewers, peer AI institutes, and the public checking what INVITE has built. A clear, credible account of each tool and its status matters most.

## Product Purpose

inviteai.org is the front door to the research software built and run by the INVITE Institute (NSF-IES National AI Institute for Innovative Intelligent Technologies for Education). It indexes each tool with a short description and a Live or Coming Soon status, and links out to the subdomain where it runs. Success is an insider reaching their tool in one click and an evaluator understanding what exists and what is live.

## Positioning

It is the software arm of an existing institute, not a separate product. It should read as part of invite.illinois.edu (the institute's WordPress site on the TheGem theme) while standing alone as a tools index with its own navigation.

## Operating Context

- Tools run on their own subdomains: dashboard.inviteai.org, agent.inviteai.org, patk.inviteai.org.
- The dashboard is used alongside VEXcode VR in classrooms, and the INVITE Agent alongside VEXcode VR and ZANY.
- The Pedagogical Agent Toolkit link sits behind a client-side password prompt (session-remembered).

## Capabilities and Constraints

- Plain static HTML and CSS served by nginx from `public/`. No build step, no framework, no runtime. Deploy is `git pull`, and Cloudflare sits in front.
- Assets (logos, partner logos, textures, fonts) are self-hosted under `public/`, copied from the institute site's WordPress backup, not hotlinked.
- The header carries the institute site's own menu (About, People, Research, Open Studies, INVITE Alliance, Publications) and a search link, all pointing to invite.illinois.edu. Below it, a sticky tool rail with every Open button sits beside full-width screenshots.

## Brand Commitments

- Visual identity is the institute site's: the INVITE logo, TheGem theme tokens (Montserrat headings, Source Sans Pro body, `#3c3950` headings, `#5f727f` body, `#00bcd4` accent, `#e7ff89` highlight), the `#1c3947` deep teal of the footer and tool rail, the cyan tab, and the footer with funding disclaimer, partner logos, search and social links.
- Funding disclaimer text (NSF and IES, Grant #2229612) must appear verbatim.

## Evidence on Hand

- The three tools, their descriptions, and their live/soon status are in `public/index.html`.
- Institute assets from the WordPress backup (`~/backup-20aug26/uploads/`): INVITE logo, NSF and IES logos, partner logos (Illinois, UF, NJIT, ETS, Oregon, VEX Robotics, Balance Studios), and the title-bar texture.
- Each tool has a screenshot of its real UI. The dashboard one shows synthetic students, never real ones. There are no usage numbers or testimonials. Do not fabricate them.

## Product Principles

1. One click to the tool: status and link come before anything decorative.
2. Indistinguishable in feel from invite.illinois.edu, so trust transfers.
3. Say only what is true: status badges reflect reality, and there are no invented claims.
4. Stay trivially maintainable: hand-editable static files.
