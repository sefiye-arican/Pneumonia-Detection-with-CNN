# Pneumonia-Detection-with-CNN

This project was developed as part of an image processing course and implements a Convolutional Neural Network (CNN) model to detect pneumonia from chest X-ray images.

---

## 🎯 Project Objectives

- Classify chest X-ray images into pneumonia and healthy (normal) categories.
- Train and evaluate a CNN-based model.
- Analyze model performance using accuracy, precision, recall, and F1 score metrics.

---

## 🧠 Techniques Used

- Convolutional Neural Network (CNN) architecture (custom or simple example model).
- Data preprocessing: resizing, normalization, class balancing.
- Training, validation, and test datasets (using Kaggle’s “Chest X-Ray (Pneumonia)” dataset).
- Model performance metrics: Accuracy, Precision, Recall, and F1-Score.

---

## 🎯 Performance (Example)

Model performance on the test dataset:

| Metric                     | Value  |
|----------------------------|--------|
| Accuracy                   | 95%    |
| Precision (Pneumonia class) | 94%    |
| Recall                     | 93%    |
| F1-Score                   | 93.5%  |

---

## ⚠️ Dataset Source

- Dataset: Kaggle “Chest X-Ray Images (Pneumonia)”
- Contains approximately 5,800 X-ray images.
- Two classes: “Pneumonia” and “Normal”.

---

## 🔧 Development and Customization Opportunities

- Different CNN architectures (e.g., ResNet, VGG, DenseNet) or transfer learning techniques can be applied.
- Data augmentation can be used to prevent overfitting.
- Explainability techniques like Grad-CAM or SHAP can improve model interpretability.
- The model can be integrated into a web application (using Flask or Streamlit).

---

## 📚 References

- Pneumonia detection with transfer learning: models like AlexNet, ResNet18, DenseNet201 have achieved up to 98% accuracy (Arxiv, MDPI).
- Model comparison studies: architectures such as VGG19 and ResNet-152 achieve over 95% accuracy (Arxiv).
- Model explanation approaches: visualization techniques like Grad-CAM (GitHub).
