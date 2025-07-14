# 📉 Batch Gradient Descent from Scratch

This project implements **batch gradient descent** using NumPy to perform linear regression without relying on external ML libraries. It’s designed to demonstrate a foundational machine learning algorithm in a transparent, hands-on way.

## 🚀 Features

- Implementation of linear regression using batch gradient descent
- Custom cost function (Mean Squared Error)
- Manual parameter tuning: learning rate, epochs
- Visualization of the cost function convergence
- Simple, educational code structure

## 🧠 Concepts Covered

- Linear regression
- Gradient computation
- Mean squared error (MSE)
- Learning rate tuning
- Overfitting/underfitting intuition

## 📁 Project Structure

```text
data-batch-gradient-descent/
├── data/
│   └── sample_data.csv          # Input dataset
├── src/
│   ├── gradient_descent.py      # Core gradient descent implementation
│   ├── utils.py                 # Helper functions (e.g., plotting, error calc)
│   └── main.py                  # Entry point to run the model
├── notebooks/
│   └── visualization.ipynb      # Cost function plots & model convergence
├── outputs/
│   ├── model_parameters.json    # Saved model weights
│   └── cost_plot.png            # Training loss curve
├── requirements.txt
└── README.md
```
```bash
git clone https://github.com/saranjthilak/data-batch-gradient-descent.git
```
## 📊 Example Output
Final MSE loss: 0.01234

Learned parameters: theta_0 = 2.1, theta_1 = 0.89

Cost plot showing convergence

## 📌 TODO
Add support for mini-batch and stochastic gradient descent

Add polynomial feature transformation

Explore ridge/lasso regularization

Export trained model to pickle or JSON

👤 Author
Saran Jaya Thilak
