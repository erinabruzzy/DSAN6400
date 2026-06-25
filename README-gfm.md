# Comparative Social Network Analysis of the Bible and the Quran
Erin Brzusek

# DSAN6400: Network Analytics

## Project Overview

This repository contains a network analytics project that analyzes and
contrasts the structural topologies of sacred texts using **Social
Network Analysis (SNA)**. By modeling character co-occurrences as
networks, this study evaluates how distinct literary styles,
specifically, the **chronological narratives** of the Christian Gospels
versus the **thematic discourses** of the Islamic Surahs, influence
network properties.

## Methodology

To account for variations in text length, structural layout, and
narrative framing, this pipeline implements:

- **Entity Resolution:** Cross-mapping shared Abrahamic figures (e.g.,
  *Moses/Musa*, *Mary/Maryam*)
- **Normalization:** Standardizing edge weights to compare global
  density, graph diameter, and average path lengths
- **Centrality Distribution Scaling:** Evaluating structural prominence
  using: **Degree Centrality**, **Betweenness Centrality**, and
  **Closeness & Eigenvector Centralities**

------------------------------------------------------------------------

## Data Sources

This project relies on structured textual data extracted from the
following public repositories:

### 1. The Holy Bible

- **Source Dataset:** *BibleData: Structured Datasets from the Holy
  Bible* (v1.0)
- **Citation:** Stephenson, B. (2026). *BibleData: Structured Datasets
  from the Holy Bible (Version 1.0)* \[Data set\]. Zenodo.
  <https://doi.org/10.5281/zenodo.19539956>
- **Scope:** Micro-parsed verse-by-verse data

### 2. The Holy Quran

- **Source API:** *Al Quran Cloud API*
- **Documentation:**
  [api.alquran.cloud](https://www.google.com/search?q=https://api.alquran.cloud)
- **Scope:** Complete textual pull of the 114 Surahs utilizing standard
  English translations (e.g., Sahih International) for character entity
  extraction

### 3. Cross-Text Entity Matrix

- **Reference:** *List of people in both the Bible and the Quran*
  (Wikipedia / Abrahamic Study Hall). Used to construct a dictionary
  matching explicit English names with their Arabic transliterated
  counterparts.
