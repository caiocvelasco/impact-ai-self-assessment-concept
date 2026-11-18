# AI-Assisted Impact Assessment — Research Concept

An independent, one-page [Quarto](https://quarto.org/) research concept exploring an **AI-assisted, human-in-the-loop self-assessment workflow** for organisations operating AI systems. The proposed workflow helps people organise evidence, examine potential societal and environmental benefits and harms, identify uncertainty, and plan further review.

The initial self-assessment is **one component of a broader research direction** spanning three complementary pillars:

1. **Structured assessment:** documents, interviews, stakeholder perspectives, governance and established assessment frameworks.
2. **Quantitative evaluation:** operational and observational data, experiments, statistical analysis and causal inference where the data and assumptions support them.
3. **Institutional research:** human oversight, organisational adoption, accountability and evidence-informed decisions.

These are *proposed research directions*, not implemented software modules. The page is a visual concept, **not a functioning AI assessment service** or a validated evaluation.

## Repository files

- `index.qmd` — the one-page website, illustrative five-step user journey and broader research vision.
- `styles.css` — responsive design, cards, workflow and research framework styling.
- `_quarto.yml` — website configuration.
- `.gitignore` — files excluded from version control.

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/) and run from the repository root:

```bash
quarto preview
```

For a static HTML build:

```bash
quarto render
```

## Publish to GitHub Pages

Publish or republish the site with:

```bash
quarto publish gh-pages
```

Follow the terminal prompts to authenticate and select the GitHub repository if requested. Ensure GitHub Pages is configured to serve the `gh-pages` branch. To publish updates, commit your source changes and run the same command again.

**Repository:** `impact-ai-self-assessment-concept`  
**Expected site URL:** <https://caiocvelasco.github.io/impact-ai-self-assessment-concept/> (once published and configured).

## Methodology, scope and attribution

The five-step journey is an **illustrative user experience**, not a new scientific assessment methodology. Existing methods—including [HIIG's Impact AI Method](https://www.hiig.de/en/project/impact-ai/) ([published materials](https://zenodo.org/records/23186663))—could supply the assessment criteria, evidence requirements and safeguards. HIIG's own method involves seven assessment stages and 25 criteria, including technical and organisational evidence, interviews, qualitative analysis and external perspectives.

The proposed AI assistance could help organise documents, identify evidence gaps and draft preliminary summaries; **people remain responsible for checking sources, interpreting impacts and deciding when independent assessment is required**. The quantitative and causal components are possible future research extensions and would require suitable data and credible research designs.

This project is **independent of HIIG**. It is not endorsed by HIIG, does not reproduce or implement its full method, and must not be presented as an official HIIG assessment. The page's visual palette is original, rather than an official HIIG brand system.

© 2026 Caio Velasco — independent concept, writing and interface design. Referenced assessment methodologies remain attributable to their respective authors.
