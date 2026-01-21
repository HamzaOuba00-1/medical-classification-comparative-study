# Machine Learning Comparative Study

## 📌 Project Overview

This project presents a **comparative study of machine learning models** on datasets of different sizes, with a focus on **robust evaluation metrics** rather than accuracy alone. The work is structured to highlight how dataset size impacts model behavior, performance, and generalization.

Two experimental tracks are explored:

* **Small dataset experiments** (medical diagnostic context)
* **Large dataset experiments** (population-level health prediction)

The project is implemented using **Jupyter notebooks** and follows standard machine learning experimentation principles.

---

## 📂 Project Structure

```
/
│── 01_theoretical_foundations.ipynb
│── 02_small_dataset_experiments.ipynb
│── 03_large_dataset_experiments.ipynb
│── ML_hamza_presentation.pdf
│── 
```

### File Descriptions

* **01_theoretical_foundations.ipynb**
  Covers the theoretical background of machine learning model.

* **02_small_dataset_experiments.ipynb**
  Comparative study of ML models on a *small medical dataset* (breast cancer classification), emphasizing feature importance and overfitting risks.

* **03_large_dataset_experiments.ipynb**
  Experiments on a *large-scale dataset* (stroke prediction), focusing on recall, ROC-AUC, and PR-AUC to handle class imbalance.

* **ML_hamza_presentation.pdf**
  Summary presentation of objectives, methodology, results, and conclusions.

---

## 🧠 Methodology

1. **Data Preprocessing**

   * Cleaning and handling missing values
   * Feature scaling and encoding

2. **Models Evaluated**

   * Logistic Regression
   * Decision Trees
   * Random Forest

3. **Evaluation Metrics**

   * Recall
   * ROC-AUC
   * Precision-Recall AUC
   * Confusion Matrix

> ⚠️ Accuracy is intentionally not the primary metric due to class imbalance in medical datasets.

---


## 🛠️ Technologies Used

* Python 
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---


## 👤 Author

**Hamza Ouba**



