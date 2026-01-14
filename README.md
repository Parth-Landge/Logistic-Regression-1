logistic Regression From Scratch (Binary Classification)

Overview
This project demonstrates a from-scratch implementation of Logistic Regression
using NumPy, without relying on Scikit-learn’s built-in LogisticRegression model.

The goal is to deeply understand:
 How classification works mathematically
 Why sigmoid is used instead of a linear function
 How gradient descent updates parameters
 How predictions and accuracy are calculated manually

What I Learned
 Difference between **Linear Regression vs Logistic Regression**
 Why Linear Regression fails for classification problems
 Sigmoid function and probability interpretation
 Cost function (Log Loss)
 Gradient Descent for classification
 Feature scaling and 
 Manual accuracy calculation
 Model limitations and real-world uncertainty

 Implementation Details
- Implemented **sigmoid function manually**
- Computed gradients using partial derivatives
- Updated weights using **gradient descent**
- Trained the model over multiple epochs
- Generated predictions using probability threshold
- Evaluated performance using accuracy score

Dataset
- Binary classification dataset
- Cleaned and preprocessed manually
- Feature scaling applied for faster convergence

 Results
- Model successfully learned decision boundary
- Achieved reasonable accuracy on test data
- Demonstrated how real-world noise affects predictions

