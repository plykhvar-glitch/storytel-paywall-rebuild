# Growth Audit — Storytel

**Live:** https://plykhvar-glitch.github.io/storytel-paywall-rebuild/
**Prototype on your phone:** https://plykhvar-glitch.github.io/storytel-paywall-rebuild/?view=proto

The Storytel paywall in Mexico, rebuilt as one screen that opens on the promise of the ad that brought each person in: the yearly price by the month, a story playing offline, the book they came for. Same design, same Mexican prices. Three phones side by side, one per ad; change the ad or who listens under a phone and its paywall rewrites itself.

## The five ideas

| # | Idea | Potential outcome |
|:--|:--|:--|
| 01 | Open the paywall on the ad’s promise | CR +15–20% |
| 02 | Put 4.8 from 23K ratings by the button | CR +10–15% |
| 03 | Tick Yearly, the plan with the free week | CR +5–15% |
| 04 | Drop the confirmation screen and its checkbox | CR +5–8% |
| 05 | Say “cancel before the last day, pay nothing” by the button | CR +3–8% |

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps, not measured lift for Storytel.

## Grounding

$169 MXN a month and $1,190 MXN a year are from the Mexican App Store’s in-app purchases (27 November 2026) and storytel.com/mx, which also says “Ahorra 40%”. The 7-day free trial on the yearly plan and the three paywall screens are from a walkthrough of Storytel on iOS with Mexico selected, shown as captured on the Today step. 4.8 from 23K ratings and the reviews are from the Mexican App Store; “cancel before the last day of the trial” and Kids Mode are from the App Store listing. The ads are from the Meta Ad Library. Progress and listening history on the phones are samples.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty.
