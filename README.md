# ANN-Regression-Customer-Salary-Prediction-Model



This project implements an **Artificial Neural Network (ANN)** to predict **customer salary** based on input features.  
The model is built using **TensorFlow**, **Keras**, **Scikit-Learn**, and **Pandas**.  
👉 **The model is also deployed as a Streamlit web app for easy interaction and prediction.**

---

## 📌 Project Objectives

- Build a regression model using Artificial Neural Networks  
- Preprocess customer data for model training  
- Train and evaluate the ANN using standard metrics  
- Deploy the trained model as a simple and interactive Streamlit web application  
- Allow users to input customer details and get real-time salary predictions  

---

## 🧠 Technologies & Libraries Used

- **Python 3.x**
- **TensorFlow**
- **Keras**
- **Scikit-Learn**
- **Pandas**
- **NumPy**
- **Streamlit** (for web deployment)
- **Matplotlib / Seaborn** (for visualization)

---

---

## 🔧 How the Model Works

### **1. Data Preprocessing**
- Load dataset  
- Handle missing values  
- Encode categorical variables (if present)  
- Train-test splitting  
- Standardization using **StandardScaler**

### **2. ANN Architecture**
The model typically includes:
- Input Layer  
- Dense Hidden Layer (ReLU)  
- Dense Hidden Layer (ReLU)  
- Output Layer (Linear activation for regression)

### **3. Model Training**
- Optimizer: **Adam**  
- Loss function: **MSE**  
- Evaluation metrics: **MAE**, **MSE**  
- Validation split included during training  

### **4. Evaluation**
- MAE, MSE  
- R² Score  
- Loss curve visualization  



