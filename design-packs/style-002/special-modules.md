# FeedHive-specific modules

These capabilities extend the existing Style 001 pack rather than squeezing FeedHive into its component list.

## Rocking integration matrix
Three rows of nine cell positions, including blank cells. Desktop cells153px/gap26px; tablet133px/gap20px; mobile86px/gap10px. The second row is staggered horizontally. Each row translates −10px to+10px over16 seconds ease-in-out; phases0/−4.5/−9 seconds. Two white gradient masks rotate −23°/+23°, covering the wide overflow. This is a rocking matrix, not an endless marquee or user-controlled horizontal scroller.

## Dense feature wall
Desktop uses ten columns and112px rows, with blank outer rows. Four central cards occupy columns4–5 /6–7 and rows3–4 /5–6. The reconstructed grid retains44 supporting feature cells, not only four generic cards. Main card glow is radial at50%100%, ending transparent at72%:
- pink rgba(244,161,189,.28)
- lilac rgba(222,196,255,.32)
- yellow rgba(254,214,98,.28)
- green rgba(174,223,184,.28)

Measured card shadow:0 24px 60px rgba(66,74,119,.08); hover0 30px 68px rgba(66,74,119,.14), scale1.01. Small corner marks emphasize intersections. Narrow screens use six small cells above, all four cards full-width, then six small cells below. This is a separate layout recipe, not a horizontally scrolling desktop wall.

## Hover-only conic ring
Primary action and release pill have a masked conic border and radial blur halo. `@property` registers an angle so only hovering starts rotation. This is distinct from a simple button background transition. Full values are in motion.md.

## Multilayer CTA
Base135°: #4e7cff0%, #9f4bff24%, #d54a9658%, #ed7d3f100%. Overlay white radial.55 at12%22%→transparent17%; white.14 at82%20%→22%; blue rgba(86,74,255,.5) at78%100%→24%; white.06 vertical wash. Large radius34px, white display copy/action, logo strip and product window crop. Keep this concentrated at the bottom so the page stays white-led overall.

## UI-driven illustrations and transitions
Layered process illustrations, approval floats, linked flow nodes, calendar dialogs, code surfaces and screenshot fades are first-class capabilities. The masks, seams and cards carry hierarchy; global scroll effects are not necessary to reproduce the source.
