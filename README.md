# Amazon-Recommendation-System
Recommendation system built on Amazon Electronics dataset (~65K ratings), applying user-user collaborative filtering, matrix factorization, and model evaluation with Precision@K and RMSE.


Project Overview

This project introduces and implements various recommendation system algorithms, exploring both memory-based collaborative filtering and model-based approaches. It serves as a hands-on learner notebook with detailed code and explanations.

Techniques Implemented

User-User Similarity (Cosine, Pearson)

Item-Item Similarity

Matrix Factorization (SVD, FunkSVD)

Evaluation: RMSE, Precision@K, Recall@K, F1 Score

Dataset

Synthetic + real datasets (MovieLens subset)

Ratings data with userId, itemId, rating, timestamp

Key Learnings

How similarity metrics affect recommendations

Impact of hyperparameter tuning (k, min_k)

Trade-off between accuracy and coverage

Results

User-User CF achieved balanced precision/recall

SVD outperformed baseline in RMSE

Best models identified for top-N recommendation tasks

How to Run
jupyter notebook "Recommendation_Systems_Learner_Notebook_Full_Code_upd.ipynb"
