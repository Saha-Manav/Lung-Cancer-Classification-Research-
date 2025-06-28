# 🩺 Lung Cancer Classification Research

This is a research-driven deep learning project focused on the **classification of lung cancer** using CT scan images. The study evaluates multiple CNN architectures to accurately classify lung conditions into three categories: **Normal**, **Benign**, and **Malignant**, aiming to assist radiologists and improve early cancer detection.

## 📌 Objective

- Develop an automated lung cancer detection system using CT-Scan image classification.
- Compare the performance of CNN architectures (ResNet50, DenseNet121, MobileNetv2).
- Analyze trade-offs in terms of accuracy, training time, and resource usage.
- Build a lightweight and scalable diagnostic system for clinical settings.

## 🧠 Methodology

- **Dataset:** IQ-OTH/NCCD Lung CT Scan Dataset (Kaggle)
- **Classes:** `Normal`, `Benign`, `Malignant`
- **Preprocessing:** Resizing, normalization, data augmentation, oversampling
- **Models Used:**
  - `ResNet50`: Deep residual learning
  - `DenseNet121`: Feature reuse with dense connections
  - `MobileNetv2`: Efficient model for resource-constrained environments
- **Metrics:** Accuracy, Confusion Matrix, Precision, Recall, F1-Score

## 📂 Dataset

- Name: IQ-OTH/NCCD (Iraq Oncology Teaching Hospital)
- Link: [IQ-OTH/NCCD on Kaggle](https://www.kaggle.com/datasets)
- Format: CT scan slices (PNG/JPG)

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** TensorFlow, Keras, NumPy, OpenCV, Matplotlib, Scikit-learn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Lung-Cancer-Classification-Research.git
   cd Lung-Cancer-Classification-Research
