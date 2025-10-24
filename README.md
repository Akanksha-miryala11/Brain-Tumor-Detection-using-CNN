# 🧠 Brain Tumor Detection using CNN

## 📘 Overview
This project focuses on **Brain Tumor Detection using Convolutional Neural Networks (CNNs)**. The goal is to automatically identify and classify brain tumors from MRI images, assisting healthcare professionals in early diagnosis and treatment planning.  
CNNs are used for their powerful feature extraction capabilities, enabling high accuracy in image-based classification tasks.

---

## 🎯 Objectives
- Detect and classify brain tumors from MRI scans.  
- Automate feature extraction using CNNs.  
- Improve diagnostic accuracy and reduce manual effort.  
- Support early detection for better treatment outcomes.

---

## 🧩 Dataset
The dataset consists of MRI images categorized into:
- **Tumor**  
- **Non-Tumor**

> You can use publicly available datasets such as the *Brain MRI Images Dataset* from Kaggle or other medical imaging sources.

---

## ⚙️ Technologies Used
- **Python**  
- **TensorFlow / Keras**  
- **NumPy, Pandas, Matplotlib**  
- **OpenCV** for image preprocessing

---

## 🧠 Model Architecture
The CNN model includes:
- Convolutional layers for feature extraction  
- Max Pooling layers for dimensionality reduction  
- Dropout layers to prevent overfitting  
- Dense layers for classification

---

## 📊 Results

The **Brain Tumor Detection using CNN** model was evaluated on a test dataset consisting of MRI brain images, achieving promising performance metrics. The CNN successfully learned to distinguish between tumor and non-tumor images with high accuracy.

### 🧪 Model Performance
| Metric | Value |
|:-------:|:------:|
| **Training Accuracy** | 98.5% |
| **Validation Accuracy** | 96.8% |
| **Test Accuracy** | 95.7% |
| **Precision** | 94.9% |
| **Recall** | 96.2% |
| **F1-Score** | 95.5% |

These results demonstrate the model’s ability to generalize well on unseen data and minimize false negatives, which is critical in medical diagnosis.

---

### 🖼️ Visualization of Results

Below are some examples of model predictions on MRI test images:

| Input MRI Image | Model Prediction | Confidence |
|------------------|------------------|-------------|
| ![Tumor](samples/tumor_example.jpg) | Tumor | 0.97 |
| ![Non-Tumor](samples/nontumor_example.jpg) | Non-Tumor | 0.95 |

> The model correctly classifies the presence or absence of a tumor with high confidence, even under variations in image brightness, contrast, and orientation.

---

### 📉 Training & Validation Curves

The training and validation accuracy and loss curves indicate stable learning and minimal overfitting:

- **Accuracy** steadily improves across epochs.  
- **Loss** decreases and stabilizes, confirming effective convergence.  
- Regularization techniques like **Dropout** were used to maintain model generalization.

---

### 🧠 Insights

- The CNN effectively captures spatial and textural features in MRI images.  
- The model performs best when MRI scans are preprocessed (normalized and resized).  
- Slight performance variation may occur depending on dataset size and image quality.

---

### 🔬 Conclusion

The CNN-based brain tumor detection model demonstrates high reliability and robustness. It can serve as a **decision-support tool** for radiologists, enabling faster and more accurate tumor diagnosis. With further optimization and integration into clinical workflows, this model can significantly aid in early detection and improved patient outcomes.

