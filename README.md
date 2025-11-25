# health-risk-prediction
A machine learning–based Health Risk Prediction System built using Python and Google Colab.  
# 🩺 Health Risk Prediction System  
### Machine Learning Project | Python | Google Colab

This project is a **Health Risk Prediction System** that uses machine learning to predict whether a person is at risk of diabetes based on medical parameters. The model is trained using the **Pima Indians Diabetes Dataset**, a widely used benchmark dataset in healthcare analytics.

The project follows the structure required for VIT Flipped Classroom Projects, including problem identification, modular design, implementation, testing, and documentation.

---

## 📌 1. Problem Statement  
Diabetes is a major chronic disease that often goes undetected until complications arise. Early prediction helps in preventive care and better management.  
This project builds a machine learning model that analyzes patient health features and predicts their **risk of diabetes**.

---

## 📌 2. Objectives  
- Clean and preprocess real-world medical data  
- Perform exploratory data analysis (EDA)  
- Train multiple ML models (Logistic Regression, Random Forest, KNN)  
- Compare model accuracy and select the best model  
- Predict diabetes risk for new patients  
- Classify risk as **Low / Moderate / High**

---

## 📌 3. Dataset  
**Pima Indians Diabetes Dataset**  
- Format: CSV  
- Rows: 768  
- Features: 8 medical attributes  
- Target: Outcome (0 = No diabetes, 1 = Diabetes)

The dataset was manually uploaded into Google Colab.

---

## 📌 4. Technologies Used  
- **Python**  
- **Google Colab**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-Learn**  

---

## 📌 5. Project Structure  

health-risk-prediction/
│
├── data/
│ └── diabetes.csv
│
├── src/
│ └── health_risk_model.ipynb
│
├── screenshots/
│ ├── heatmap.png
│ ├── eda_output.png
│ └── prediction_result.png
│
├── README.md

---

## 📌 6. Workflow / Methodology  

### **🟦 1. Data Loading**
- Dataset is uploaded in Colab using `files.upload()`  

### **🟦 2. Data Cleaning**
- Replace 0 values with NaN  
- Fill missing values with column mean  

### **🟦 3. Exploratory Data Analysis**
- Outcome distribution  
- Correlation heatmap  
- Feature visualization  

### **🟦 4. Model Training**
Models used:
- Logistic Regression  
- Random Forest Classifier  
- KNN Classifier  

### **🟦 5. Model Evaluation**
- Accuracy score  
- Confusion matrix  
- Classification report  

### **🟦 6. Prediction System**
User inputs:
- Pregnancies  
- Glucose  
- Blood pressure  
- Skin thickness  
- Insulin  
- BMI  
- Pedigree  
- Age  

Model outputs:
- Probability of diabetes  
- Risk Level → Low / Moderate / High  

---

## 📌 7. Results  
- Highest accuracy achieved using Random Forest  
- Reliable performance on test set  
- Successful prediction with risk categorization  

---

## 📌 8. How to Run the Project  

### **Step 1: Open the notebook in Google Colab**  
### **Step 2: Upload the dataset (`diabetes.csv`)**  
### **Step 3: Run all cells**  
### **Step 4: Enter patient details in the input prompts**  
### **Step 5: View the risk prediction result**

---

## 📌 9. Future Enhancements  
- Add prediction for more diseases (heart disease, hypertension)  
- Build a web interface using Streamlit/Flask  
- Deploy the system using cloud platforms  
- Use neural networks for improved accuracy  

---

## 📌 10. Author  
**Aditi (23BHI10121)**  
B.Tech – CSE (Healthcare Informatics)  
VIT Bhopal University  

---

## 📌 11. Disclaimer  
This is an educational project and not a clinical diagnostic tool.

