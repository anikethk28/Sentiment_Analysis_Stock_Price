# Sentiment Analysis for Stock Price Movements


![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/RMarkdown-gray?style=for-the-badge&logo=RMarkdown)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)


This project is an academic exploration implemented in R that investigates the potential predictive power of sentiment analysis on stock price movements. By extracting sentiment scores from financial news headlines, articles, or other textual sources using dictionary-based methods (such as AFINN, NRC, or domain-specific financial lexicons), the analysis aligns daily sentiment aggregates with corresponding stock price data (fetched via quantmod or tidyquant) to examine correlations, lagged effects, and directional influences on returns or volatility. The work combines text preprocessing, feature engineering, time-series visualization, statistical modeling (primarily regression), and interpretation to assess whether public sentiment provides meaningful signals beyond traditional price-based indicators, making it a typical data & predictive analytics course or research demonstration project.

## 🎯 Project Goal

Collect and preprocess historical stock price data for one or more selected companies using reliable financial APIs or packages in R.

Acquire, clean, and tokenize relevant textual data (news headlines or articles) to prepare it for sentiment analysis.

Apply multiple sentiment analysis techniques and lexicons to compute daily sentiment scores (polarity, emotion, or valence) and evaluate their differences in a financial context.

Merge sentiment time series with stock return series, compute lagged features, and perform correlation analysis as well as regression modeling to quantify the sentiment–price relationship.

Visualize key patterns (time-series overlays, scatter plots, correlation heatmaps) and interpret statistical findings to determine whether sentiment can serve as a leading or coincident indicator for stock movements.



