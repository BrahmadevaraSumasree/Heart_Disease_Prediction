# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can help in providing timely treatment and improving survival rates.

This project uses **Machine Learning techniques** to predict whether a person is likely to have heart disease based on several medical attributes such as age, cholesterol level, blood pressure, and other clinical features.

The model is trained using a dataset containing patient health information and is implemented in **Python using Google Colab**.

# 🎯 Objective

The main goal of this project is to:

* Analyze medical data related to heart disease
* Perform **data preprocessing and exploration**
* Train machine learning models to **predict heart disease**
* Evaluate the performance of the models

# 📂 Project Structure
Heart-Disease-Prediction
│
├── heart.csv                     # Dataset used for training the model
├── heart_disease_Project.ipynb   # Google Colab notebook with code
└── README.md                     # Project documentation

# 📊 Dataset Information

The dataset **heart.csv** contains **1025 patient records** and **14 attributes** related to heart health.

### Dataset Features

| Feature  | Description                              |
| -------- | ---------------------------------------- |
| age      | Age of the patient                       |
| sex      | Gender (1 = Male, 0 = Female)            |
| cp       | Chest pain type                          |
| trestbps | Resting blood pressure                   |
| chol     | Serum cholesterol level                  |
| fbs      | Fasting blood sugar                      |
| restecg  | Resting electrocardiographic results     |
| thalach  | Maximum heart rate achieved              |
| exang    | Exercise induced angina                  |
| oldpeak  | ST depression induced by exercise        |
| slope    | Slope of peak exercise ST segment        |
| ca       | Number of major vessels                  |
| thal     | Thalassemia type                         |
| target   | Heart disease presence (1 = Yes, 0 = No) |

# ⚙️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

# 🔍 Project Workflow

The project follows these main steps:

### 1️⃣ Data Loading

The dataset is loaded using **Pandas**.

### 2️⃣ Data Exploration

Basic analysis is performed to understand the dataset structure and features.

### 3️⃣ Data Preprocessing

* Checking missing values
* Data cleaning
* Feature preparation

### 4️⃣ Model Training

Machine learning algorithms are used to train the model for predicting heart disease.

### 5️⃣ Model Evaluation

The model performance is evaluated using standard evaluation metrics.

---

# 📈 Expected Outcome

The trained model can analyze patient health parameters and predict the **likelihood of heart disease**, helping in early diagnosis and preventive healthcare.

# ▶️ How to Run the Project

1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

2️⃣ Open the notebook

```
heart_disease_Project.ipynb
```

3️⃣ Run all cells in **Google Colab** or **Jupyter Notebook**.

---

# 💡 Future Improvements

* Use more advanced ML models
* Improve prediction accuracy
* Deploy the model as a **web application**
* Add real-time health data input.
