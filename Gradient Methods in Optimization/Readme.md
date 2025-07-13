# 🚀 Gradient Descent & Polyak's Heavy Ball Method Visualized

This repository contains an interactive Jupyter Notebook demonstrating the **Gradient Descent** and **Polyak’s Heavy Ball** optimization methods on a simple quadratic function.

## 📌 Purpose

The notebook visually compares the behavior of two optimization algorithms:
- **Vanilla Gradient Descent**
- **Polyak's Heavy Ball Method** (a momentum-based approach)

These methods are applied on a 1D quadratic function `f(x) = x²` to observe:
- Convergence speed
- Oscillations (Zig-Zag problem)
- Impact of momentum

---

## 🧠 Key Concepts

- **Gradient Descent** iteratively updates variables in the negative gradient direction to minimize a function.
- **Polyak’s Method** adds momentum to accelerate convergence and reduce oscillations.

> 💡 A fundamental property of the negative gradient is that it always points perpendicular to the contours of a function. This is universally true.

---

## 📊 Visualizations

- 📈 Shows trajectory of both methods on the curve `f(x) = x²`
- 🔴 Red dots illustrate the update path
- 🎢 The "Zig-Zag" behavior is observed in standard Gradient Descent

---

## 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
