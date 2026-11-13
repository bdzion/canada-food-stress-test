# Canada Food System Stress Test

Shocks to Canada's food system are inevitable; crises are not. Whether a shock becomes a crisis depends on buffers: the spare capacity that absorbs it. No one tests how shocks spread, combine or could be stopped early. This prototype shows how a national stress test could.

**Live page:** https://bdzion.github.io/canada-food-stress-test/

**User guide:** https://bdzion.github.io/canada-food-stress-test/guide.html

Developed at the Arrell Food Institute (AFI), University of Guelph, as a discussion prototype for a long-term research program on preparing earlier for disruptions to the food system. It builds on AFI's 2026 Canada Agri-Food Chokepoint Audit.

## What it shows

The front page has two connected parts.

**1. The risk dashboard** (`#dashboard`) has four tabs:

- **The system** (`#system`): a simple map of how food moves, from farm inputs to stores and households, with buyers abroad and food from abroad on either side, and the authors' overall view.
- **The indicators** (`#indicators`): twelve measured facts that show where Canada is exposed, each with how serious the authors judge it, whether it can be fixed, the threats that hit there and a linked source.
- **The threats** (`#threats`): eighteen threats in six groups, with the highest example warning level in each group (Normal, Watch, Get ready, Act now), and seven "what if" tests of single threats.
- **Possible timelines** (`#timelines`): four ways a bad year could unfold when several threats arrive together. Possible, not predicted.

Below the tabs, **What a bad year could cost** (`#costs`) is interactive. It runs all seven tested threats, or one of the timelines, in the same year and compares acting early (at each "get ready" sign), waiting to react (at each "act now" sign, a stand-in for how responses often work today) and doing nothing. Sliders set the extra damage when threats overlap and the extra delay when agencies are stretched, and a checkbox adds a shared plan agreed in advance. Each single-threat test also shows the best day to start, what a false alarm would cost, and a plan agreed in advance. Proposed leads and funding have not been agreed by any agency.

**2. The decision game** (`#challenge`) takes one threat from the dashboard and puts the user in charge: a Prairie grain rail line may close in 72 hours. Choose a plan, get news on Day 5, and see what happened by Day 35 and what it cost in Canadian dollars compared with waiting to react. About three minutes.

Other pages are linked from "More on this site" at the bottom of every page: the research plan (`#research`), how the tests work (`#methods`, including the full list of threats), recent events (`#updates`), potential partners (`#partners`, not finalized), the *Feeding a Fragile World* Substack, the companion [Granary Risk Assessment Dashboard](https://feeding9billion-cmyk.github.io/Granary_Risk_Dashboard/), the user guide, and a printable summary. Links that leave the site open in a new tab.

## Important caveats

- **Examples, not forecasts.** The tests use simple models with stated assumptions. Every input is listed in the page's "Assumptions and sources" table and marked as a fact or an example value.
- Warning levels are example settings chosen by the authors, not live readings. How serious each threat and indicator is reflects the authors' preliminary judgement. The first phase of the research program would replace this with a structured expert ranking.
- None of the tests has yet been checked against real events.

## Structure

Two self-contained pages with no build step: `index.html` (the site) and `guide.html` (the user guide: plain-language terms, how to use the site to prepare a decision, how the full system would work, and evidence on effectiveness). Indicators, threats, recent events and timelines are plain data arrays in the script in `index.html`, so they are easy to update. `preview.png` is the image shown when the link is shared. Fonts load from Google Fonts. GitHub Pages serves the site from the root of the `main` branch.

## Feedback

Email comments to mbodrudd@uoguelph.ca. Each revision is recorded in the commit history.

## Contact

Arrell Food Institute, University of Guelph
