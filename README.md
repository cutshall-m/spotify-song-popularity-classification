# Spotify Song Popularity Classification

This repository contains a machine learning workflow that explores the Spotify TidyTuesday dataset (2020-01-21)[cite: 1] to predict song popularity based on audio features (such as acousticness, energy, danceability, and loudness) and categorical metadata (like playlist subgenres).

## Project Overview
* **Problem Type:** Binary Classification (Popular = 1 if popularity score $\ge 50$, Non-Popular = 0 otherwise).
* **Dataset Source:** [TidyTuesday Spotify Songs Dataset](https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-01-21/spotify_songs.csv)[cite: 1]

## Key Findings & Features
* **Data Preprocessing:** Cleaned duplicate entries, handled missing values, and created a binary outcome column based on track popularity thresholds.
* **Influential Features:** Features that had the strongest influence on the classification outcome included `playlist_subgenre`, `loudness`, and `energy`.
* **Model Performance:** While the dataset presented challenges due to overlapping feature distributions, the classification model performed better than an intercept-only baseline model.

## File Structure
* `Cutshall_Matthew_Main.ipynb` (or `.html`) - The primary Jupyter notebook containing the complete EDA, feature engineering, and modeling steps.

## Technologies Used
* Python (Pandas, NumPy, Matplotlib, Seaborn)
