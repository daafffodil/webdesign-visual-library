# Motion evidence and implementation

Measured from loaded source stylesheets in `evidence/stylesheets/`, plus direct Browser preview/menu interactions. CSS declarations are evidence of available behavior; no source JavaScript timer interval was recovered.

| Effect | Measured values | Trigger |
|---|---|---|
| Check bounce | 340ms cubic-bezier(.22,1,.36,1); 0% opacity0/Y6px/scale.2;58% opacity1/Y−1/scale1.12;78% Y1/scale.97;100% identity | Selected preview changes |
| Agent logo swap | 420ms cubic-bezier(.2,.8,.2,1), opacity0/Y55%/scale.72 → opacity1/Y0/scale1 | Logo replacement |
| Integration row | 16s ease-in-out infinite; X−10px↔+10px; phases0/−4.5/−9s | Continuous |
| Primary background | 300ms cubic-bezier(.4,0,.2,1) | Hover |
| Conic border | 2.2s linear infinite, paused until hover; angle0→1turn | Hover |
| Border/halo visibility | opacity220ms; halo blur8px | Hover |
| Focus card | scale1.01 and stronger shadow,300ms cubic-bezier(.22,1,.36,1) | Hover |
| Focus card icon | scale1.03, brightness.98,200ms | Hover |
| Customer marks | grayscale1/.75 opacity → grayscale0/1 opacity,300ms ease-out | Hover |
| Closing CTA action | translateY−2px,200ms | Hover |

Ring colors: #4f7dff→#7165ff→#d650ff→#ff7f59→#4f7dff. Border inset−4px/radius18px/padding2.75px; halo inset−6px/radius20px, radial #636eff6b→transparent68%. Pill uses −3px/−5px insets and9999px radius. Two content-box masks exclude the center.

## Reconstructed controls and timing
Preview automatic period4500ms, logo period3000ms and demo scene period2400ms are implementation choices, not recovered source timers. Manual preview selection stops the demo's automatic cycling. Pause/resume is added for inspection. Escape closes menus. Reduced-motion disables transitions/animations and automatic hero rotation. Demo only advances after an explicit click. These accessibility provisions are adaptations rather than claims about the original site.

## Negative findings
Across a complete manual top-to-bottom desktop inspection and mobile review, no reliable source evidence established scroll reveal, stagger, parallax, sticky navigation, scroll-controlled scale or blur, or an infinite marquee. A screenshot loading late is not itself a scroll animation. Do not label these unobserved effects measured. Source product-window floats are part of images, not fixed browser overlays.
