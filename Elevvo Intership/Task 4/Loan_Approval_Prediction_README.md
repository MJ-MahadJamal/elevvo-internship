# Loan Approval Prediction

## 📌 Project Overview
This project predicts whether a loan application will be **approved or rejected** based on applicant details such as income, credit history, loan amount, and other demographic factors. The goal is to assist financial institutions in **automating loan approval** decisions.

## 📂 Dataset
- **Source:** Loan Approval dataset (CSV format)  
- **Features:** Applicant income, co-applicant income, loan amount, loan term, credit history, gender, marital status, education, self-employment, property area, etc.  
- **Target Variable:** Loan_Status (Approved/Not Approved)  

## 🛠️ Methodology
1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical variables  
   - Scaling numerical features  
2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and correlations  
3. **Model Building**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score  

## 📊 Results
- **Best Model:** Random Forest Classifier  
- **Accuracy:** ~85% (varies with random state)  

## ▶️ How to Run
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
2. Open and run `Loan_Approval_Prediction.ipynb` in Jupyter Notebook or Google Colab.
