# Data Description

## Overview

This project is based on a dataset of Arabic-language social media content related to Kuwait and the Iran 2026 War.

The dataset captures public discourse, reactions, and narrative construction in a high-intensity regional context.

---

## Dataset Characteristics

- Platform: X (Twitter)
- Language: Arabic
- Geographic focus: Kuwait
- Timeframe: Late February 2026 – Early April 2026

---

## Size and Structure

- Total rows: ~29,000
- Unique posts: ~1,800
- Unique users: ~1,600
- Number of variables: 40+

---

## Data Fields

The dataset includes multiple types of variables:

### Content-level fields
- Post text
- Timestamp
- Post ID
- Language

### User-level fields
- Username
- Profile description
- Follower count
- Account activity metrics

### Engagement metrics
- Views
- Impressions
- Likes
- Replies
- Reposts

### Relational indicators
- Reply relationships
- Quote relationships

---

## Data Quality Notes

Several important characteristics affect interpretation:

### High duplication
The dataset contains repeated entries of the same post due to:

- Reposts and platform dynamics
- Scraping overlaps

Duplication is intentionally preserved and analyzed as part of narrative amplification.

---

### Missing values

Certain fields are largely empty, including:

- Reply-to identifiers
- Quote-related metadata

These are treated as structural absences rather than errors.

---

### Inconsistent labeling

Some categorical fields (e.g., country) contain multiple naming formats, such as:

- Arabic variants
- English variants
- Mixed-language entries

Standardization is applied where necessary.

---

## Analytical Implications

- Row count does not equal unique content
- High-engagement posts may be overrepresented
- Narrative dominance must be interpreted alongside user-level distribution

---

## Data Access

The raw dataset is not included in this repository.

This decision is based on:

- Privacy considerations
- Platform policies
- Responsible research practices

Only aggregated and non-sensitive outputs are shared.
