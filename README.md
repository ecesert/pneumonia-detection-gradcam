# Pneumonia Detection with Grad-CAM (Chest X-Ray)

This project detects **PNEUMONIA vs NORMAL** from chest X-ray images using **Transfer Learning (EfficientNet)** and explains predictions with **Grad-CAM**.  
A **Gradio interface** is provided for interactive testing.

## Dataset
Kaggle: Chest X-Ray Images (Pneumonia)  
Dataset is downloaded via Kaggle API (credentials are not included in this repo).

## Method
- CNN + Transfer Learning (EfficientNet)
- Binary Classification (sigmoid)
- Class imbalance handled with class_weight
- Explainability: Grad-CAM
- Demo UI: Gradio (share link)

## Results (Test Set)
- Accuracy: ~0.89
- Pneumonia Recall: ~0.95

## Training Metrics
[Training Metrics]
<img width="1900" height="620" alt="image" src="https://github.com/user-attachments/assets/1395c569-19f1-454c-85b6-07586314f179" />

## Confusion Matrix
![Confusion Matrix](assets/confusion_matrix.png)

## Grad-CAM Example
![Grad-CAM](assets/gradcam_sample.png)

## How to Run (Colab)
1. Install requirements
2. Download dataset via Kaggle API
3. Train / load model
4. Run Gradio interface

## Requirements
See `requirements.txt`
