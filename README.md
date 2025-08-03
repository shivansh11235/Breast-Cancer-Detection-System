# Breast-Cancer-Detection-System
📌 Problem Statement: Breast cancer is one of the most common and deadly cancers among women worldwide. Early detection significantly increases the chances of successful treatment and survival. Medical imaging techniques such as mammography, ultrasound, and histopathology are commonly used to screen for breast cancer, but manual interpretation by radiologists can be time-consuming and prone to human error.

This project aims to build a machine learning system that can automatically detect and classify breast cancer from medical images. The system will analyze input images and predict whether a tumor is benign (non-cancerous) or malignant (cancerous), helping assist radiologists in faster and more accurate diagnosis.

🎯 Type of Prediction / Classification This is a binary classification problem. The model will classify each input image into one of two categories:

Benign (non-cancerous)

Malignant (cancerous)

In some datasets, there may be additional subtypes (multi-class classification), but the core objective here is to detect malignancy — hence binary classification is the main focus.

🏁 Project Goals and Success Criteria 📌 Goals Build an image classification model using Convolutional Neural Networks (CNNs) capable of accurately distinguishing between benign and malignant tumors.

Use real-world breast cancer imaging datasets to train, evaluate, and validate the model.

Improve model performance using data preprocessing, augmentation, and transfer learning.

Ensure the model is interpretable and could assist medical professionals.

Success Criteria & Quantitative Metrics:

Accuracy ≥ 90%

F1-score ≥ 0.85

Precision and Recall should be balanced (especially minimizing false negatives — malignant cases classified as benign)

ROC-AUC score to assess performance across thresholds

Qualitative Metrics:

-Clear and interpretable visualizations of model predictions (e.g., Grad-CAM, confusion matrix)

-Well-documented and reproducible workflow

-Ethical discussion and limitations clearly addressed
