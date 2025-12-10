# bbc-news-classification-and-NMF-limitations
This project focuses on classifying BBC News articles into topic categories using both unsupervised and supervised machine learning methods. It also includes a second component analyzing the limitations of sklearn’s NMF on a movie-ratings matrix.

📚 Part 1 — BBC News Classification (Kaggle)

Key steps in the notebook include:

Exploratory Data Analysis (EDA) and visualization

Text preprocessing: cleaning, tokenization, and TF-IDF feature extraction

Unsupervised learning: NMF topic modeling and interpretation

Supervised learning: Logistic Regression and Linear SVM

Performance comparison and Kaggle submission generation

📉 Part 2 — Limitations of sklearn’s NMF (Movie Ratings)

Re-evaluates the matrix factorization approach from a previous recommender-system task:

Baseline predictors: global mean, user mean, item mean

sklearn NMF with dense imputation and RMSE evaluation

Analysis of why sklearn’s NMF underperforms (no bias terms, dense fill, loss function issues)

Suggestions for improvement (biased MF, weighted loss, better algorithms)


<img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/59650404-450c-4853-b0d7-e9eb9e0bdc9e" />


