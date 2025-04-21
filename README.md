#  Facial Emotion Recognition Using CNN

This project implements and compares multiple Convolutional Neural Network (CNN) architectures to classify human facial emotions. Developed as part of the CSC462 Machine Learning course by Savana Alshubayli.

## 🧠 Models Implemented
- **Plain CNN** – A simple 3-layer ConvNet without enhancements
- **Baseline CNN** – A minimal architecture with only 2 convolutional layers
- **Enhanced CNN** – Includes Batch Normalization, Dropout, Class Weighting, and tuned hyperparameters

## 🎯 Goal
To classify facial expressions into one of 7 emotions:
`neutral`, `angry`, `disgust`, `fear`, `happy`, `sad`, `surprise`.

## 📁 Dataset
- Custom dataset organized in `train/`, `val/`, and `test/` directories
- Images resized to **64×64 RGB**
- Augmentation applied using `ImageDataGenerator`

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

> 🏆 **Best performance:** Enhanced CNN with 97% accuracy on the test set.

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- scikit-learn
- Google Colab

## 📂 Files Included
- `Facial_Emotion_Recognition 2.ipynb` – Complete notebook with all models, training, and evaluation
- `expressions.zip` – Dataset (optional to include in repo or host externally)
- `report.pdf` – Final project report (optional)
- `README.md` – This file

## 🚀 How to Run
1. Clone this repository
2. Upload or link your dataset (`expressions/`)
3. Open the notebook in Google Colab or Jupyter Notebook
4. Run cells step-by-step

---

**Author:** Savana Alshubayli  


