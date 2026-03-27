# Pneumonia Detection using Chest X-Ray Images

## Project Overview
This project leverages deep learning to detect **pneumonia** from chest X-ray images. Using **transfer learning** with pre-trained models (InceptionV3 and DenseNet201), and an **ensemble approach** that combines their strengths, the system aims to provide accurate and reliable predictions to assist medical professionals.

## Dataset
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data

It contains:
- **Normal cases**: Chest X-rays of healthy patients  
- **Pneumonia cases**: Chest X-rays of patients diagnosed with pneumonia  

## Methodology
1. **Data Preprocessing**  
   - Image resizing and normalization  
   - Train-validation-test split  

2. **Model Architectures**  
   - **InceptionV3**: Captures fine-grained features with deep convolutional layers  
   - **DenseNet201**: Efficient feature reuse and gradient flow  
   - **Ensemble Model**: Combines predictions from both models to improve robustness and accuracy  

3. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

## Goals
- Achieve high accuracy in pneumonia detection  
- Demonstrate the effectiveness of ensemble learning in medical imaging  
- Provide a reproducible pipeline for healthcare AI research  

