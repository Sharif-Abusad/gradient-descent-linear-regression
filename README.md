# 🚀 Gradient Descent & Linear Regression From Scratch

> A complete implementation of **Linear Regression** and multiple variants of **Gradient Descent Algorithms** from scratch using Python, NumPy, and Matplotlib.

This project demonstrates the mathematical intuition behind:
- 📈 Linear Regression
- ⚡ Gradient Descent Optimization
- 🔄 Stochastic Gradient Descent (SGD)
- 📦 Mini Batch Gradient Descent (MBGD)

The repository also includes comparison with **Scikit-Learn's LinearRegression** implementation for validation and better understanding.

---

# ✨ Features

✅ Linear Regression from scratch  
✅ Gradient Descent implementation  
✅ Optimization of only intercept (`b`)  
✅ Optimization of both slope (`m`) and intercept (`b`)  
✅ Stochastic Gradient Descent (SGD)  
✅ Mini Batch Gradient Descent (MBGD)  
✅ Mathematical intuition with visualizations  
✅ Comparison with Scikit-Learn model  
✅ Clean Jupyter Notebook implementations  

---

# 📂 Project Structure

```bash
GRADIENT_DESCENT/
│
├── 📘 GD_Mini_Batch.ipynb
│   └── Mini Batch Gradient Descent implementation from scratch
│
├── 📘 GD_Stochastic.ipynb
│   └── Stochastic Gradient Descent (SGD) implementation
│
├── 📘 Gradient_Descent_m_&_b.ipynb
│   └── Linear Regression using Gradient Descent optimizing both m and b
│
├── 📘 Gradient_Descent_Only_b.ipynb
│   └── Gradient Descent optimizing only intercept (b)
│
├── 📄 README.md
│   └── Project documentation
│
└── 📄 requirements.txt
    └── Required Python libraries
```

---

# 🧠 Algorithms Implemented

## 1️⃣ Gradient Descent (Optimizing Only `b`)

- Keeps slope (`m`) constant
- Optimizes only intercept (`b`)
- Helps understand the role of intercept in regression models

---

## 2️⃣ Gradient Descent (Optimizing `m` & `b`)

- Optimizes:
  - 📈 Slope (`m`)
  - 📍 Intercept (`b`)
- Full implementation of Linear Regression using Gradient Descent

---

## 3️⃣ Stochastic Gradient Descent (SGD)

- Updates parameters using **one training example at a time**
- Faster updates and learning
- Useful for large datasets

---

## 4️⃣ Mini Batch Gradient Descent (MBGD)

- Uses small batches of data for parameter updates
- Combines advantages of:
  - Batch Gradient Descent
  - Stochastic Gradient Descent
- More stable and efficient convergence

---

# 📚 Concepts Covered

📌 Linear Regression  
📌 Cost Function (MSE)  
📌 Partial Derivatives  
📌 Gradient Descent Optimization  
📌 Learning Rate  
📌 Epochs & Iterations  
📌 Model Convergence  
📌 Scikit-Learn LinearRegression  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming Language |
| 🔢 NumPy | Numerical Computation |
| 📊 Pandas | Data Handling |
| 📉 Matplotlib | Data Visualization |
| 🤖 Scikit-Learn | Model Validation |
| 📓 Jupyter Notebook | Interactive Development |

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/gradient-descent-linear-regression.git
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📊 Visualizations Included

✅ Regression Line Plot  
✅ Cost Reduction Graph  
✅ Gradient Descent Iterations  
✅ Convergence Visualization  
✅ Training Process Analysis  

---

# 🔍 Comparison with Scikit-Learn

This project also compares manual implementations with:

```python
from sklearn.linear_model import LinearRegression
```

to validate correctness and understand how production-level ML libraries work internally.

---

# 🎯 Learning Outcomes

By completing this project, you will understand:

✔️ How Linear Regression works internally  
✔️ Mathematics behind Gradient Descent  
✔️ Parameter optimization process  
✔️ Difference between:
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini Batch Gradient Descent

✔️ Practical implementation of ML algorithms from scratch  

---

# 🚀 Future Improvements

🔹 Polynomial Regression  
🔹 Multiple Linear Regression  
🔹 L1 & L2 Regularization  
🔹 Animated Gradient Descent Visualization  
🔹 Momentum Optimizer  
🔹 Adam Optimizer  

---

# 👨‍💻 Author

## Abu Sharif

Passionate about:
- 🤖 Machine Learning
- 📊 Data Science
- 🧠 Deep Learning
- 📐 Mathematics behind AI

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---