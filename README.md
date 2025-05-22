# Logistic Regression Practice

This project demonstrates a complete workflow for building and evaluating a **Logistic Regression** model using the **Spaceship Titanic** dataset.

The notebook walks through data preprocessing, exploratory analysis, model training, evaluation, and cross-validation — providing a comprehensive approach to binary classification.

---

## 📌 Workflow Overview

### 1. 📚 Import Libraries
Key Python libraries used:
- `pandas` and `NumPy` for data manipulation
- `seaborn` and `matplotlib` for visualization
- `scikit-learn` for modeling and evaluation

### 2. 📥 Load Data
- Dataset is loaded from a CSV file
- First few rows are displayed for initial inspection

### 3. 🧹 Data Exploration & Cleaning
- Data types and missing values are analyzed
- Rows with missing values are dropped (for simplicity)

### 4. 🏗️ Feature Selection & Engineering
- Selected features: `RoomService`, `Spa`, `FoodCourt`, `ShoppingMall`, `Age`, `VIP`, `CryoSleep`, and `Transported`
- Binary categorical features (`VIP`, `CryoSleep`) are encoded as integers
- One-hot encoding is applied where necessary

### 5. 📊 Exploratory Data Analysis (EDA)
- `seaborn.pairplot()` is used to visualize relationships between input features and the target variable

### 6. ⚙️ Model Preparation
- Features (`X`) and target (`y`) are defined
- Dataset is split into training and testing subsets

### 7. 🤖 Model Training & Prediction
- Logistic Regression model is trained using training data
- Predictions are generated on the test set

### 8. 🧪 Evaluation
- Misclassified samples are identified
- Model performance is evaluated using:
  - Classification report (precision, recall, F1-score)
  - Cross-validation to assess generalization

---

## 📁 Dataset
This project uses the [Spaceship Titanic dataset](https://www.kaggle.com/competitions/spaceship-titanic) from Kaggle.

---

## 🚀 Getting Started

To run this notebook:
1. Clone the repo
2. Install required packages:
   ```bash
   pip install -r requirements.txt
