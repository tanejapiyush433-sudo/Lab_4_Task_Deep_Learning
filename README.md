# Lab_4_Task_Deep_Learning

# 🧠 Multiple Linear Regression Using Linear Perceptron (From Scratch)

This project implements Multiple Linear Regression using a single linear neuron (perceptron without activation) as part of a deep learning lab.

The goal is to understand how a perceptron can perform numeric prediction instead of classification by minimizing Mean Squared Error (MSE).

---

## 📌 Objective

* Implement multiple linear regression from scratch
* Use gradient descent to train model
* Predict salary using experience and test score
* Understand difference between classification and regression

---

## 📂 Dataset

Dataset used: Salary Prediction Dataset
Features:

* YearsExperience
* TestScore
* Salary (target output)

Place dataset CSV file in project folder before running code.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas

No machine learning libraries like sklearn are used for the model.
Everything is implemented manually for learning purposes.

---

## 🚀 Steps Implemented

1. Load dataset using pandas
2. Inspect data (rows, columns, shape)
3. Separate inputs (X) and output (y)
4. Initialize weights and bias
5. Implement prediction function
6. Implement Mean Squared Error loss
7. Compute gradients
8. Update weights using gradient descent
9. Train model over multiple epochs
10. Predict salary for new input

---

## 🧮 How Model Works

Model uses equation:

Salary = w1×Experience + w2×TestScore + bias

During training:

* Predictions are made
* Error is calculated using MSE
* Weights and bias updated
* Loss decreases over time

---

## ▶️ How to Run

Install dependencies:

```
pip install numpy pandas
```

Run file:

```
python linear_regression.py
```

Make sure dataset CSV is in same folder.

---

## 📊 Output

* Training loss decreasing
* Final learned weights
* Final bias value
* Predicted salary for new input

---

## 🎯 Learning Outcome

After completing this project, you will understand:

* How regression differs from classification
* How perceptron can predict numeric values
* How gradient descent reduces error
* Importance of learning rate
* How weights learn from data

