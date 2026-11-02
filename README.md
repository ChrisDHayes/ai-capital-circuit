# The AI Capital Circuit

**Follow the capital. Question the circuit.**

An evidence-led, interactive investigation of how AI investment, cloud procurement, infrastructure finance and customer demand connect, and whether they are converging or drifting apart.

**Live experience → https://ChrisDHayes.github.io/ai-capital-circuit/**

*By Christopher Hayes, CDAIO · MBAN · MPS DAV · MSc in AI Candidate, Boston University*
*Evidence cutoff: October 28, 2026 · Not investment advice*

---

## The question

The familiar diagram of AI financing is a ring of famous companies joined by identical arrows. But the arrows are not identical. One is cash that has moved, another is a borrowing facility, another is a contract commitment, and another marks a reported valuation. Each one means something different, and each can tell a different story.

This project labels the arrows and then asks one test: **do capital, capacity, demand and obligations converge, or drift apart?**

## Start here

| If you want to… | Open |
|---|---|
| **Explore the evidence yourself** | [The interactive investigation](https://ChrisDHayes.github.io/ai-capital-circuit/#opening) |
| **Read the argument in order** | [The companion article](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html) |
| **See the method, hypotheses and limits** | [The full research essay](https://ChrisDHayes.github.io/ai-capital-circuit/research/essay.html) |
| **Check a figure against its source** | [Source index](data/SOURCE_INDEX.csv) · [Evidence workbook](data/AI_Capital_Circuit_Cumulative_Evidence.xlsx) |
| **Jump to a specific exhibit** | [Exhibit directory](https://ChrisDHayes.github.io/ai-capital-circuit/docs/EXHIBIT_LINKS.html) |

## Seven stops, one route through the evidence

The article and the interactive follow the same seven stops. Each stop in the article links to its exhibit, and each act in the interactive links back to the matching article section.

| Stop | Question | Interactive exhibit | Article section |
|---|---|---|---|
| 1 · Acceleration | How much is being invested, and what are we counting? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#acceleration) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#acceleration) |
| 2 · Origins | Where does the capital come from, and in what form? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#classification) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#origins) |
| 3 · Financial network | Who funds whom, and how large is each relationship? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#network-premium) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#financial-network) |
| 4 · Company trajectories | How are individual firms changing over time? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#motion-premium) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#company-trajectories) |
| 5 · Return of demand | What becomes recognized economics? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#realization) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#return-of-demand) |
| 6 · Obligations | Which dependencies and deadlines matter? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#resilience) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#obligations) |
| 7 · Sustainability | What do we know, and what do we not know? | [Open](https://ChrisDHayes.github.io/ai-capital-circuit/#findings) | [Read](https://ChrisDHayes.github.io/ai-capital-circuit/articles/substack.html#sustainability) |

Every citation in the article, such as **[8]**, jumps to its entry in the source list, and each entry links to the original document and back to the place in the text where it was cited. Source numbers and links are included in the interactive and the article as a shared evidence trail.

## How to read it responsibly

This project keeps different kinds of numbers apart. It does not add them together:

- completed equity investments
- financing facilities and borrowing capacity
- future procurement commitments and contract ceilings
- recognized revenue
- debt principal
- reported valuations
- hypothetical model outputs

Company size and link weights change meaning with the lens you select. Private financing valuations are not the same as public market capitalizations. Dates refer to the period and disclosure in the source, not necessarily the date the narrative was updated.

## What this does not show

- It does not estimate the total cash recycled across the AI economy.
- It is not a verified map of every equity, debt and contract relationship. It is a transparent, curated sample.
- It does not claim covenant stress across the board.
- It is not a calibrated contagion model. Hypothetical stress values are labelled as hypothetical and are never presented as reported facts.

The interactive runs entirely in the browser. It has no back end, no live monitoring and no automatic data updates. Links to original filings and reports need an internet connection.

## Repository map

```
index.html                       Interactive seven-theme experience (GitHub Pages home page)
.nojekyll                        Tells GitHub Pages to serve the files as they are
articles/substack.html           Companion article: reading page with citations and exhibit links
articles/Substack_Article.md     Substack-ready source (uses {{SITE_URL}} placeholders)
articles/Substack_Article.docx   Word draft of the article
research/essay.html              Full research essay: reading page
research/AI_Capital_Circuit_Research_Essay.md   Essay source
research/Research_Essay.docx     Essay as a Word document
research/Research_Development_Map.md           How the project was built, stage by stage
assets/                          Reading-page styles and the constellation preview image
data/                            Source index, evidence workbook, valuation source register
docs/                            Exhibit directory, methodology, verification, QA, publishing guide
scripts/                         Link configuration and link validation
```

## For maintainers

GitHub Pages setup, link configuration and Substack cross-linking steps are in [`docs/PUBLISHING_GUIDE.md`](docs/PUBLISHING_GUIDE.md). Run `python scripts/validate_links.py` before every release to confirm the static site is wired correctly.

## Suggested citation

Hayes, C. (2026). *The AI Capital Circuit: Follow the capital. Question the circuit.* Interactive investigation, evidence cutoff October 28, 2026.

## Acknowledgment and rights

Financial facts and contextual analysis refer to the linked disclosures and research, and attribution is kept in the essay and source index. The HTML, explanatory text and calculations are part of the project and are made available for noncommercial reuse subject to attribution and citation.

*This is research and analytical commentary, not investment advice.*
