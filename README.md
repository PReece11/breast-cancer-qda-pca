# 🧬 Breast Cancer Classification (PCA → QDA)

This project uses the **Breast Cancer Wisconsin Diagnostic** dataset (569 observations, 30 numeric features) to classify tumors as **malignant vs benign**. :contentReference[oaicite:1]{index=1}

## Goal
Can tumor shape/texture features accurately classify breast tumors as malignant or benign? :contentReference[oaicite:2]{index=2}

## Approach
- Assumption checks showed **LDA was not appropriate** due to unequal covariance matrices (Box’s M test significant). :contentReference[oaicite:3]{index=3}  
- Used **PCA** to reduce multicollinearity and dimensionality, then applied **QDA**. :contentReference[oaicite:4]{index=4}

## Results (Test Set)
- Accuracy: **0.95** :contentReference[oaicite:5]{index=5}  
- F1 (Malignant): **0.96** :contentReference[oaicite:6]{index=6}  
- F1 (Benign): **0.92** :contentReference[oaicite:7]{index=7}  

## How to Run
```bash
pip install -r requirements.txt
