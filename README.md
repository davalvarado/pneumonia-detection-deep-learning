# Evaluating Deep Learning Models for Pneumonia Detection

## Overview

This project evaluates deep learning approaches for detecting pneumonia from chest X-ray images. A baseline Convolutional Neural Network (CNN) was compared against a MobileNetV2 transfer learning model to determine which approach produced the strongest performance.

## Dataset

- Chest X-Ray Images (Pneumonia) Dataset
- Source: Kaggle
- Binary classification:
  - NORMAL
  - PNEUMONIA

## Methods

Two models were evaluated:

1. Baseline CNN
2. MobileNetV2 Transfer Learning Model

Images were resized to 224x224 pixels and normalized before training.

## Results

| Metric | CNN | MobileNetV2 |
|----------|----------|----------|
| Test Accuracy | 72.6% | 75.0% |
| Pneumonia Recall | 0.99 | 1.00 |
| False Negatives | 2 | 0 |

*Note: Performance metrics may vary slightly between runs due to random initialization and training variability.*

MobileNetV2 achieved the strongest overall performance and eliminated false negatives within the testing dataset.

## Key Findings

- Dataset class imbalance influenced model behavior.
- The baseline CNN showed signs of overfitting.
- MobileNetV2 improved accuracy and recall.
- Transfer learning provided the best overall performance.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Author

David Alvarado
Master of Science in Data Science
Bellevue University
