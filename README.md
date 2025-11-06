## Linear Classification + MLP Regression (COMP24112 Coursework)

This repository contains my work on two tasks:

### 1) Loan Approval – Linear Classification (built from scratch)
- Implemented a linear classifier using hinge loss + L2 regularisation
- Optimised with gradient descent using **pure NumPy** (no sklearn SVMs)
- Explored effect of learning rate η
- Full grid search (C × η)
- Compared against logistic regression baseline

### 2) Soybean Crop Yield Prediction – MLP Regression
- Preprocessed real agricultural dataset (52k samples, 13+ features)
- Evaluated multiple MLP architectures (1 hidden layer + 2 hidden layer)
- Performed GridSearchCV over activation + hidden layers + epochs
- Feature importance via Gradient Boosting
- Achieved **R² ≈ 1.0** on test split

---

### Tech Stack
- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib / seaborn

---

### Files
- `notebook.ipynb` → main code + results
- `report.pdf` → written discussion + conclusions
