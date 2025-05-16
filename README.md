# 🧠 Brain Tumor Classification Using Deep Learning

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify MRI brain images into categories indicating the presence or absence of a tumor. It automates the detection process, aiming to assist in early diagnosis of brain tumors and support healthcare professionals.

---

## 📁 Dataset Structure

After unzipping, the dataset should follow this structure:

```text
brain_tumor/
├── glioma_tumor/
├── meningioma_tumor/
├── no_tumor/
└── pituitary_tumor/
```

Each folder contains images related to that particular brain tumor type.

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- PIL (Pillow)

## 🧪 Features

- Automatically extracts and loads the dataset from a ZIP file.
- Constructs a CNN model using Keras Sequential API.
- Trains and validates the model on labeled MRI data.
- Evaluates the model using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-score
- Displays performance metrics and sample predictions.

## 🚀 How to Run

Step 1: Clone this repository:
```bash
git clone https://github.com/SandeepBalimidi/brain-tumor-classification.git
cd brain-tumor-classification
```
Step 2: Add Dataset
Place your dataset ZIP file named brain_tumor.zip in the root directory.

Step 3: Launch the Notebook
```bash
jupyter notebook brain_tumor.ipynb
```

The notebook will unzip the dataset, load images, train the model, and show evaluation results.

## 📊 Model Evaluation
The notebook will display:

Accuracy and loss graphs over epochs

Confusion matrix

Classification report with precision, recall, and F1-score

## 🧠 Classes Detected
Glioma Tumor

Meningioma Tumor

No Tumor

Pituitary Tumor

## 📈 Sample Results
Sample output visuals include:

Training vs Validation Accuracy

Training vs Validation Loss

Confusion Matrix heatmap

Correct vs Incorrect Predictions (optional visualization)

## ✅ Future Enhancements
Apply image augmentation to improve model generalization.

Use pre-trained models like VGG16, ResNet for better accuracy.

Deploy using Flask or Streamlit for live predictions.

Include Grad-CAM for model interpretability.

##  👨‍🎓Author
Sandeep Balimidi
GitHub: https://github.com/SandeepBalimidi
