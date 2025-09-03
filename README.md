

# Logistic Regression – Student Admission Prediction 🎓

## 📌 Overview

This project demonstrates **logistic regression from scratch** (without using libraries like scikit-learn) to predict whether a student is admitted to university based on their exam scores.

It was built as a **practice project** while following Andrew Ng’s *Machine Learning Specialization* and serves as a portfolio-ready example of applying core machine learning concepts.

---

## 🚀 Project Workflow

1. **Data Setup**

   * Created a small dataset of student exam scores and admission results (0 = not admitted, 1 = admitted).

2. **Sigmoid Function**

   * Implemented the logistic (sigmoid) function to map predictions between 0 and 1.

3. **Prediction Function**

   * Built a function to compute probabilities using the logistic regression equation:

     $$
     \hat{y} = \sigma(w \cdot x + b)
     $$

4. **Cost Function (Log Loss)**

   * Implemented the loss function to measure prediction error.

5. **Gradient Descent**

   * Optimized parameters `w` (weight) and `b` (bias) using gradient descent.

6. **Model Training**

   * Trained the logistic regression model for several epochs and minimized cost.

7. **Evaluation**

   * Tested the model with new student exam scores to predict admission chances.

---

## 📂 Files in This Repository

* `logistic_regression.ipynb` → Main notebook with step-by-step implementation.
* `README.md` → Project overview and documentation.

---

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries**: NumPy, Matplotlib
* **Environment**: Jupyter Notebook (works on Kaggle, Google Colab, or local JupyterLab)

---

## 📊 Results

* Successfully trained logistic regression from scratch.
* Learned parameters (`w`, `b`) that separate admitted vs. not admitted students.
* Plotted decision boundary (optional extension).

Example output:

```
Learned parameters: w = 1.20, b = -3.45
Final cost: 0.29
```

---

## 🔮 Next Steps / Improvements

* Expand dataset with real admission data.
* Add **feature scaling** for faster convergence.
* Compare with **scikit-learn LogisticRegression** implementation.
* Extend to **multi-class classification**.

---

## ✨ Learning Goal

This project is not about state-of-the-art accuracy, but about **understanding logistic regression deeply by building it from scratch**. It’s a strong foundation for moving into advanced machine learning and AI applications.
