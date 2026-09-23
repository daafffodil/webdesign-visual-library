# Product UI as visual material

The original uses large WebP screenshots and composited product illustrations. Live DOM measurements establish their wrapper, crop, border and fade, but not the internal application UI values.

## Source modes
Composer has a purple browser bar, a central paper editor, thumbnail strip and paired lower widgets. AI Assistant splits conversation and green/red edit-review text. Automation and conditions show linked flow nodes. Scheduling shows a calendar with a centered dialog. Inbox and recycling are list-based. Analytics uses chart panels. Design Library is a dense image grid. Agent chat, coding assistant and API/CLI expose chat or terminal layouts. The source mode labels and images are indexed in assets.json; preserve their diversity when adapting the pattern.

## Reconstruction implementation
`ProductUI` builds these visual families with real DOM, CSS and neutral text. `WindowBar` supplies the saturated violet/blue strip. Pale surfaces, dense text, thin borders, chat bubbles, list dividers, miniature media, code text and small utility widgets supply the same visual hierarchy. These internals are reconstructed, including font sizes, shadows, fixed working widths, thumbnails, chart values and fake project records.

Do not claim the product demo is a working automation service. The page-level controls switch these compositions, the demo advances through five scenes, and workbench fields can be edited. The original video is represented by a reconstructed interactive sequence inside its measured frame. For a new product, replace the scene with that product's own UI or video.

## Wrapping recipes
1. Hero: oversize beyond the right column; preserve left alignment, purple window header, right-edge transparency and broad bottom fade. The UI should feel embedded into the page, not like an isolated screenshot card.
2. Process: layer small paper/dialog elements at differing heights, connect them with arrows, dissolve the bottom into white.
3. Workflow cards: clip screenshots inside pale gray cards; add a thin rounded purple outline and bottom fade.
4. Editorial: compose distinct split, approval and queue diagrams with local floats; no page-level fixed positioning.
5. CTA: large crop emerging from below the gradient panel. Mobile retains a280px crop height but a scaled UI width.

## Source asset policy
Real source screenshots and selected original WebP assets appear only in Reference and the evidence pack. The default Playground does not use FeedHive logos, customer marks or original business screenshots to imply similarity. Bundled original fonts provide the measured typography. Source URLs and observation date remain attached for later refreshes.
