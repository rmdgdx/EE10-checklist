# Electrical Engineering Proposal Quality Evaluator

A self-contained browser-based checklist and proposal-readiness evaluator for electrical engineering research concepts.

The tool accepts a student profile, concept statement, variables and measurements, methodology, and data-analytics plan. It then generates a transparent 100-point rating, criterion-level feedback, identified strengths, and prioritized recommendations.

## Key features

- 24-item electrical engineering proposal checklist
- Automated 100-point proposal-readiness rating
- Ten weighted quality criteria
- Criterion-by-criterion evidence report
- Personalized comments and priority revisions
- Print or save the evaluation report as PDF
- Responsive royal-blue-and-gold design
- Fully client-side processing
- No account, server, database, or external package required

## Important scope statement

Scopus evaluates publication sources rather than individual research proposals. This educational rubric adapts relevant Scopus quality dimensions—such as academic contribution, clarity, readability, international relevance, peer review, and research integrity—and combines them with electrical-engineering methodology, measurement, validation, safety, and statistical-analysis standards.

A high score does not guarantee research approval, journal acceptance, or Scopus indexing. Final decisions should remain with the research adviser, panel, ethics body, and relevant technical or statistical experts.

Official reference: [Scopus content policy and selection](https://www.elsevier.com/products/scopus/content/content-policy-and-selection)

## Repository contents

| File | Purpose |
| --- | --- |
| `index.html` | Complete evaluator, including styles and JavaScript |
| `README.md` | Project overview and usage instructions |
| `UPLOAD_TO_GITHUB.md` | Step-by-step GitHub and GitHub Pages instructions |
| `CITATION.cff` | Suggested citation metadata for GitHub |
| `CHANGELOG.md` | Version history |
| `LICENSE` | Copyright and reuse terms |
| `.nojekyll` | Prevents GitHub Pages from applying Jekyll processing |
| `.gitignore` | Excludes common local system and editor files |

## Use locally

No installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Complete all required fields.
4. Review the checklist and select the items already addressed.
5. Select **Rate this proposal**.
6. Use **Print / Save report as PDF** if a copy is needed.

The checklist completion percentage is intentionally separate from the automated score. Checking an item does not add points; the evaluator looks for corresponding evidence in the written entries.

## Quality rubric

| Criterion | Weight |
| --- | ---: |
| Significance and relevance | 10 |
| Research gap and novelty | 12 |
| Objective clarity and alignment | 8 |
| Variables and measurement | 10 |
| Methodological rigor and reproducibility | 14 |
| Data quality and feasibility | 10 |
| Data analytics and statistics | 12 |
| Electrical-engineering technical validation | 10 |
| Ethics, safety, and research integrity | 6 |
| Clarity, literature, and scope | 8 |
| **Total** | **100** |

## Rating bands

| Score | Interpretation |
| ---: | --- |
| 90–100 | Excellent — publication-oriented |
| 80–89 | Very good — strong proposal |
| 70–79 | Good foundation — revisions required |
| 60–69 | Developing — major revision |
| Below 60 | Insufficient evidence — redesign needed |

## Privacy

All entries and scoring remain in the user's browser. The evaluator does not make network requests, transmit entries, or permanently store proposal data.

## Customization

The application is contained in `index.html`:

- Edit the CSS variables near the beginning of the file to change the color palette.
- Edit the checklist markup to adapt institutional requirements.
- Edit the `evaluate()` function to revise scoring rules or weights.
- Keep the ten criterion weights equal to 100 after any rubric change.

## Browser support

The evaluator is designed for current versions of Chrome, Edge, Firefox, and Safari. JavaScript must be enabled.

## Version

Current release: **1.0.0**

