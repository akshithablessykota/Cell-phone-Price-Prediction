# 📱 Cell Phone Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the price category of a mobile phone based on its technical specifications using Machine Learning classification algorithms. Instead of predicting the exact price, the model classifies each phone into one of four price categories.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using multiple classification algorithms.

---

## 🎯 Objective

The objective of this project is to build a machine learning model that accurately predicts the price category of a mobile phone using its hardware and software specifications.

---

## 📊 Dataset Information

The dataset contains specifications of different mobile phones.

### Features include:
- Battery Power
- Bluetooth
- Clock Speed
- Dual SIM
- Front Camera
- Internal Memory
- Mobile Depth
- Mobile Weight
- Number of Cores
- Primary Camera
- Pixel Resolution Height
- Pixel Resolution Width
- RAM
- Screen Height
- Screen Width
- Talk Time
- 3G Support
- Touch Screen
- WiFi Support

### Target Variable

**price_range**

- 0 → Low Cost
- 1 → Medium Cost
- 2 → High Cost
- 3 → Very High Cost

---

## 🧹 Data Preprocessing

- Checked for missing values
- Verified duplicate records
- Explored feature distributions
- Split dataset into training and testing sets
- Applied feature scaling where required

---

## 📈 Exploratory Data Analysis (EDA)

Performed Exploratory Data Analysis to understand:

- Feature distributions
- Correlation between variables
- Relationship between RAM and price category
- Data balance across all price categories

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)

---

## 📊 Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **96.5%** |
| Decision Tree | **85.25%** |
| Random Forest | **88.0%** |
| K-Nearest Neighbors | **56.25%** |
| Support Vector Classifier | **96.25%** |

---

## 🏆 Best Performing Model

**Logistic Regression** achieved the highest accuracy of **96.5%**, followed closely by **Support Vector Classifier (96.25%)**.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Repository Structure

```
Cell-Phone-Price-Prediction/
│── Cell_Phone_Price_Prediction.ipynb
│── README.md
│── requirements.txt
│── .gitignore
│── data/
│── report/
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Cell-Phone-Price-Prediction.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all the cells.

---

## 📌 Problem Type

**Machine Learning Classification**

Specifically:

**Multiclass Classification**

---

## 📄 Project Report

A detailed project report is included in the repository.

---

## 👩‍💻 Author

**Akshitha Blessy Kota**

B.Tech – Computer Science Engineering

Machine Learning & Data Science Enthusiast
