# 🤖 Learning ML — Pure NumPy Implementations

A collection of Machine Learning and Deep Learning algorithms implemented **from scratch** using only NumPy, with no high-level ML frameworks.

---

## 📌 Philosophy

> Understand the math. Write the code. Skip the magic.

Every algorithm here is built from the ground up — no `scikit-learn`, no `PyTorch`, no `TensorFlow`. Just NumPy and the underlying mathematics.

---

## 🧠 Implemented Algorithms

### Logistic Regression (`logistic-regression/`)
| Type | Description |
|------|-------------|
| **Binary** | Predicts pass/fail based on study hours & practice exams |
| **Multivariate** | Predicts letter grades (A–F) using softmax & categorical cross-entropy |

**Key concepts covered:**
- Sigmoid & Softmax activations
- Binary Cross-Entropy Loss (BCEL)
- Categorical Cross-Entropy Loss (CCEL)
- Backpropagation & Gradient Descent
- One-Hot Encoding

---

### K-Nearest Neighbors (`k-nearest-neighbor/`)
- Euclidean distance computation
- Manual bubble sort for neighbor ranking
- Majority vote classification

---

## 🛠️ Requirements

```bash
pip install numpy jupyter
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/learn-ML.git
cd learn-ML
jupyter notebook
```
