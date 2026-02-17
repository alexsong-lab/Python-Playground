# Advertising Sales Prediction — Linear & Polynomial Regression

This project explores supervised learning techniques using linear regression and polynomial regression to predict product sales based on advertising spending. Using real marketing data, the project demonstrates how to build, evaluate, and improve regression models with Scikit‑learn, Pandas, and Seaborn.

---

## **Project Purpose**

The purpose of this assignment is to provide hands‑on experience with core regression modeling. Through a series of experiments, students learn how to:

- Build regression models using different feature sets  
- Evaluate model performance using standard metrics  
- Engineer polynomial features to capture nonlinear relationships  
- Tune hyperparameters using GridSearchCV  
- Visualize data and analyze model behavior  
- Compare model performance across multiple experiments  

These tasks build foundational skills in machine learning modeling and performance evaluation.

---

## **Dataset**

- **File:** `advertising1.csv`  
- **Features:**  
  - `TV` — advertising spend on TV  
  - `radio` — advertising spend on radio  
  - `newspaper` — advertising spend on newspapers  
- **Target:**  
  - `sales` — product sales  

This dataset contains real advertising spending data commonly used in introductory regression modeling.

---

## **Tasks and Requirements**

### **1. Implement Regression Models**
- Complete all sections marked `# [YOUR CODE HERE]`  
- Build multiple linear regression models using different combinations of features  
- Extend the model to polynomial regression (e.g., adding squared terms like `TV²`)

### **2. Evaluate Model Performance**
Compute and compare key metrics:

- R² score  
- RMSE  
- MSE  
- MAE  

### **3. Visualize Data and Model Behavior**
Use Seaborn and Matplotlib to create:

- Pair plots  
- Regression plots  
- Residual plots  

### **4. Hyperparameter Tuning**
Use GridSearchCV to tune:

- Polynomial degree  
- Whether to include an intercept  
- Additional preprocessing options  

### **5. Compare and Interpret Results**
- Summarize performance differences across models  
- Comment on improvements from polynomial features and tuning  
- Analyze model behavior using visual diagnostics  

Sample outputs are provided in the assignment; your results may vary slightly but should be close.

---

## **Project Structure**

```
├── data/                 # advertising1.csv dataset
├── notebooks/            # Jupyter notebook with regression experiments
└── README.md             # Project documentation
```

---

## **Tools and Libraries**

- Python  
- Pandas — data manipulation  
- NumPy — numerical operations  
- Scikit‑learn — regression models, metrics, GridSearchCV  
- Seaborn / Matplotlib — visualization  
- Jupyter Notebook — interactive analysis  

---

## **Learning Outcomes**

By completing this project, you will gain experience in:

- Building and evaluating regression models  
- Understanding linear vs. nonlinear relationships  
- Applying feature engineering to improve performance  
- Using hyperparameter tuning to optimize models  
- Interpreting model results through metrics and plots  
