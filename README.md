# LASSO vs Ridge Regression using Gradient-Based Optimization

## Project Overview
This project demonstrates the implementation and comparison of two regularized regression techniques: **LASSO Regression** and **Ridge Regression**. These techniques help reduce overfitting and improve the generalization performance of regression models.

In this project, a synthetic dataset is generated using the Scikit-learn library. The dataset is standardized before training the models. LASSO regression is implemented using the subgradient optimization method, while Ridge regression is implemented using gradient descent.

The performance of both models is evaluated using **Mean Squared Error (MSE)** and convergence graphs are plotted to visualize the optimization process.

---

## Course Information

Course: Numerical Optimization  
Program: B.Tech CSE – AIML  
Institution: JAIN (Deemed-to-be University)

---

## Team Members

| Name | USN |
|------|------|
| Hima Sajeesh Kumar | 23BTRCL102 |
| Kaviya M | 23BTRCL049 |
| Likitha H | 23BTRCL051 |
| Keerthi K M | 23BTRCL106 |

---

## Objectives

- Generate a regression dataset for training and testing.
- Apply feature standardization to improve optimization performance.
- Implement LASSO regression using the subgradient method.
- Implement Ridge regression using gradient descent.
- Evaluate model performance using Mean Squared Error (MSE).
- Visualize convergence of optimization algorithms.

---

## Dataset

A synthetic dataset is generated using the `make_regression()` function from the Scikit-learn library.

Dataset characteristics:

- Number of samples: 200
- Number of features: 20
- Informative features: 5
- Random noise added to simulate realistic data

The dataset is standardized using **StandardScaler** before training the models.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Structure

Numerical-Optimization-Project  
│  
├── main.py  
├── README.md  
├── requirements.txt  
├── graphs  
│   ├── lasso_convergence.png  
│   └── ridge_convergence.png  
└── documentation  
    └── Numerical_Optimization_Project_Report.docx  

---

## Installation

Install required libraries using:

pip install numpy matplotlib scikit-learn

Or using requirements file:

pip install -r requirements.txt

---

## Running the Project

Run the Python script:

python main.py

The program will train the models, calculate performance metrics, and display convergence graphs.

---

## Example Output

LASSO Test MSE: 93.91  
Ridge Test MSE: 728.81  

Number of zero weights in LASSO: 0  
Number of zero weights in Ridge: 0  

---

## Results

The results show that **LASSO regression achieved a lower Mean Squared Error compared to Ridge regression** in this experiment.

LASSO regression can encourage sparsity by shrinking some coefficients toward zero, which helps identify important features. Ridge regression reduces the magnitude of coefficients but keeps all features in the model.

The convergence graphs show how the loss value decreases over iterations for both models during the optimization process.

---

## Conclusion

This project demonstrates how **regularization techniques and optimization methods** can improve regression models. LASSO regression helps with feature selection, while Ridge regression stabilizes the model by controlling coefficient magnitude.

Both techniques are important tools for building reliable and generalizable machine learning models.

---
