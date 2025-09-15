# Amazon Reviews Sentiment Analysis - Practice
Practice before I start my actual masters project for Sentiment Analysis

## Dataset
- Source: [Amazon Reviews for Sentiment Analysis on Kaggle](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews)
- Download the dataset from Kaggle (requires a free Kaggle account) and extract the archive.
- Copy the `test.ft.txt` file (or other files you plan to use) into the repository (for example as `amazon_reviews_kaggle/test.ft.txt` or rename to `review_labels.txt`).

## Versioning the dataset with Git LFS
If you want to keep the dataset in Git:

1. Install Git LFS on your machine (see [git-lfs.github.com](https://git-lfs.github.com/)).
2. Run `git lfs install` once per machine.
3. In this repository run `git lfs track "amazon_reviews_kaggle/*.txt"` (and `git lfs track "review_labels.txt"` if you keep a copy in the project root). This updates `.gitattributes`.
4. Add your dataset files normally with `git add` and commit. Git LFS will store the large content outside the regular Git history.
5. Push as usual with `git push`; the LFS hooks will upload the data to GitHub's LFS storage.
6. Anyone cloning the repo must also have Git LFS installed; otherwise they will only receive pointer files.

If you prefer not to version the data, keep the large files out of Git and rely on the instructions above to download them locally before running experiments.

## Getting Started
Once the dataset is in place you can iterate locally on notebooks or scripts for preprocessing and modelling without committing the large source data to GitHub.
