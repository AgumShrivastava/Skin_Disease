# 🩺 Skin Disease Classification using Deep Learning (CNN)

 

---

# 📖 Overview

This project implements a **Convolutional Neural Network (CNN)** to classify skin lesions into **seven different disease categories** using the **HAM10000** dataset.

The notebook covers the complete deep learning pipeline, including data preprocessing, visualization, handling class imbalance, model training, evaluation, and prediction.

The objective is to demonstrate how computer vision and deep learning can assist in the early identification of skin diseases.

---

# 🎯 Dataset

**Dataset:** HAM10000 (Human Against Machine with 10,000 Training Images)

The dataset contains dermatoscopic images of common pigmented skin lesions.

## Disease Classes

* Actinic Keratoses (akiec)
* Basal Cell Carcinoma (bcc)
* Benign Keratosis (bkl)
* Dermatofibroma (df)
* Melanoma (mel)
* Melanocytic Nevi (nv)
* Vascular Lesions (vasc)

---

# ✨ Features

* Automated dataset download
* Data preprocessing
* Image visualization
* Exploratory Data Analysis
* Class balancing using oversampling
* Image augmentation
* Custom CNN architecture
* Early stopping and checkpoint callbacks
* Model evaluation
* Confusion Matrix
* Classification Report
* Sample image prediction
* Model export for future deployment

---

# 🧠 Deep Learning Pipeline

```text
Dataset
      │
      ▼
Load Images
      │
      ▼
EDA & Visualization
      │
      ▼
Balance Classes
      │
      ▼
Train / Validation / Test Split
      │
      ▼
Image Augmentation
      │
      ▼
Custom CNN
      │
      ▼
Model Training
      │
      ▼
Evaluation
      │
      ▼
Prediction
      │
      ▼
Save Model
```

---

# 🛠 Tech Stack

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* OpenCV
* KaggleHub

---

# 📁 Project Structure

```text
SkinDiseaseClassification/

│── skin_disease_classification.ipynb
│── skin_disease_cnn.keras
│── README.md
│── requirements.txt
│── images/
│     ├── banner.png
│     ├── workflow.png
│     ├── confusion_matrix.png
│     ├── prediction.png
│     └── architecture.png
```

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/SkinDiseaseClassification.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```bash
jupyter notebook
```

or

```bash
Google Colab
```

Run all cells sequentially.

---

# 📊 Model Evaluation

The notebook evaluates the trained CNN using:

* Test Accuracy
* Confusion Matrix
* Classification Report
* Per-class Accuracy
* Training Curves
* Sample Predictions

---

# 📸 Visualizations

The project includes:

* Disease distribution
* Sample images
* Data augmentation preview
* Training accuracy
* Validation accuracy
* Loss curves
* Confusion matrix
* Prediction examples

---

# 🔮 Future Improvements

* Transfer Learning (EfficientNet, ResNet50)
* MobileNet deployment
* Grad-CAM visualization
* Streamlit Web App
* Flask REST API
* Docker deployment
* Model quantization for mobile devices

---

# 👨‍💻 Author

**Agum Shrivastava**

If you found this project useful, please consider giving it a ⭐ on GitHub.
