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

📄 Deliverables

One Jupyter Notebook containing analysis, code, and results

Kaggle submission files (NMF, LogReg, Linear SVM)

Short discussion on NMF’s limitations and alternative solutions
<img width="229" height="160" alt="image" src="https://github.com/user-attachments/assets/4efda8b8-34e7-4861-b99a-238ccd185bb0" />
