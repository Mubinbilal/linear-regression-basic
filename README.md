# linear-regression-basic
Simple Linear Regression using Scikit-learn — covers data visualization, model training, batch prediction, and live user input inference. Great for ML beginners.
# 📈 Linear Regression from Scratch with Scikit-learn

A beginner-friendly implementation of **Simple Linear Regression** using Python and Scikit-learn. This project demonstrates how to train a regression model on a small dataset, visualize the data, make batch predictions, and interactively predict outputs for custom inputs.

---

## 🔍 Overview

This notebook walks through the core steps of a supervised machine learning workflow:

1. **Define** a simple dataset (X → Y with a perfect linear relationship)
2. **Visualize** the raw data with a scatter plot
3. **Train** a Linear Regression model using Scikit-learn
4. **Predict** values for a new set of inputs
5. **Interact** — take a custom value from the user and return a live prediction

---

## 📁 Project Structure

```
linear-regression-basic/
│
├── linear_regression_basic.ipynb   # Main Jupyter Notebook
└── README.md                       # Project documentation
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| NumPy | Array and data handling |
| Scikit-learn | Linear Regression model |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive development environment |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/linear-regression-basic.git
cd linear-regression-basic
```

### 2. Install dependencies

```bash
pip install numpy scikit-learn matplotlib notebook
```

### 3. Launch the notebook

```bash
jupyter notebook linear_regression_basic.ipynb
```

---

## 📊 Dataset

A simple hand-crafted dataset used to demonstrate the concept:

| X (Input) | Y (Output) |
|---|---|
| 1 | 100 |
| 2 | 200 |
| 3 | 300 |
| 4 | 400 |
| 5 | 500 |

The model is then used to predict outputs for inputs **6 through 10**, and accepts a custom value via user input.

---

## 💡 Key Concepts Covered

- What is Linear Regression?
- Fitting a model with `model.fit(X, Y)`
- Making predictions with `model.predict()`
- Scatter plot visualization before modeling
- Accepting and processing real-time user input for inference

---

## 🙌 Acknowledgements

Built as a learning project to understand the fundamentals of supervised machine learning and the Scikit-learn API.
