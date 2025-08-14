# Movie Recommendation System

## 📌 Description
A movie recommendation engine built using the **MovieLens 100K dataset**, implementing three different algorithms:
- **User-based Collaborative Filtering (User-CF)**
- **Item-based Collaborative Filtering (Item-CF)**
- **Matrix Factorization (SVD)**

## 🔹 Key Steps
- Load ratings and movies data from Kaggle  
- Build user–item rating matrix  
- Compute similarity (cosine similarity for CF)  
- Predict ratings for unseen movies  
- Evaluate recommendations using **Average Precision@5**  

## 🛠 Tech Stack
- Python  
- pandas  
- numpy  
- scikit-learn  
- scipy  
- kagglehub

## ▶️ How to Run
```bash
pip install kagglehub pandas numpy scikit-learn scipy
jupyter notebook Movie_Recommendation_System.ipynb
```
