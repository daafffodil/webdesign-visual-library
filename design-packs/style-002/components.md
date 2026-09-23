# Components

## Navigation and actions
Measured: 80px desktop / 76px mobile navigation, full-width three-column menu, 48px menu icon boxes. The source menu uses native links and on mobile expandable categories. Playground uses neutral local section links and a closeable full-screen selection menu; category wording and destination behavior are reconstructed.

Primary action: #4457ff, hover #3347fb, min-height50px, radius15px, horizontal32px, Inter15px/500/−.03em, 300ms cubic-bezier(.4,0,.2,1). Hover adds the conic border and blur documented in motion.md. Closing white CTA: min-height52px, radius16px, horizontal28px, font16px/600, −2px Y on hover over200ms. Hero proof text is13px with approximately20–21px leading.

Preview chips: fully rounded, dashed1px #d8dbe2 border, white surface, 30px height, 8px spacing, selected pale blue fill and solid border. The top-right blue check is a separate animated bubble. Source currently has twelve modes (Composer, AI Assistant, Automation, Post Conditions, Smart Scheduling, Social Inbox, Recycle Suggestions, Analytics, AI Design Library, OpenClaw, Claude Code, API/CLI). Demo replaces branded integrations with Agent Chat and Code Assistant.

## Product and content cards
- Process panels: white on a seam grid, layered illustration at top, numbered small heading below. Not independent rounded floating cards.
- Chart panels: broad, visually taller than the process illustrations, bottom white fades, supporting caption below. Data is illustrative in the demo.
- Workflow cards: #f6f6f8, radius15px, gap18px, title19px/800, body15px/23px, screenshot in purple outline that disappears at the bottom.
- Micro integration cards: compact icon inline with heading, one explanatory line, 1px seams; no shadow.
- Social tiles: #f5f5f8, desktop153px square/radius28px; inner color icon72px. Empty tiles are part of the composition.
- Feature wall small cells: 1px boundaries, centered icon/label, quiet hover. Four focus cards span2×2 cells with individual glows and shadows; see special-modules.md.
- Editorial illustration: split/merge adapters, approval overlay, rules plus queue. These are six-purpose UI compositions across process/editorial, not repeated abstract cards.

## Inputs and states
The captured homepage does not expose a live product form. Many apparent inputs are pixels inside WebP screenshots. Editable workbench inputs/textarea, disabled buttons, visible focus outline and selection feedback are **reconstructed**. They must never be described as measured FeedHive input tokens. Playground menus, chips and demo controls are real buttons; image-like UI interiors are editable source code, not a functional publishing application.

## Reuse API
`ProductUI({mode,bare})` renders twelve dense UI states. `Diagram({variant})` renders six process/editorial illustrations. `Chart({line})` renders neutral illustrative evidence. `FeatureWall({onSelect})` exposes emphasis-card selection. `Heading({label,children})` combines measured mono eyebrow and display heading. Root class `style-002-scope fh` isolates tokens and component styles from the library shell.
