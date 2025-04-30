# STA2201: Predicting Pokémon Types with Clustering and Classification

This repository contains the code and documentation for our STA2201 final project at the University of Toronto, Winter 2025.

## Overview

Our project investigates whether a Pokémon’s type can be predicted from its visual and statistical attributes using unsupervised and supervised learning techniques. We explore clustering and classification performance on two datasets: one with 809 PNG images of Pokémon and another with 801 Pokémon statistics (e.g., height, weight, attack, defense).

Key techniques used include:
- Principal Component Analysis (PCA)
- Uniform Manifold Approximation and Projection (UMAP)
- K-means Clustering (including weighted and K-means++)
- Linear Discriminant Analysis (LDA)
- Gradient Boosting (XGBoost)

## Research Question

> Can clustering and classification methods uncover or predict a Pokémon’s type based on its image and statistical features?

## Dataset

We used two Kaggle datasets:
- [Pokémon Images and Types](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types)
- [Complete Pokémon Stats Dataset](https://www.kaggle.com/datasets/rounakbanik/pokemon)

## File Structure

```bash
STA2201/
├── Data/                   # Raw and processed data files
├── Code/                   # RMarkdown analysis scripts
│   ├── Pretreatment.R
│   ├── DimensionReduction/
│   ├── Clustering/
│   ├── Classification.Rmd
│   └── Code.Rmd            # Aggregate code file (all of the above)
├── Report/
│   └── FinalReport.pdf     # Full project report
├── Slides/
│   └── Presentation.pdf    # Presentation slides
└── README.md               # This file
