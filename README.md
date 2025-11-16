# World Music Tracks
This project is a data science exploration that analyzes the dataset of World Music Tracks. The goal of this project is to predict the release year of the song by looking art its audio characteristics such as dancability, energy, etc.

The analysis follows:
1. Data Loading and Exploratory Data Analysis (EDA)
2. Data Cleaning and Preprocessing
3. Feature Selection
4. Model Training (Linear Regression)
5. Model Evaluation

## Metodology and Model

Dataset: The analysis was performed on the WorldHits.csv dataset which includes various acoustic and measurable attributes of music tracks from https://www.kaggle.com/datasets/thebumpkin/300-world-music-tracks-with-spotify-data
Preprocessing: Categorical columns (Track, Artist, Album) were dropped. Corellation analysis was performed to understand the relationship between features and Year.
Model: A Linear Regression model was trained on the processed data.
Splitting: Data was split into training (%80) and testing (%20).

## Results and Evaluation
Trained Linear Regression model showed limited success in predicting the release year. The results indicate that a simple linear relationship is not enough to explain the variance in the track years.
