# 📉 Linear Regression from Scratch (NumPy)

## 🧠 Project Overview
In machine learning, it is easy to rely on "black box" libraries like Scikit-Learn. To truly understand the underlying algorithms, I implemented **Linear Regression** from first principles using only Python and NumPy.

This project implements **Gradient Descent** optimization to minimize the Mean Squared Error (MSE) cost function, demonstrating a deep understanding of vectorization and calculus-based learning.

## Concepts Implemented
* **Vectorization:** Leveraging linear algebra for efficient matrix computation ($y = X\theta$).
* **Gradient Descent:** Manually implemented the update rule: $\theta = \theta - \alpha \nabla J(\theta)$.
* **Evaluation Metrics:** Calculated **MSE** and **$R^2$ Score** from scratch to evaluate model performance.

## Results
The model successfully converged to the optimal parameters using synthetic data.
* **Learning Rate:** 0.1
* **Iterations:** 1000

## How to Run
1.  Clone the repository:
    ```bash
    git clone [YOUR_NEW_REPO_LINK_HERE]
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the script:
    ```bash
    python linear_regression_scratch.py
    ```

---
*Author: Nilesh Singh | Master's Student, Computer Engineering at SDSU*
