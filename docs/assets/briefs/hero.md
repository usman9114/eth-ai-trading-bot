# Brief: README hero and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (AI illustration, no text), composed with real type into `docs/assets/hero.jpg` (README banner) and `docs/assets/social-preview.jpg` (1280x640, upload in GitHub Settings, Social preview). The exact prompt, model and time are in `docs/assets/hero-art.png.json`. References are inspiration only; none was used as an image input or copied.

## What a newcomer must see
A signal does not trade until evidence earns it a weight, and trading stays inside hard risk limits. The art must not suggest profit: it shows the gate and the shield, not a winning chart.

## References
| Reference | What works | Taken / avoided |
|---|---|---|
| [freqtrade README](https://github.com/freqtrade/freqtrade) (opened) | Banner plus feature bullets; dry-run listed; plain risk disclaimer | Keep a plain disclaimer in the banner text |
| [freqtrade stoploss docs](https://www.freqtrade.io/en/stable/stoploss/) (opened) | Risk shown as one worked price path with before and after levels | Show risk as a path crossing a threshold, not a settings list |
| Dry-run docs mirror ([codeclimate copy](https://codeclimate.com/github/freqtrade/freqtrade/docs/bot-basics.md/source), search snippet only) | Paper vs live as a labelled mode, with a warning | Reflected in the Mermaid note on dry, testnet and live modes |

Research note: the freqtrade README has no visual for paper vs live; our banner and flow show the evidence gate instead.

## Design (revised 2026-11-26)

- **Style:** Tilt-shift clay and felt diorama, golden hour.
- **Why this picture:** The repo's core rule is an evidence gate: no signal gets capital until forward evidence earns it, inside hard limits. A boat waiting for a canal-lock gate to open is that rule, and it implies no profit.
- **Subject:** a brick canal lock with heavy wooden gates, a small sailboat in the chamber, the gate beginning to open, and a plain wooden gauge post. Shallow depth of field. Palette: warm gold, sky blue, brick red, moss green.
- **Layout:** the left third stays quiet for the title; colours and font of the title are set per image in `compose_banner.py`.
- **Must not contain:** text, letters, numbers, logos, watermarks, borders, real people, robots.
- **QA:** schema check by a vision model against this brief, plus a manual look.

## Revision note

The first version of this banner used the same dark navy, teal and grid look as the owner's other repos. It was consistent but samey, so it was replaced with a distinct art direction per repo, each built on a metaphor for what the repo does.
