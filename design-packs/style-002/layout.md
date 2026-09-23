# Layout and density

Measured source rules, primarily desktop DOM/CSS with responsive classes in sections.json. Actual heights vary with text and viewport.

| Element | Measured rule |
|---|---|
| Main container | max-width 1188px |
| Hero desktop | padding 64px 32px 40px; left padding-top 32px |
| Hero columns | 640px + remaining 540px at full container, gap 8px; 620px left at 1024–1279px |
| Hero stage | min-height 680px, padding-top 24px; oversized image approximately 128% wrapper |
| Hero badge / title | badge padding 6px 14px; title margin-top 28px |
| Hero actions / switcher | margin-top 40px / 44px |
| Pills | 30px high, 12px horizontal padding, 8px gaps, max-width 540px |
| Trust | padding 32px; columns 220px + remaining, 40px gap |
| Process | section top 56px, bottom 92px; heading max760px; grid margin44px; 1px seams |
| Process card | top34px bottom42px; caption max240px; image intrinsic ratio |
| Video | top46px bottom118px; heading-to-frame60px; 16:9, 14px frame, radius16px |
| Outcomes | top56px bottom92px; quote top100px, portrait60px; two equal chart columns |
| Social block | top/bottom82px; cells153px, horizontal gap26px; three rows |
| Workflow block | top54px bottom108px; 2 columns, gap18px; gray cards radius15px, padding28px 34px 0 |
| Editorial block | top/bottom78px; three alternating rows and 1px separators |
| Feature wall | max-width1260px; inner1240px, ten columns, gap1px, auto rows112px |
| CTA | max-width1248px, radius34px, padding46px 56px 0; UI crop430px high, margin-top72px |

Hero grid uses two linear gradients with rgba(61,86,255,.055) 1px lines at 100px spacing. A vertical mask stays opaque through62%, falls to .78 at78%, .32 at90%, transparent at100%. Preserve this quiet field, not a purple wash.

Reconstruction: internal DOM product windows have fixed design widths with CSS zoom to preserve miniature UI density. Their zoom ratios and illustrative chart heights are adjusted optically rather than measured source application DOM. Main marketing geometry is independent of these internals. Give every grid child min-width:0 so the intentional product overflow never widens the text track on mobile.
