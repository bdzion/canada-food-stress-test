# Canada Food System Stress Test

An interactive prototype that puts Canada's food system at the centre: stresses from inside and outside Canada, sorted into six categories, ranked within each, traced to where they hit, and stress-tested alone and together, comparing acting early, acting late and doing nothing.

**Live page:** https://bdzion.github.io/canada-food-stress-test/

**User guide:** https://bdzion.github.io/canada-food-stress-test/guide.html

Developed at the Arrell Food Institute (AFI), University of Guelph, as a discussion prototype for a long-term research program on anticipatory decision-making for food-system shocks. It builds on AFI's 2026 Canada Agri-Food Chokepoint Audit.

## What it shows

The site has three levels:

1. **Front page: the national stress test.** Six category tiles show where the pressure is now (climate and weather; plant and animal health; conflict and trade; markets and inputs; logistics and cyber; people and labour). Below them, the integrated stress test runs a modelled shock from every category in the same year and compares doing nothing, acting late and acting early, with the value of a joint playbook.
2. **Category pages** (`#cat/<id>`). The ranked stresses in a category, each with signal, origin, transmission channel and evidence, and the integrated stress test for that category's modelled shocks.
3. **Single-stress tests.** Prairie drought, avian influenza, loss of an export market, phosphate before seeding, rail or port shutdown, cyberattack on distribution, and workforce outbreak at meat plants. Each shows warning signs, the cost of waiting, the decision window and a four-part playbook (trigger, action and lead, money, learning).

Every test compares early action with a **reactive response** (acting at the action signal, an assumed stand-in for current practice) and with no response as a boundary case. Results carry evidence labels (observed, illustrative, proposed, demonstration signals), "About this number" notes, a false-alarm cost and a model card. All models are at validation level V0 (demonstration).

The header links to a **three-minute decision challenge** (`#challenge`) and to **From prototype to science** (`#research`), the research programme with its workstreams, first pilot and validation ladder. The challenge is a stateful grain-corridor exercise: a Day 0 plan within an eight-unit budget, a Day 5 update, a Day 35 outcome compared with a reactive comparator, and a debrief across three event paths. Other supporting pages are linked from the "Explore the platform" panel at the bottom of every page: Methodology (`#methods`, including the full shock register and transmission channels), Compound scenarios (`#scenarios`), Recent developments (`#updates`), Potential partners (`#partners`, not finalized), the *Feeding a Fragile World* Substack, the user guide, and a printable decision brief.

## Important caveats

- **Illustrative only.** The models are stylized and use stated assumptions. They are not forecasts.
- Every assumption is listed in the page's "Assumptions and sources" table and marked as sourced or illustrative.
- Signal levels are the authors' demonstration settings. Shock rankings are the authors' preliminary judgement. Phase 1 of the program replaces them with a structured expert ranking.

## Structure

The site has two self-contained pages with no build step: `index.html` (the interactive stress test) and `guide.html` (the user guide: plain-language definitions, a decision workflow, how the full platform will work, back-end work and evidence on effectiveness). Register entries, recent developments and storylines are plain data arrays near the top of the script in `index.html`, so they are easy to update. `preview.png` is the image shown when the link is shared. Fonts load from Google Fonts. GitHub Pages serves it from the `main` branch root.

## Feedback

Email comments to mbodrudd@uoguelph.ca. Each revision is recorded in the commit history.

## Contact

Arrell Food Institute, University of Guelph
