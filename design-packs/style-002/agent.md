# Style 002 — FeedHive

Source: https://www.feedhive.com/ · observed 2026-09-09, current v2.0 homepage

## Read order
1. `manifest.json`, then `tokens.json` / `tokens.css`
2. `visual-inventory.md`, `typography.md`, `layout.md`, `responsive.md`
3. `components.md`, `product-ui.md`, `special-modules.md`, `motion.md`
4. `validation.md`; consult `evidence/` when resolving an uncertain value

## Implementation contract
Import the scoped CSS tokens before components. The working React implementation is `components/feedhive-playground.tsx` plus `components/feedhive.css` at the repository root. It exports `FeedHivePlayground`, `Heading`, `ProductUI`, `Diagram`, `Chart`, and `FeatureWall`. It depends on React and lucide-react. Preserve those relative locations, or update the CSS token import when moving files. Load the three WOFF2 files specified in `typography.md` before visual comparison.

FeedHive is a white, blue-led, product-heavy visual system. Preserve tight Jakarta display typography, dashed blue emphasis, fine grid seams, oversized UI fading into white, the rocking integration matrix, agent workflow cards, dense feature wall and multicolor closing CTA. Do not import Style 001's black buttons, dotted decoration, section composition or reveal choreography. The other style is only a directory organization precedent.

Choose modules appropriate to the new product rather than copying the source homepage's business narrative. Replace FeedHive's brand, customer marks, quotes, copy and product data. The neutral Draftroom implementation demonstrates reuse; its fictional numbers are not performance evidence. Product screenshots belong in source reference, not as a substitute for an adaptable UI in a new product.

## Evidence discipline
- `measured`: computed styles, DOM classes, loaded source CSS or an observed interaction. The source of each token is recorded in tokens.json. A DOM pixel measurement is viewport-specific, not an eternal design rule.
- `reconstructed`: adapted illustration interiors, substitute content, unknown rotation periods, added usability controls. Do not relabel them measured merely because the reconstruction can be measured in our browser.
- A source image's internal UI cannot be measured as live DOM. Keep its pixel appearance and our CSS reconstruction distinct.
- There is no confirmed global scroll reveal, stagger, parallax or sticky navigation in this inspection. Do not invent these as FeedHive traits.

## Acceptance
Check at 1440×900 and 390×844, plus a tablet width. Compare source and implementation with the same preview selected. Inspect heading wraps, white-to-color ratio, section density, stage crop and fade, card scale, matrix masks and mobile rearrangement. Test all preview buttons, menus, demo, feature cards and inputs. Respect reduced motion and keyboard focus. Read the reconstruction limitations in validation.md before claiming fidelity.

The pack deliberately has additional files for product UI, special modules and responsive behavior. Do not discard them to fit the Style 001 schema.
