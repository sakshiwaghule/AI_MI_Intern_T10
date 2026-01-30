# AI_MI_Intern_T10
# MNIST Handwritten Digits Dataset Summary
# Project Overview
This repository contains a dataset of handwritten digits used for training and evaluating machine learning models, specifically the **K-Nearest Neighbors (KNN)** algorithm. The goal is to correctly classify images into one of ten digit categories (0-9).
# Dataset Specifications
* **File Name:** `mnist_dataset.csv`
* **Total Samples:** 42,000 images
* **Features:** 784 columns (`pixel0` to `pixel783`)
* **Image Size:** 28 x 28 pixels (grayscale)
* **Data Range:** 0 (Black) to 255 (White)
# Implementation Workflow
1. **Exploratory Data Analysis (EDA):** Visualized pixel data to confirm the structure of handwritten digits.
2. **Preprocessing:** Applied `StandardScaler` to normalize pixel intensities, ensuring distance-based calculations in KNN remain unbiased.
3. **Model Training:** Implemented a **K-Nearest Neighbors** classifier.
4. **Hyperparameter Tuning:** Evaluated multiple values of  (3, 5, 7, 9) to find the optimal balance between bias and variance.
5. **Evaluation:** Utilized a **Confusion Matrix** to identify specific digit misclassifications and calculated accuracy scores.
# Key Results
* **Optimal K:**  provided the highest accuracy in testing.
* **Model Accuracy:** Achieved approximately **~97%** accuracy on the standard digits test set.
* **Performance:** The model demonstrates high reliability, with minimal confusion between visually similar digits (e.g., 4 and 9).
# Requirements
* Python 3.x
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
