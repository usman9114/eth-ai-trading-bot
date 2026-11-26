# Brief: README hero and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (AI illustration, no text), composed with real type into `docs/assets/hero.png` (README banner) and `docs/assets/social-preview.png` (1280x640, upload in GitHub Settings, Social preview). The exact prompt, model and time are in `docs/assets/hero-art.png.json`. References are inspiration only; none was used as an image input or copied.

## What a newcomer must see
A signal does not trade until evidence earns it a weight, and trading stays inside hard risk limits. The art must not suggest profit: it shows the gate and the shield, not a winning chart.

## References
| Reference | What works | Taken / avoided |
|---|---|---|
| [freqtrade README](https://github.com/freqtrade/freqtrade) (opened) | Banner plus feature bullets; dry-run listed; plain risk disclaimer | Keep a plain disclaimer in the banner text |
| [freqtrade stoploss docs](https://www.freqtrade.io/en/stable/stoploss/) (opened) | Risk shown as one worked price path with before and after levels | Show risk as a path crossing a threshold, not a settings list |
| Dry-run docs mirror ([codeclimate copy](https://codeclimate.com/github/freqtrade/freqtrade/docs/bot-basics.md/source), search snippet only) | Paper vs live as a labelled mode, with a warning | Reflected in the Mermaid note on dry, testnet and live modes |

Research note: the freqtrade README has no visual for paper vs live; our banner and flow show the evidence gate instead.

## Design
- **Subject:** a glowing trend line, dim and dotted before a tall translucent gate and bright solid after it, with a small shield arc beside the gate (risk limits).
- **Palette and style (shared across the owner's repos):** deep navy ink (#0B1020), teal/green highlight, amber for the exception, soft glow, faint perspective grid, minimal and not photoreal. Subject in the right two-thirds, calm empty left third for the title.
- **Must not contain:** text, letters, numbers, logos, watermarks, borders, people, robots, brains.
- **QA:** schema check by vision model against this brief, plus a manual look. Result noted in the commit.
