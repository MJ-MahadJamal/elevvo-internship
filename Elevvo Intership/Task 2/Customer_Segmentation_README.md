# Customer Segmentation

## 📌 Description
This project performs customer segmentation using the **Mall Customers Dataset** to identify groups with similar spending patterns.  
It applies **K-Means clustering** with optimal `k` determined using the **Elbow method** and **Silhouette score**.

## 🔹 Key Steps
- Load dataset from Kaggle or local file  
- Perform Exploratory Data Analysis (EDA) with scatter plots  
- Feature scaling (StandardScaler)  
- Determine best `k` using Elbow method & Silhouette score  
- Apply K-Means clustering  
- Visualize clusters in scaled and original space  
- Analyze average spending per cluster  

## 🛠 Tech Stack
- Python  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Customer_Segmentation.ipynb
```
