# Advanced Neural Framework for MRI-Based Brain Tumor Detection and Multiclass Classification

## 📌 Overview

**Advanced Neural Framework for MRI-Based Brain Tumor Detection and Multiclass Classification** is an AI-based medical image analysis project developed to automatically classify brain tumors from Magnetic Resonance Imaging (MRI) scans.

The system uses deep learning and machine learning techniques to analyze MRI images and classify them into three tumor categories:

* **Glioma**
* **Meningioma**
* **Pituitary Tumor**

The project focuses on developing a customized **VGG-16-inspired Convolutional Neural Network (CNN)** architecture for automated multiclass classification of brain MRI images.

> **Disclaimer:** This project is intended for academic and research purposes only. It is not designed to replace professional medical diagnosis.

---

## 🎯 Objectives

The main objectives of this project are:

* To develop an AI-based system for brain tumor classification from MRI images.
* To classify MRI scans into multiple brain tumor categories.
* To preprocess MRI images for deep learning-based analysis.
* To develop a customized VGG-16-inspired CNN architecture.
* To compare different machine learning and deep learning approaches.
* To evaluate the performance of the developed models using standard classification metrics.
* To explore the potential of AI in computer-aided medical image analysis.

---

## 🧠 Brain Tumor Classes

The system performs multiclass classification for the following tumor categories:

| Class           | Description                                                   |
| --------------- | ------------------------------------------------------------- |
| Glioma          | A tumor originating from glial cells in the brain             |
| Meningioma      | A tumor that develops from the meninges surrounding the brain |
| Pituitary Tumor | A tumor occurring in or around the pituitary gland            |

---

## 📊 Dataset

The project uses a brain MRI image dataset containing approximately **10,183 MRI images**.

### Classes

```text
Dataset
│
├── Glioma
├── Meningioma
└── Pituitary Tumor
```

The dataset is organized according to the respective tumor classes to facilitate supervised multiclass classification.

The complete dataset is **not included in this repository** because of its size and dataset distribution considerations.

---

## 🔄 Image Preprocessing

Before training the models, the MRI images undergo preprocessing to make them suitable for deep learning.

The preprocessing pipeline includes:

1. Loading MRI images.
2. Resizing images to **200 × 200 pixels**.
3. Converting images into tensors.
4. Applying normalization and transformations.
5. Organizing images according to their respective class labels.
6. Creating training and testing data loaders.

The preprocessing steps help provide standardized input to the neural network.

---

## 🏗️ Proposed Model

The primary model developed in this project is a **customized VGG-16-inspired CNN architecture**.

The architecture contains approximately **22 layers**, including convolutional and activation layers, followed by classification layers.

### Main Architecture Flow

```text
MRI Image
    ↓
Image Preprocessing
    ↓
Convolutional Layers
    ↓
ReLU Activation
    ↓
Feature Extraction
    ↓
Fully Connected Layers
    ↓
Softmax Classification
    ↓
Tumor Class Prediction
```

The CNN learns important visual features from MRI images and uses the extracted features to classify the images into the three tumor categories.

---

## 🤖 Models Explored

Multiple approaches were explored during the development of the project.

### Deep Learning Models

* Customized VGG-16-inspired CNN
* VGG-16
* AlexNet
* ResNet152

### Machine Learning Model

* Random Forest Classifier

These models were explored to understand and compare different approaches for MRI-based brain tumor classification.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Deep Learning

* PyTorch
* Torchvision

### Machine Learning

* Scikit-learn

### Data Processing

* NumPy
* Pandas

### Image Processing

* PIL
* OpenCV

### Data Visualization

* Matplotlib

### Development Environment

* Google Colab
* Jupyter Notebook

---
## 🚀 How to Run the Project

### Option 1: Google Colab

The project can be executed using Google Colab.

1. Open `MRI_Brain_Tumor_Detection.ipynb`.
2. Open the notebook in Google Colab.
3. Install the required dependencies.
4. Provide the required dataset.
5. Run the preprocessing cells.
6. Run the model training cells.
7. Evaluate the trained model.
8. Test the model with MRI images.

### Option 2: Local Environment

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/MRI-Brain-Tumor-Detection.git
```

Navigate to the project directory:

```bash
cd MRI-Brain-Tumor-Detection
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook using Jupyter Notebook or JupyterLab.

---

## 📦 Requirements

The major Python libraries required for this project include:

```text
torch
torchvision
numpy
pandas
matplotlib
scikit-learn
Pillow
opencv-python
```

---

## 📈 Model Evaluation

The models can be evaluated using the following metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

Training and validation graphs can also be used to analyze model performance and learning behavior.

### Results

Add your actual final results here:

| Metric              |           Result |
| ------------------- | ---------------: |
| Training Accuracy   | Add actual value |
| Validation Accuracy | Add actual value |
| Test Accuracy       | Add actual value |
| Precision           | Add actual value |
| Recall              | Add actual value |
| F1-Score            | Add actual value |

> **Important:** Replace the placeholders with the actual results obtained from your experiments. Do not use estimated values.

---

## 🔍 Prediction

After training, the model can be used to classify an MRI image into one of the supported categories:

```text
Input MRI
    ↓
Preprocessing
    ↓
Trained CNN Model
    ↓
Prediction
    ↓
Glioma / Meningioma / Pituitary Tumor
```

---

## 💡 Key Features

* Automated MRI-based brain tumor classification.
* Multiclass classification of three tumor categories.
* Customized VGG-16-inspired CNN architecture.
* Image preprocessing and transformation.
* Deep learning-based feature extraction.
* Comparison of multiple machine learning and deep learning models.
* Performance evaluation using classification metrics.
* Compatible with Google Colab.
* Visualization of training and evaluation results.

---

## 🔬 Project Workflow

```text
MRI Dataset
     ↓
Data Loading
     ↓
Image Preprocessing
     ↓
Dataset Splitting
     ↓
DataLoader Creation
     ↓
Model Training
     ↓
Model Validation
     ↓
Performance Evaluation
     ↓
Tumor Classification
```

---

## ⚠️ Limitations

* The system is trained on a specific MRI dataset and may not generalize to all medical imaging datasets.
* Performance may vary depending on image quality and dataset distribution.
* The project is intended for research and educational purposes.
* The model should not be used as an independent medical diagnostic system.

---

## 🔮 Future Enhancements

Future improvements could include:

* Expanding the dataset with more diverse MRI images.
* Adding additional tumor categories.
* Applying advanced data augmentation techniques.
* Improving model generalization.
* Exploring advanced transfer learning techniques.
* Implementing explainable AI techniques such as **Grad-CAM**.
* Developing a user-friendly web application for MRI prediction.
* Deploying the trained model as a cloud-based application.
* Providing visual explanations for model predictions.

---

## 👩‍💻 Project Information

**Project:** Advanced Neural Framework for MRI-Based Brain Tumor Detection and Multiclass Classification

**Domain:** Artificial Intelligence / Machine Learning / Medical Image Analysis

**Programming Language:** Python

**Frameworks:** PyTorch, Torchvision, Scikit-learn

**Environment:** Google Colab

**Dataset Size:** Approximately 10,183 MRI images

**Classification Classes:** Glioma, Meningioma, Pituitary Tumor

---

## 📜 Disclaimer

This project has been developed for **academic, educational, and research purposes**.

The predictions produced by this system should not be considered a medical diagnosis. Any medical decision must be made by qualified healthcare professionals using appropriate clinical evaluation and diagnostic procedures.

---

## ⭐ Acknowledgement

This project demonstrates the application of artificial intelligence and deep learning techniques to medical image classification, with the goal of exploring AI-assisted approaches for brain tumor detection and multiclass classification.

