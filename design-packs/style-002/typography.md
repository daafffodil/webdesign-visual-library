# Typography

All following source typography values are measured from DOM / loaded CSS. File names and source URLs are indexed in `evidence/assets.json`.

| Role | Family | Desktop | Weight | Tracking | Mobile |
|---|---|---|---|---|---|
| Hero | Plus Jakarta Sans | 55px / 56.1px | 600 | −.035em | 46px / 46.92px; 52px from 640px |
| Section heading | Plus Jakarta Sans | 58px / 56.84px | 600 | −.03em | 32px / 31.36px; 46px from 640px |
| Workflow card heading | Plus Jakarta Sans | 19px / 28.5px | 800 CSS declaration | −.032em | same |
| Editorial heading | Plus Jakarta Sans | 29–30px / 1.01 | 800 CSS declaration | per source element | 26px |
| Closing CTA | Plus Jakarta Sans | 54px / 54px | 600 | −.025em | 33px; 42px from 640px |
| Body / benefits | Inter | 16px / 24px | 400, emphasis 600 | local −.02 to −.025em | 16px / 24px |
| Eyebrow | Sometype Mono | 14px / 21px | 700 | .14em | generally 14px |
| Primary button | Inter | 15px | 500 | −.03em | same |
| Preview pill | Inter | 14px / 22px | 500 | −.02em | same |

Loaded source font CSS advertises Jakarta 500/600/700; certain source elements request 800. Treat 800 as the measured CSS request, not proof that an independent 800 font file was delivered.

Local font mapping in `components/feedhive.css`:
- `FeedHive Jakarta` → `/feedhive-reference/fba5a26ea33df6a3-s.p.1bbdebe6.woff2`
- `FeedHive Inter` → `/feedhive-reference/83afe278b6a6bb3c-s.p.3a6ba036.woff2`
- `FeedHive Mono` → `/feedhive-reference/543712a1048bd1ed-s.p.b875d14a.woff2`

Aliases are reconstructed implementation names; the font identities and files are measured. Preserve the source’s compact line-height and negative tracking; do not globally replace them with a generic 1.2 heading line-height. The English demo is intentionally neutral. For new Chinese interfaces, follow the workspace's Chinese copy preferences and re-evaluate line length rather than imitating English line breaks.
