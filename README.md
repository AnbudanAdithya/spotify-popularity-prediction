# 🎵 Spotify Song Popularity Prediction

## Executive Summary
The music industry spends millions of dollars signing artists, producing albums, and funding marketing campaigns—often with no data-driven basis for deciding which songs deserve that investment. This project builds a multi-class classification model to predict whether a Spotify song will achieve High, Medium, or Low popularity based on its audio features before release. 

Missing a genuine hit is significantly more costly than over-investing in one mediocre song. This model acts as a data-backed screening tool for Record label A&R teams, music producers, and streaming platform editorial curators deciding where to allocate marketing investment.

## Dataset
* **Source:** Spotify Tracks Dataset (114,000 Songs across 114 genres)
* **Target Variable:** Popularity (Binned into Low: 0-40, Medium: 41-65, High: 66-100)
* **Features:** Audio features including Danceability, Energy, Loudness, Acousticness, Liveness, Valence, Tempo, and engineered features like `dance_energy` and `energy_acoustic_ratio`.

## Model Performance
The best-performing model is a **Random Forest Classifier**:
* **Accuracy:** 74% on unseen data.
* **Weighted F1-Score:** 72.7%.
* The model correctly identifies nearly three out of every four songs' commercial potential in under 10 seconds.

## Files in this Repository
* `24030302038_S Adithya.ipynb`: The complete Jupyter Notebook containing data preprocessing, EDA, feature engineering, and model training/evaluation.
* `Spotify_Music.csv`: The dataset used for training the model.
* `24030302038_Business Report.pdf`: A comprehensive business report detailing the executive summary, methodology, limitations, and strategic recommendations.
