# 🏥 Chest X-ray Classification using the Indiana University Dataset
Developed and implemented a ResNet18-based deep learning model for chest X-ray classification using the Indiana University  Chest X-ray dataset. Applied preprocessing techniques like resizing, normalizing, and augmentation to improve robustness and generalizability.  

## 📌 Project Overview

Chest X-rays are among the most commonly used diagnostic tools in clinical practice. Automating the interpretation of chest radiographs can assist radiologists by flagging potentially abnormal cases. In this project, we apply machine learning techniques to structured report data linked with IU chest X-ray images to predict whether a case is **Normal** or **Abnormal**.

---

## 📁 Project Structure

- **Data Loading**: Importing metadata from IU reports and projection files
- **Data Merging**: Combining labels (Normal/Abnormal) with image filenames
- **Preprocessing**:
  - Dropping irrelevant columns
  - Handling categorical variables
  - Label encoding
- **Feature Engineering**
- **Train-Test Split**
- **Model Training**:
  - Binary classification using traditional ML algorithms
- **Evaluation**:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## 📊 Dataset Details

- Source: Indiana University Chest X-ray Collection
- Image Modality: Grayscale radiographs
- Annotations:
  - Problems (`Normal` vs `Abnormal`)
  - Projection type
  - Clinical impressions
- Preprocessed to binary form for abnormality detection

---

## ✅ Key Highlights

- Converted textual radiology reports into binary labels
- Used structured metadata instead of raw images for initial model prototyping
- Prepared dataset for integration with CNN-based vision models later
- Evaluated models based on accuracy and class distribution handling

---

## 🚀 How to Run

You can run this notebook using Google Colab or Jupyter Notebook:

👉 [Open in Colab](https://www.kaggle.com/code/basitibrahim/iu-dataset/edit)  
→ Upload the notebook: `iu-dataset.ipynb`

---

## 👤 Author

- **Name:** Basit Ibrahim  
- **GitHub:** [github.com/BasitIbrahim11](https://github.com/BasitIbrahim11)  
- **Education:** MS in Artificial Intelligence  
- **Focus:** Medical Imaging | Deep Learning | Classification

---

## 📚 License

This project is intended for educational and research purposes only.
