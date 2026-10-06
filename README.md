# Respiratory Disease Prediction using Machine Learning

## Project Overview

This project focuses on predicting respiratory diseases from lung auscultation audio using Machine Learning and Deep Learning techniques.

## Dataset

The project uses the Respiratory Sound Database containing lung sound recordings and patient diagnosis information.

The dataset contains 920 audio recordings from 126 patients.

## Preprocessing

The following preprocessing steps were performed:

1. Audio loading
2. Noise reduction
3. MFCC feature extraction
4. MFCC normalization
5. Feature preparation for Machine Learning models

## Machine Learning Models

Four models were implemented:

- Support Vector Machine (SVM)
- Random Forest
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

## Results

The final models achieved approximately:

| Model | Accuracy |
|-------|----------|
| SVM | 86.41% |
| Random Forest | 86.96% |
| ANN | 86.41% |
| CNN | 86.96% |

Random Forest and CNN achieved the highest overall accuracy of approximately 86.96%.

## Project Structure

```text
Respiratory_Disease_Prediction/
│
├── dataset/
├── models/
├── notebooks/
│   └── 01_data_exploration.ipynb
├── results/
│   ├── ann_confusion_matrix.png
│   ├── cnn_confusion_matrix.png
│   ├── random_forest_confusion_matrix.png
│   ├── svm_confusion_matrix.png
│   ├── roc_curve_comparison.png
│   ├── precision_recall_curve_comparison.png
│   └── model_comparison.csv
│
├── requirements.txt
└── README.md