# Titanic-Survival-Prediction

## 🚢 Titanic Survival Prediction using Machine Learning

A Machine Learning project based on the famous Titanic dataset from Kaggle.

---

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques.

The notebook includes:

- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Encoding
- Model Training
- Prediction Generation
- Kaggle Submission

---

## 📂 Dataset Information

Features used in the dataset:

- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

### 🎯 Target Variable

- `Survived`

### 🔗 Dataset Link

https://www.kaggle.com/competitions/titanic

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing

- Filled missing values
- Removed unnecessary columns
- Converted categorical data into numerical format

### 2️⃣ Feature Engineering

Created features such as:

- `Title`
- `Age_Bin`
- `Fare_bin`
- `Fare_per_ticket`
- `Num_family`
- `tkt_count`

### 3️⃣ Encoding

Applied:

- Label Encoding
- One-Hot Encoding

### 4️⃣ Model Training

Implemented:

- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|---|---|
| Random Forest Classifier | 83.14% |

---

## 📈 Visualizations Included

- Fare Distribution
- Survival Analysis
- Age Distribution
- Passenger Class Analysis

---

## 🚀 How to Run

### Clone Repository

```bash
git clone <your-github-repo-link>
