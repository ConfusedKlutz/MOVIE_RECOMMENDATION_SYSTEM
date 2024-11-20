# 🎥 Collaborative Filtering-Based Movie Recommendation System

This repository contains a **Collaborative Filtering-Based Movie Recommendation System** built using the **MovieLens 20M Dataset** from [GroupLens](https://grouplens.org/datasets/movielens/20m/). The system predicts movie ratings for users and generates personalized recommendations using techniques such as **KNN**, **Matrix Factorization (SVD, SVD++)**, and **Hybrid Models**.

---

## 📂 Dataset: MovieLens 20M

The dataset is sourced from GroupLens and contains:
- **20 million ratings** from **138,000 users** for **27,000 movies**.
- Ratings range from **0.5 to 5.0**.
- Additional metadata like movie titles, genres, and release years.

You can download the dataset [here](https://grouplens.org/datasets/movielens/20m/).

---

## 🚀 Features

- **Collaborative Filtering Models**:
  - **KNN-based Methods**: User-based and Item-based filtering.
  - **Matrix Factorization**: SVD and SVD++ for latent factor analysis.
  - **Hybrid Models**: Combines collaborative filtering with machine learning (e.g., XGBoost).
- **Performance Metrics**:
  - Evaluates models using **Root Mean Square Error (RMSE)** on the test set.
- **Interactive Recommendations**:
  - Users can input favorite movies to receive personalized recommendations.
- **Scalable Implementation**:
  - Handles large datasets with efficient sparse matrix techniques.

---

## 🛠 Setup and Installation

### Requirements
Ensure the following dependencies are installed:

```bash
pandas
numpy
scikit-learn
surprise
xgboost
fuzzywuzzy
matplotlib
seaborn
