# 🩺 Explainable and Uncertainty-Aware Diabetic Retinopathy Detection

## Overview

This project presents an explainable and uncertainty-aware deep learning framework for automated diabetic retinopathy (DR) detection from retinal fundus images.

The system combines DenseNet121 with explainable AI techniques and uncertainty estimation to improve the transparency and reliability of predictions for clinical decision support.

---

## Features

* DenseNet121 (ImageNet pretrained)
* CLAHE image preprocessing
* Binary Focal Loss
* Threshold Optimization
* Grad-CAM Visualization
* SHAP Explainability
* Monte Carlo Dropout Uncertainty Estimation
* Reliability Diagram
* Expected Calibration Error (ECE)
* Clinical Decision Report
* Error Analysis Dashboard

---

## Dataset

APTOS 2019 Blindness Detection Dataset

---

## Final Performance

| Metric                     | Value      |
| -------------------------- | ---------- |
| Accuracy                   | **95.08%** |
| Precision                  | **96.27%** |
| Recall                     | **92.81%** |
| Specificity                | **96.98%** |
| F1 Score                   | **94.51%** |
| ROC-AUC                    | **98.52%** |
| Brier Score                | **0.1216** |
| Expected Calibration Error | **0.2290** |

---

## Project Structure

```
models/
figures/
outputs/
notebook/
```

---

## Technologies

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* SHAP
* Scikit-learn

---

## Future Work

* Streamlit Web Application
* Multi-class DR Detection
* Improved Calibration
* Clinical Deployment
