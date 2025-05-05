# ❤️ Heart Disease Prediction Project

A simple machine learning project to predict the presence of heart disease using Logistic Regression.

---

## 📝 Description

This project involves:

- Loading and preprocessing heart disease data from a CSV file.
- Splitting the dataset into training and test sets.
- Training a Logistic Regression model.
- Evaluating the model on both training and testing data.
- Predicting heart disease for a single patient's input.

---

## 🚀 Getting Started

### 📦 Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- Required libraries:
  ```bash
  pip install numpy pandas scikit-learn
  ```

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## 📊 Usage

### 🧠 Train the Model

Run the training script:

```bash
python train_model.py
```

What it does:
- Loads `data.csv`
- Splits data (80% training, 20% testing)
- Trains a Logistic Regression model
- Prints training and test accuracy

### 🧪 Predict for a Single Patient

Run the prediction script:

```bash
python predict.py
```

The script:
- Defines a sample input tuple of patient data
- Makes a prediction using the trained model
- Prints whether the person has heart disease

---

## 📁 Data

- The dataset is based on the UCI Heart Disease dataset.
- It includes 13 input features and 1 target column:
  - `target`:  
    - `0` → Healthy  
    - `1` → Heart Disease

---
