# Browser comparison and validation

Observed 2026-09-09 against https://www.feedhive.com/ current v2.0 homepage.

## Visual review
The source was browsed from announcement through footer on desktop, then reviewed on mobile. Read-only DOM/computed-style captures, delivered CSS, original assets and real screenshots are retained in evidence/ and screenshots/. Reference includes complete desktop/mobile page captures, not mock screenshots.

The neutral Playground and source were compared in Browser at1440×900 and390×844. Shared comparisons included Hero/Composer, integration matrix, feature wall and closing CTA. The layout inventory was checked against the remaining source sections. This is a visual-language reconstruction, not a pixel-identical copy of FeedHive's proprietary product illustrations.

| Dimension | Result / limitation |
|---|---|
| Density | Same sequence of major visual families, wide product areas and a dense44-cell feature wall; extra workbench follows the footer |
| Composition | Hero copy/stage alignment, seam grids, alternating rows and closing panel retained |
| Color ratio | White is dominant; blue confined to emphasis/actions/window chrome; saturated multicolor concentrated in CTA |
| Typography | Original font files; measured55px Hero,58px section titles and compact leading; neutral text changes some wraps |
| Whitespace | Source per-module spacing retained; no single universal section-spacing token imposed |
| Component size | Measured buttons, workflow cards, social tiles and feature-wall rows; UI interiors optically reconstructed |
| Background / depth | 100px fading grid, side/bottom screenshot masks, slanted social masks, pastel card glows, conic ring and radial CTA lights |
| Product presentation | Twelve DOM preview families with scaled/cropped wrappers; less micro-detail than source WebP images |
| Motion | Source CSS keyframes/easing retained; unknown automatic rotation periods explicitly reconstructed |
| Mobile | Actual alternate compositions, not uniform desktop scaling; no document horizontal overflow at390px |

Corrections made during Browser comparison: grid min-content overflow on mobile; text-first order for all editorial rows; six/four/six mobile feature wall; source two-column CTA logo flow; second social row58px mobile stagger; CTA crop heights; separate full-screen mobile navigation.

## Functional review
- Twelve preview controls exercised; selected state maps to corresponding composition, manual choice pauses cycling
- Full-screen mobile menu expands groups; Escape closes it
- Desktop gradient ring responds to hover:2.2s animation, opacity1, blur8px verified in computed styles
- Demonstration playback advances scenes and pauses
- Feature emphasis cards display selection feedback
- Workbench text fields accept editing; disabled action remains disabled
- All four detail tabs render; mobile embedded preview measures390px; Agent copy reports success
- Reference assets, machine-readable manifest and downloadable archive checked for existence

## Technical validation
`npm run build` and `npx tsc --noEmit` pass. Targeted lint for Style002 components and routes passes. Whole-project lint reports three pre-existing accessibility errors in `app/shiguang/shiguang.tsx` and `components/ocoya-playground.tsx`; those unrelated styles were not modified.

Build initially encountered Windows subprocess restrictions inside the sandbox; the same existing build command succeeded with approved execution outside the sandbox. This is an environment issue, not a source change.

## Explicit reconstruction boundaries
Neutral brand/copy/customer wordmarks/avatar, illustrative data, editable product interiors, icon substitutions, demo sequence replacing the original video, input/disabled/focus states and timer periods are reconstructed. Footer destinations and menu copy are adapted to local demonstrations. Minor internal shadow/line density differences remain in the DOM illustrations. No original source scroll-reveal/stagger/parallax behavior is asserted.

Reference screenshot files are JPEG bytes returned by Browser and therefore use .jpg extensions. The browser trims its scrollbar area from captures; CSS viewport dimensions remain1440×900 /390×844, while saved visible rasters can be1425×891 /375×812. Full-page capture height depends on loaded source content. This is not a synthesized responsive mockup.
