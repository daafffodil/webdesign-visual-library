# Responsive rules

Measured source breakpoints:640px(sm),768px(md),1024px(lg),1280px(xl), observed in loaded CSS / DOM classes. Desktop evidence initially sampled at1754×1315, with reference screenshots standardized to1440×900. Mobile evidence sampled at390×844.

| Behavior | Wide | Narrow |
|---|---|---|
| Hero | Two columns from1024; left620px then640px from1280 | Single column; gap40px; stage min430px |
| Page gutters | 32px | 24px tablet,16px mobile |
| Hero title | 55px from1024 | 52px from640,46px below640 |
| Section title | 58px desktop | 46px from640,32px below640 |
| Navigation | Full links and mega menu | Drawer-style full-screen menu |
| Trust logos | Horizontal strip | Two columns at narrow width |
| Process / outcomes | Three / two columns | One column |
| Workflow cards | Two columns | One column; still gray surface and cropped purple UI |
| Micro descriptions | Three columns from768 | One column narrow |
| Editorial rows | Alternating left/right | Text first for all three rows |
| Social cells | 153px, gap26px | 133px/gap20;86px/gap10 mobile |
| Social tile radius | 28px | 24px tablet,22px mobile |
| Feature wall | Fixed-width ten-column matrix | Six cells + four vertical cards + six cells |
| CTA | 54px title, horizontal action | 33px title, vertical action; logos wrap;280px product crop |
| Footer | Brand area + four link columns | Link groups single-column below640, two columns from640 in source |

Playground's miniature UI zoom and neutral copy lengths are reconstructed. Check actual content instead of imposing the source's total page height. Its extra Component Workbench follows the footer and is not part of the source homepage. Intentional visual overflow lives inside clipped scene containers; the document itself must not scroll horizontally.
