# 🎵 Music Genre Classification using Neural Networks

This project implements an end-to-end **Music Genre Classification system** using
audio feature extraction and a **Multi-Layer Perceptron (MLP)** neural network.
The system predicts the genre of a music track based on extracted audio features.

The project is designed to run **both locally and in the Kaggle Notebook environment**.

---

## 📌 Project Overview

- **Task:** Multi-class music genre classification
- **Input:** Audio features extracted from music files
- **Output:** Predicted music genre with confidence score
- **Model:** Multi-Layer Perceptron (MLP)
- **Dataset:** GTZAN Music Genre Dataset (feature-based)

---

## 🔗 Project Links

- **GitHub Repository:**  
  https://github.com/nppro/machine-learning

- **Kaggle Notebook:**  
  https://www.kaggle.com/code/phuocphamnguyen/machine-learning

## 🧠 Machine Learning Pipeline

1. Load audio feature dataset
2. Remove unnecessary metadata columns
3. Encode genre labels
4. Normalize feature values
5. Split data into training and testing sets
6. Train an MLP neural network
7. Evaluate performance using accuracy and confusion matrix
8. Predict genres for unseen audio samples

---

## 🗂 Project Structure

MACHINE-LEARNING/
│
├── data/
│ └── features*3_sec.csv # Audio feature dataset (GTZAN, 3-second segments)
│
├── notebooks/
│ └── music-genre.ipynb # Main Jupyter/Kaggle notebook
│
├── samples/
│ └── *.mp3 / \_.wav # Sample audio files for live prediction demo
│
└── README.md # Project documentation

---

## ⚙️ Execution Environments

This project supports **two execution modes**:

- **Local Machine (Jupyter Notebook)**
- **Kaggle Notebook**

The code automatically adapts to the environment by detecting the dataset path.

---

## 🖥️ Option 1: Run Locally (Jupyter Notebook)

### 1️⃣ Requirements

- Python **3.8 or higher**
- Jupyter Notebook

### 2️⃣ Install Dependencies

Install required libraries using pip:

````bash
pip install numpy pandas matplotlib seaborn scikit-learn librosa tensorflow


3️⃣ Run the Notebook
```bash
jupyter notebook
````

☁️ Option 2: Run on Kaggle (Recommended)

Kaggle Notebook Link

👉 https://www.kaggle.com/code/phuocphamnguyen/machine-learning

1️⃣ Open the Notebook
• Open the link above
• Click “Copy & Edit” or “Fork” to run your own version
