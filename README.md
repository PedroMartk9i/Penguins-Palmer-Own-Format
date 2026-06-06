# Palmer Penguins: Morphological Differentiation Across Species

## Overview

Exploratory Data Analysis (EDA) on the Palmer Penguins dataset, completed as part of the **Statistics for Data Science** course in the Master of Data Science program at **Universidad Autónoma de Bucaramanga (UNAB)**, 2026.

The study investigates morphological differences across three penguin species (Adélie, Chinstrap, Gentoo) collected from three islands in the Palmer Archipelago, Antarctica. The goal is to identify patterns, trends, and statistical relationships between physical measurements (bill length, bill depth, flipper length, body mass) and categorical variables (species, island, sex).

## Methodology

- Descriptive statistics (mean, median, standard deviation, quartiles)
- Distribution analysis with histograms and KDE plots
- Outlier detection via boxplots
- Correlation analysis (Pearson/Spearman) with heatmaps
- Bivariate and multivariate visualizations (scatterplots, pairplots)
- Hypothesis formulation based on observed patterns

## Tech Stack

- Python 3, pandas, NumPy, seaborn, matplotlib, SciPy
- Google Colab

## Key Findings

- **Gentoo** penguins show significantly larger flipper length and body mass compared to Adélie and Chinstrap
- Bill length and bill depth show species-dependent correlation patterns (Simpson's paradox)
- Clear morphological clustering by species supports classification feasibility
- Consistent sexual dimorphism across all species enables heuristic sex inference for unclassified records

## Repository Structure

```
├── Pedro_Martinez_Actividad1.ipynb   # Full EDA notebook
├── penguins_size (1).csv             # Palmer Penguins dataset
└── README.md
```

## Course

**Statistics for Data Science** — M.Sc. Data Science, UNAB (2026)

## Author

**Pedro Esteban Martínez Santamaría**
