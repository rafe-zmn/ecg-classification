# ECG Classification

A machine learning project that classifies ECG images into four classes:

- Normal Rhythm
- Myocardial Infarction (MI)
- History of MI
- Abnormal Heartbeats

Built using Convolutional Neural Networks (CNN) and compared with traditional ML models (SVM, XGBoost, AdaBoost, EfficientNet).

---

## Models Used

-  CNN (Custom)
-  EfficientNet (Pretrained)
-  SVM, XGBoost, AdaBoost (Traditional ML)

---

## Results Summary

| Model        | Accuracy | 
|--------------|----------|
| CNN          |   98%    | 
| EfficientNet |   88%    | 
| XGBoost      |   93%    | 
| AdaBoost     |   95%    | 
| SVM          |   93%    | 

> Grad-CAM was used for model explainability.

---

## Dataset

Data was collected from publicly available sources:
- Kaggle
- Mendeley
- NIH (National Institutes of Health)

> Stored in Google Drive due to size and licensing — **not included in this repo**.

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive
3. Set data paths
4. Run training or evaluation



