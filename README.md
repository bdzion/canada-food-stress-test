# Canada Food System Stress Test

An interactive prototype that puts Canada's food system at the centre: stresses from inside and outside Canada, sorted into six categories, ranked within each, traced to where they hit, and stress-tested alone and together, comparing acting early, acting late and doing nothing.

**Live page:** https://bdzion.github.io/canada-food-stress-test/

**User guide:** https://bdzion.github.io/canada-food-stress-test/guide.html

Developed at the Arrell Food Institute (AFI), University of Guelph, as a discussion prototype for a long-term research program on anticipatory decision-making for food-system shocks. It builds on AFI's 2026 Canada Agri-Food Chokepoint Audit.

## What it shows

| View | Content |
| --- | --- |
| Overview (opens first) | Where the pressure is now (six category tiles), what needs attention (top five stresses), and recent developments with dated, linked sources; a dated snapshot, not a live feed |
| Shock register | 18 stresses in six categories, tagged by origin (inside, outside, both) and pathway into Canada, ranked within category, with priority band, confidence and signal; filterable |
| Pathways into Canada | Traces a stress from event to pathway, Canadian chokepoint and outcome; groups stresses that share a pathway |
| Compound scenarios | Four storylines across categories with most likely path, events that would change it, and unmodelled stresses; each runs in the integrated test |
| Integrated stress test | The selected modelled shocks in one year; doing nothing, acting late or acting early; overlap losses; value of a joint playbook |
| Rail or port shutdown | Corridor closure from a labour dispute, flood or wildfire |
| Phosphate before seeding | Fertilizer import shortfall ahead of spring seeding |
| Cyberattack on distribution | A major grocery distributor taken offline |
| Avian influenza | A regional wave of highly pathogenic avian influenza in poultry |
| Prairie drought | Feed shortfall for Prairie livestock in a dry year |

Each stress test includes a four-part playbook card (trigger, action and lead, money, learning). "Print a decision brief" prints the current view with its settings.

## Important caveats

- **Illustrative only.** The models are stylized and use stated assumptions. They are not forecasts.
- Every assumption is listed in the page's "Assumptions and sources" table and marked as sourced or illustrative.
- Signal levels are the authors' demonstration settings. Shock rankings are the authors' preliminary judgement. Phase 1 of the program replaces them with a structured expert ranking.

## Structure

The site has two self-contained pages with no build step: `index.html` (the interactive stress test) and `guide.html` (the user guide: plain-language definitions, a decision workflow, how the full platform will work, back-end work and evidence on effectiveness). Register entries, recent developments and storylines are plain data arrays near the top of the script in `index.html`, so they are easy to update. `preview.png` is the image shown when the link is shared. Fonts load from Google Fonts. GitHub Pages serves it from the `main` branch root.

## Feedback

Open an issue in this repository, or send comments to the team. Each revision is recorded in the commit history.

## Contact

Arrell Food Institute, University of Guelph
