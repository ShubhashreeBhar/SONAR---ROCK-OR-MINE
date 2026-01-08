# SONAR---ROCK-OR-MINE PREDICTION

This project is a **Machine Learning classification model** that predicts whether an object detected by SONAR signals is a **Rock** or a **Mine**.  
The model is trained using the **Sonar Dataset**, which contains sonar signal patterns reflected from objects under the sea.

---

## 📌 Problem Statement

Submarines use SONAR to detect underwater objects.  
Based on the returned sonar signals, the goal is to classify the object as:

- **R (Rock)**  
- **M (Mine)**

This is a **binary classification problem**.

---

## 📊 Dataset Information

- Total Instances: **208**
- Features: **60 numerical attributes**
- Target Labels:
  - `R` → Rock
  - `M` → Mine

Each feature represents the energy of sonar signals at different frequencies.

---

## 🛠️ Technologies Used

- Python 
- NumPy
- Pandas
- Scikit-learn
- Matplotlib 
- Jupyter Notebook

---

## ⚙️ Model Used

- **Logistic Regression** 

The dataset is split into **training and testing sets**, and the model is evaluated using accuracy score.

---

## 📈 Workflow

1. Load and preprocess the dataset  
2. Perform exploratory data analysis (EDA)  
3. Split data into training and testing sets  
4. Train the machine learning model  
5. Evaluate model performance  
6. Make predictions on new data  


