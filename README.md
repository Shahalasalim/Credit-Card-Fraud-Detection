# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using **Machine Learning**.
The model is trained to classify transactions as either:

* **0 → Legitimate Transaction**
* **1 → Fraudulent Transaction**

Credit card fraud detection is a critical real-world application of data science in the financial sector, helping institutions reduce financial losses and improve transaction security.


## 🎯 Objective

The main goal of this project is to build a machine learning model that can accurately identify fraudulent credit card transactions from a highly imbalanced dataset.

## 📂 Dataset Information

The dataset contains anonymized credit card transactions with numerical input variables.

### Features include:

* **Time** → Time elapsed between transactions
* **V1 to V28** → PCA-transformed numerical features
* **Amount** → Transaction amount
* **Class** → Target variable

### Target Variable

| Class | Meaning                |
| ----- | ---------------------- |
| 0     | Legitimate Transaction |
| 1     | Fraudulent Transaction |


## 🛠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**


## 📊 Project Workflow

### 1️⃣ Data Collection

Loaded the credit card transaction dataset using Pandas.

### 2️⃣ Data Exploration

Performed:

* Dataset inspection
* Statistical summary
* Null value checking
* Class distribution analysis

### 3️⃣ Data Preprocessing

Handled the highly imbalanced dataset by:

* Separating legitimate and fraudulent transactions
* Random sampling of legitimate transactions
* Creating a balanced dataset

### 4️⃣ Feature Selection

Separated:

* **Independent variables (X)**
* **Target variable (Y)**

### 5️⃣ Train-Test Split

Split dataset into:

* **80% Training Data**
* **20% Testing Data**

### 6️⃣ Model Building

Implemented **Logistic Regression** for fraud classification.

### 7️⃣ Model Evaluation

Evaluated performance using:

* Accuracy Score

---

## 🤖 Machine Learning Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning classification algorithm used for binary classification problems.

It predicts the probability of a transaction being fraudulent or legitimate.

---

## 📈 Results

The model was evaluated on:

* **Training Accuracy**
* **Testing Accuracy**

The project demonstrates effective fraud detection using Logistic Regression on balanced transaction data.

---

## 📌 Key Learnings

Through this project, I learned:

* Handling imbalanced datasets
* Data sampling techniques
* Fraud detection concepts
* Binary classification
* Logistic Regression implementation
* Model evaluation techniques

---

## 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

### Navigate to project folder

```bash
cd credit-card-fraud-detection
```

### Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
credit_card_fraud_detection.ipynb
```
## Dataset

The dataset used in this project is too large to upload directly to GitHub.

You can download it from Kaggle:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

File used: `creditcard.csv`
## 📷 Project Output

The model predicts whether a transaction is:

✔ Legitimate
❌ Fraudulent

## 💼 Real-World Applications

This project can be applied in:

* Banking systems
* Online payment gateways
* Financial transaction monitoring
* Fraud prevention systems

##👩‍💻 Author

**Fathima Shahala PT**

Aspiring ** Data Scientist** passionate about building machine learning solutions for real-world problems.

## ⭐ Repository Highlights

* Machine Learning Classification
* Fraud Detection System
* Data Balancing Techniques
* Logistic Regression Implementation
* End-to-End ML Workflow
