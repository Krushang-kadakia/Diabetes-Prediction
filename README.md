# Diabetes-Prediction

The **Diabetes Prediction** project is a machine learning model designed to predict whether a person has diabetes based on certain health-related data. 

---

### **Project Objective**
The primary goal of this project is to build a classification model that predicts whether a person is diabetic (1) or non-diabetic (0) based on features such as glucose levels, blood pressure, and BMI. This is a **binary classification problem** with significant healthcare applications.

---

### **Dataset**
The project uses a dataset named **Diabetes.csv**, which contains:
- **Input Features**: Health-related parameters like:
  - Glucose levels
  - Blood pressure
  - Insulin levels
  - BMI (Body Mass Index)
  - Age
  - Number of pregnancies, etc.
- **Target Variable**: 
  - `Outcome`: Indicates whether the individual has diabetes (1) or not (0).

---

### **Steps in the Project**
1. **Data Import and Exploration**:
   - The dataset is loaded into a pandas DataFrame.
   - The structure (rows, columns) and statistical summary of the data are examined.
   - The distribution of diabetic and non-diabetic patients in the dataset is analyzed.

2. **Data Preprocessing**:
   - Feature scaling is applied using **StandardScaler** to normalize the dataset, ensuring that all features contribute equally to the model.

3. **Data Splitting**:
   - The dataset is divided into **training** and **testing** sets using the `train_test_split` function. This allows the model to be trained on one subset and evaluated on another.

4. **Model Selection**:
   - The project uses **Support Vector Machine (SVM)** as the machine learning algorithm.
   - SVM is a robust classification algorithm that works well with high-dimensional data by finding the optimal hyperplane to separate classes.

5. **Model Training and Evaluation**:
   - The SVM model is trained on the training dataset.
   - Predictions are made on the testing dataset, and accuracy is calculated using `accuracy_score` to evaluate the model's performance.

---

### **Applications**
This project has critical real-world implications in the healthcare domain, such as:
- **Early Detection**: Helps identify diabetes in individuals, enabling early intervention.
- **Risk Assessment**: Aids healthcare providers in evaluating an individual’s risk of developing diabetes based on health indicators.
- **Preventive Care**: Encourages individuals to make lifestyle changes if they are at risk.

---

### **Conclusion**
The **Diabetes Prediction** project demonstrates the use of machine learning for a healthcare problem. By leveraging a Support Vector Machine (SVM), it effectively classifies individuals as diabetic or non-diabetic based on health data. This project showcases:
- Data preprocessing techniques.
- The application of SVM for classification tasks.
- Model evaluation and accuracy assessment.
