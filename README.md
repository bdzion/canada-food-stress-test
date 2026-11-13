# Canada Food System Stress Test

Canada grows plenty of food. A few weak links could still turn one bad event into a crisis. Banks are regularly tested against a severe but plausible bad year, so that weak points are fixed before a crisis. This prototype shows how Canada could do the same for its food system.

**Live page:** https://bdzion.github.io/canada-food-stress-test/

**User guide:** https://bdzion.github.io/canada-food-stress-test/guide.html

Developed at the Arrell Food Institute (AFI), University of Guelph, as a discussion prototype for a long-term research program on preparing earlier for disruptions to the food system. It builds on AFI's 2026 Canada Agri-Food Chokepoint Audit.

## What it shows

The front page walks through four steps:

1. **The system** (`#system`). A simple map of how food moves: farm inputs, farms, transport and ports, processing, and stores and households, with buyers abroad and food from abroad on either side. Each link shows how many indicators and threats affect it, followed by the authors' overall view.
2. **The indicators** (`#indicators`). Twelve measured facts that show where Canada is exposed, such as the share of grain exports that move by rail. Each gives the number, what it means, how serious the authors judge it, whether it can be fixed, the threats that hit there, and a linked source.
3. **The threats** (`#threats`). Eighteen events that could hit the system, in six groups, each with where it starts, what it hits, how serious it is judged to be and an example warning level (Normal, Watch, Get ready, Act now). Seven have a "what if" test: Prairie drought, avian influenza, loss of an export market, phosphate before seeding, a rail or port shutdown, a cyberattack on food distribution, and an outbreak among meat plant workers.
4. **Possible timelines** (`#timelines`). Four ways a bad year could unfold when several threats arrive together, marking the windows to act and the points after which only damage control is possible. Possible, not predicted.

Each "what if" test compares acting early (at the "get ready" sign) with waiting to react (at the "act now" sign, a stand-in for how responses often work today) and with doing nothing. It shows the best day to start, what a false alarm would cost, and a plan agreed in advance: when to act, what to do and who leads, money set aside, and learning afterwards. Proposed leads and funding have not been agreed by any agency.

**Try it yourself** (`#challenge`) is a three-minute exercise: a Prairie grain rail line may close in 72 hours. Choose a plan, get news on Day 5, and see what happened by Day 35 and what it cost in Canadian dollars compared with waiting to react.

Other pages are linked from "More on this site" at the bottom of every page: the research plan (`#research`), how the tests work (`#methods`, including the full list of threats), recent events (`#updates`), potential partners (`#partners`, not finalized), the *Feeding a Fragile World* Substack, the user guide, and a printable summary. Links that leave the site open in a new tab.

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
