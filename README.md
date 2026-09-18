# AI Resume Screening System — Week 2: Data Cleaning & Transformation

Virtual Data Science Apprentice — Python Specialist Intern (Week 2 of 4)

## Overview

This week's deliverable documents the data cleaning and transformation strategy for the raw resume text used in the **AI Resume Screening System**, preparing it for exploratory analysis (Week 3) and modeling (Week 4).

## Objective

Draft a detailed plan for handling data inconsistencies, missing values, duplicates, outliers, and text normalization/vectorization using Python — with an emphasis on documentation and planning rather than raw code output.

## What's in This Report

- **Missing value handling** — detection and resolution strategy for empty resume text or missing category labels.
- **Duplicate handling** — normalized-text duplicate detection and removal.
- **Noisy text cleanup** — stripping HTML, URLs, special characters, and inconsistent casing while preserving meaningful technical tokens (e.g., "C++", "SQL").
- **Outlier handling** — resume-length outliers and category-level rarity, flagged for review rather than blind deletion.
- **NLP preprocessing pipeline** — tokenization → stopword removal → lemmatization → skill-term normalization.
- **Feature engineering** — TF-IDF vectorization (primary) and optional sentence embeddings; label encoding; class-imbalance handling; scaling considerations.
- **Anticipated challenges and solutions** — loss of meaning from aggressive cleaning, vocabulary sparsity, inconsistent skill naming, and data-leakage risk during resampling.

## Deliverable

| File | Description |
|---|---|
| `Week2_Data_Cleaning_and_Transformation.docx` | Full data cleaning & transformation strategy (Word document) |

## Tech Stack

Python · pandas · numpy · re · nltk / spaCy · scikit-learn (TfidfVectorizer, LabelEncoder) · imbalanced-learn (optional)

## Status

✅ Week 2 complete — cleaning/transformation strategy finalized, ready for Week 3 (EDA & Visualization Strategy).

## Author

[Your Full Name]
