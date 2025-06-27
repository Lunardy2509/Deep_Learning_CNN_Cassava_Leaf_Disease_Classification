# 🌿 Deep Learning CNN for Cassava Leaf Disease Classification

This repository contains my final-term project for the Machine Learning course. The objective is to develop a deep learning model using **Convolutional Neural Networks (CNN)** to classify **cassava leaf diseases** into five distinct categories.

---

## 🧠 Project Overview

Cassava is a crucial crop in many tropical regions, and early identification of diseases in its leaves can significantly boost crop yield and reduce losses. This project implements a CNN-based classifier to automatically identify cassava leaf conditions based on image input.

---

## 🗂️ Contents

```bash
Deep_Learning_CNN_Cassava_Leaf_Disease_Classification/
├── CNN_Project_Cassava.ipynb     # Jupyter notebook with the full training + evaluation pipeline
├── Paper_Work.pdf                # Final report (theoretical background + results)
└── README.md
```

## 🧪 Model Summary
- 🧱 Model Type: CNN (Sequential model with Conv2D, MaxPooling2D, Dense)
- 📁 Dataset Source: Publicly available cassava leaf dataset (originally from Kaggle)
- 🏷️ Classes: 5 disease categories
- ⚙️ Frameworks: TensorFlow, Keras, NumPy, Matplotlib
- 🧼 Preprocessing: Rescaling, augmentation, stratified split
- 📊 Evaluation: Accuracy, confusion matrix, loss plots

## 🚀 How to Run
### 1. Clone this Repository
```bash
git clone https://github.com/Lunardy2509/Deep_Learning_CNN_Cassava_Leaf_Disease_Classification.git
cd Deep_Learning_CNN_Cassava_Leaf_Disease_Classification
```

### 2. Prepare Your Environment
You can use `conda` or `virtualenv`. Then install the required packages:
```bash
pip install -r requirements.txt
```
Or manually install:
```bash
pip install tensorflow keras numpy matplotlib scikit-learn
```

### 3. Load Dataset
- Download the cassava leaf image dataset from `Kaggle` by searching "Cassava Leaf Disease Classification".
- Unzip the dataset and place the training and test folders in your working directory.

### 4. Run the Notebook
Launch Jupyter:
```bash
jupyter notebook CNN_Project_Cassava.ipynb
```
Run the cells sequentially to train and evaluate the model.

## 📚 Report
A full report of the project, including:
- Background theory of CNNs
- Explanation of dataset and preprocessing
- Model architecture
- Results and conclusions
📄 **See** `Paper_Work.pdf` for the final report.

## 🧾 License
This project is for academic and educational use only.

## 📬 Contact
- GitHub: [@Lunardy2509](https://github.com/Lunardy2509)
- Email: ferdilunardy@gmail.com

⭐️ If you found this helpful or want to build on it, feel free to fork or star the project!

---

Let me know if you'd like:
- A **Bahasa Indonesia** version of the README,
- A **requirements.txt** generated from the notebook,
- Or a **diagram of the model architecture**!

I'm happy to help further.
