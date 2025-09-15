# Amazon Reviews Sentiment Analysis - Practice
Practice before I start my actual masters project for Sentiment Analysis

## Dataset
- Source: [Amazon Reviews for Sentiment Analysis on Kaggle](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews)
- Download the dataset from Kaggle (requires a free Kaggle account) and extract the archive.
- Keep a compressed copy in this repository (for example `review_labels.txt.gz`). Create it locally with `gzip -c review_labels.txt > review_labels.txt.gz`. The `.gz` stays below GitHub's 100 MB limit.
- After cloning the repo, restore the raw dataset as needed with `gunzip -k review_labels.txt.gz` (the `-k` flag keeps the archive).
- If you prefer not to commit any data, keep the Kaggle files outside Git and follow the download steps locally before running experiments.

## Getting Started
Once the dataset is in place you can iterate locally on notebooks or scripts for preprocessing and modelling without committing the large source data to GitHub.
