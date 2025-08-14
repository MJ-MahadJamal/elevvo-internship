# Student Score Prediction

## 📌 Project Overview
This project predicts a student's **exam score** based on the **number of study hours**. It demonstrates a simple **linear regression** model for predictive analytics.

## 📂 Dataset
- **Source:** Hours vs Scores dataset  
- **Rows:** 25 samples  
- **Features:** Hours of study  
- **Target Variable:** Score (0–100)  

## 🛠️ Methodology
1. **Data Preprocessing**
   - Load CSV data  
   - Check for missing values  
2. **Model Building**
   - Simple Linear Regression  
3. **Evaluation**
   - Mean Absolute Error (MAE)  
   - R² Score  

## 📊 Results
- Predicted scores closely match actual scores for test data  
- Example: 9.25 hours study → ~93.9 predicted score  

## ▶️ How to Run
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
2. Run `Student_Score_Prediction.ipynb` in Jupyter Notebook.
