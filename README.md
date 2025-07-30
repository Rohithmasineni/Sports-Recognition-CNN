# Sports-Recognition-CNN

# Sports Detection – CNN-Based Image Classification Project

A deep learning computer vision project that classifies sports categories from images using a Convolutional Neural Network (CNN) built with PyTorch. This project focuses on training an image classifier that can recognize different types of sports scenes based on visual data.

---

## 📌 1. Project Description and Goal

### 🔍 Overview
This project aims to identify the type of sport depicted in an image (e.g., Cricket, Football, Tennis, etc.) by training a CNN model on labeled sports image datasets. The model learns to capture visual patterns and make accurate predictions.

### 🎯 Goal
- Build a CNN-based multi-class image classification model.
- Achieve good prediction performance using a clean dataset and deep learning.
- Utilize PyTorch for model training, evaluation, and tuning.

---

## 🧩 2. Workflow / Methodology

### 🔄 Project Pipeline
1. Data Collection
2. Data Preprocessing
3. CNN Model Architecture Design
4. Model Training on GPU
5. Evaluation on Validation Data
6. Visualization of Results

---

## 📊 3. Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/gpiosenka/sports-classification/data?select=sports.csv)
- **Structure**: 
  - `train/` folder with subfolders for each sport category
  - `test/` folder for validation images
  - `val/` folder for validation images
- **Classes**: Multiple sports (e.g., Cricket, Football, Basketball, etc.)

📁 **Due to the large size of the dataset**, you can access it via Google Drive:

👉 [Project Files & Dataset on Google Drive](https://drive.google.com/drive/u/2/folders/1b857du_v7iSHsNxaZdDVv63rBDyKjI7n)

---

## 🧠 4. Model Details

- **Architecture**: Custom CNN with Conv2D, ReLU, MaxPooling, Dropout, and Fully Connected Layers
- **Framework**: PyTorch
- **Training**: Batch training with CrossEntropyLoss and Adam optimizer
- **Evaluation**: Accuracy and Loss on validation set

---

## 📈 5. Results

- ✅ **Validation Accuracy**: 90.59%
- 📉 **Validation Loss**: 0.3559

---

## 📬 Contact

If you have any questions, feedback, or suggestions, feel free to reach out:

- 📧 Email: rohithmasineni223@email.com
- 🔗 LinkedIn: [Rohith Kumar Masineni](https://www.linkedin.com/in/rohith-kumar-masineni)

⭐ If you find this project helpful, feel free to star the repository and share it!

---

