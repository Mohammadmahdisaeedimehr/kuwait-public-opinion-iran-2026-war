# Methodology

## Analytical Approach

This project applies a structured OSINT-based analytical framework to examine public opinion and political narratives using social media data.

The methodology is designed to balance data integrity, interpretability, and policy relevance.

---

## Unit of Analysis

The dataset contains duplicated entries due to platform dynamics such as reposts and scraping overlaps.

Two parallel analytical lenses are used:

- **Content-level analysis (row-based):** reflects the weight and visibility of narratives in the information environment
- **Unique-level analysis (post/user-based):** controls for repetition and identifies genuine distribution across users

No rows are removed. Duplication is treated as a meaningful signal rather than noise.

---

## Data Processing

- Standardization of key fields (e.g., country naming inconsistencies)
- Timestamp normalization
- Identification of structural missing values
- Separation of engagement metrics (views, impressions, likes, replies, reposts)

---

## Topic Classification

Each piece of content is assigned to **one and only one primary topic**.

This ensures:

- No overlap between categories
- Full distribution summing to 100 percent

Topic categories are derived inductively from the data but include:

- Iran and its political system
- United States and military presence
- Persian Gulf (خلیج فارس) and regional security
- Israel and direct conflict narratives
- Missile and defense systems
- Negotiation and diplomacy
- Residual and noise category

---

## Narrative Mapping

Narrative relationships are analyzed through co-occurrence patterns.

Important note:

- This layer is **not percentage-based**
- A single post can contribute to multiple narrative links

The goal is to identify:

- Central narrative nodes
- Key associative structures
- Multi-layer threat construction patterns

---

## Stance Analysis

Stance is measured using a **binary classification**:

- Positive
- Negative

Neutral classification is intentionally excluded to enforce interpretive clarity.

Each stance distribution:

- Is calculated only on content with explicit positioning
- Sums exactly to 100 percent

---

## Temporal Analysis

Two temporal indicators are used:

- Daily content volume
- Daily impression (visibility) totals

This allows differentiation between:

- Activity spikes
- Attention spikes

Narrative evolution is interpreted through temporal clustering rather than isolated peaks.

---

## Actor-Type Classification

Accounts are categorized into:

- Official and institutional actors
- Media and news organizations
- Analysts and influencers
- Ordinary users

Comparative analysis focuses on:

- Content production share
- Share of total impressions
- Engagement patterns

This enables differentiation between:

- Narrative construction (top-down)
- Social reaction (bottom-up)

---

## Sensitivity Matrix

A qualitative-quantitative matrix is used to evaluate:

- Narrative weight
- Public sensitivity
- Potential for de-escalation

Scales are normalized into a 1 to 5 system for interpretability.

---

## Limitations

- Data represents a platform-specific slice of public discourse
- High duplication may amplify certain narratives
- Language nuances in Arabic may introduce classification ambiguity
- Absence of private or offline opinion data

---

## Ethical Considerations

- No personal data is exposed
- No attempt is made to identify individuals
- Analysis focuses on aggregated patterns
- Sensitive data is not published
