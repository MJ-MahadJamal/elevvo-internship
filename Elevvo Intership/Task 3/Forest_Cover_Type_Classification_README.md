# Forest Cover Type Classification

## 📌 Project Overview
This project classifies **forest cover types** using cartographic and environmental features, such as elevation, slope, soil type, and wilderness area. This is a **multi-class classification** task.

## 📂 Dataset
- **Source:** UCI ML Forest Cover Type dataset  
- **Rows:** ~581,012 samples  
- **Features:** 54 attributes (numeric + binary)  
- **Target Variable:** Cover_Type (7 forest categories)  

## 🛠️ Methodology
1. **Data Preprocessing**
   - Standard scaling  
   - Train/test split  
2. **Model Building**
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Gradient Boosting Classifier  
3. **Evaluation**
   - Accuracy Score  
   - Confusion Matrix  

## 📊 Results
- **Best Model:** Gradient Boosting Classifier  
- **Accuracy:** ~90%  

## ▶️ How to Run
1. Install dependencies:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```
2. Run `Forest_Cover_Type_Classification.ipynb` in Jupyter Notebook.
