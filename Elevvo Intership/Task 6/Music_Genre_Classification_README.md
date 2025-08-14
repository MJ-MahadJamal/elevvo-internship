# Music Genre Classification

## 📌 Description
Classifies songs into genres using the **GTZAN dataset** with two approaches:  
- **Tabular Approach**: Extract **MFCC features** with `librosa` → classify using **RandomForest**  
- **Image Approach**: Generate **Mel-spectrogram images** → train CNN via **MobileNetV2 transfer learning**

## 🔹 Key Steps
- Load audio dataset from Kaggle  
- Extract MFCCs (tabular) and Mel-spectrograms (image)  
- Split into train/test sets  
- Train RandomForest classifier for tabular approach  
- Train MobileNetV2 CNN for spectrogram approach  
- Evaluate with accuracy, classification report, confusion matrix  

## 🛠 Tech Stack
- Python  
- librosa  
- scikit-learn  
- tensorflow  
- matplotlib  
- joblib

## ▶️ How to Run
```bash
pip install kagglehub librosa soundfile scikit-learn tensorflow matplotlib joblib
jupyter notebook Music_Genre_Classification.ipynb
```
