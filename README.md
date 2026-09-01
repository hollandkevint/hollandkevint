# Kevin Holland

I lead and build healthcare data and AI products that people trust, buy, and use to make decisions.

I have spent more than 10 years turning clinical data, research workflows, and hard product decisions into working systems. I work close enough to the implementation to test failure cases and make product tradeoffs with engineers and clinicians.

## Flagship build: CensusChat

[CensusChat](https://github.com/hollandkevint/CensusChat) is a natural-language interface for US Census data, built for healthcare strategy teams.

The key product decision sits between the model and the database: generated SQL must pass a validation layer before DuckDB executes it. The repository includes the working application, test suite, safety controls, documentation, and the limitations I found while building it.

## Other open-source work

- [ThinkHaven](https://github.com/hollandkevint/thinkhaven): A live decision-architecture product that turns a hard-question session into a decision record someone can review and defend.
- [Data Product Operator](https://github.com/hollandkevint/data-product-operator): Skills and workflows for discovery, validation, quality, governance, and delivery across data products.
- [ThinkHaven Method Kit](https://github.com/hollandkevint/thinkhaven-method-kit): The open method behind ThinkHaven, including pressure tests, decision briefs, and anti-sycophancy patterns.
- [AI Presence Template](https://github.com/hollandkevint/ai-presence-template): A small template for making a personal site easier for people and AI-powered search to understand.

## Complementary products and proof

### InstaDoc Health

I co-founded [InstaDoc Health](https://instadoc.health/), an AI symptom assessment that routes people to a next step and keeps licensed clinicians responsible for care decisions. I lead product and technical architecture, including the evaluation pipeline and safety boundaries.

### NeuroBlu Analytics

At [NeuroBlu Analytics](https://www.neuroblu.ai/), I built the product from zero to roughly $10M in annual recurring revenue, scaled the clinical dataset from 0.5M to 46M+ patient lives, and shipped clinical-data and AI products used across 25+ regulated organizations.

My AI and machine-learning work there includes:

- **Research Assistant:** Product leadership for a human-reviewed question-to-evidence workflow spanning cohort definition, governed analysis, and auditable reporting.
- **Clinical NLP and Symptom Intelligence:** Turning information in clinical notes, validated scales, mental-status exams, and diagnoses into queryable symptom-level evidence. [See the public Symptom Intelligence release](https://www.neuroblu.ai/announcements/introducing-symptom-intelligence-symptom-level-rwe-for-neuropsychiatry).
- **Natural-language analytics:** Evaluation and governance for natural-language-to-SQL inside a controlled data environment, with human review retained for research conclusions.

The current public product reports 188M+ clinical notes and 3,099 clinician-validated mappings across 63 symptoms and five disorders. The code, customer data, and internal evaluation results belong to Holmusk and stay private. The public NeuroBlu links show the product context, not a claim that I built every part alone.

### kevintholland.com

I built [kevintholland.com](https://www.kevintholland.com/) as the full proof manual for my products, commercial record, operating methods, and writing.

## How I build

1. Name the user, decision, and owner.
2. Test the riskiest claim against real evidence.
3. Ship the smallest useful system with clear safety boundaries.
4. Watch what breaks, document it, and improve the product.

[Portfolio](https://www.kevintholland.com/) · [LinkedIn](https://www.linkedin.com/in/kevintholland) · [Email](mailto:kevin@kevintholland.com)
