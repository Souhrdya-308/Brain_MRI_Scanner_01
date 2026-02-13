# 🧠 Brain Tumor MRI Classification using Deep Learning

This project uses a **Convolutional Neural Network (CNN)** to classify brain MRI images into  
**Glioma, Meningioma, Pituitary Tumor, or No Tumor**.  
It also provides **Grad-CAM visualizations** to explain model predictions through an interactive **Gradio web application**.

---

## 📌 Project Overview

Brain tumor detection from MRI scans is a complex and time-sensitive task.  
This project demonstrates how deep learning can assist in **automated brain tumor classification** while maintaining **model transparency** using Grad-CAM.

The system is designed for **educational and research purposes** and showcases end-to-end AI development:
data preprocessing → model training → evaluation → explainability → deployment.

---

## 🚀 Features

- ✅ Brain MRI image classification (4 classes)
- 📈 ~97% accuracy on test data
- 📊 Prediction confidence visualization
- 🔍 Grad-CAM heatmaps for explainable AI
- 🖥️ Interactive Gradio-based web application
- ⚠️ Medical disclaimer for ethical usage

---

## 🧬 Tumor Classes

- Glioma  
- Meningioma  
- Pituitary Tumor  
- No Tumor  

---

## 🧠 Model Architecture

- Convolutional Neural Network (CNN)
- Multiple `Conv2D` + `MaxPooling` layers
- Fully connected `Dense` layers
- Softmax output layer for multi-class classification
- Input image size: **256 × 256**

---

## 📈 Performance

| Metric | Value |
|------|------|
| Test Accuracy | ~97% |
| Evaluation | Confusion Matrix + Classification Report |

✔ The model performs well overall but may occasionally confuse **glioma and meningioma**, which is a known challenge in medical imaging due to similar visual features.

---



## 📂 Dataset

- Publicly available brain MRI datasets
- Preprocessed and labeled into 4 tumor classes
- Images normalized and resized to 256 × 256

> ⚠️ Dataset is used strictly for **educational and research purposes only**

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/brain-tumor-mri-classifier.git
cd brain-tumor-mri-classifier

