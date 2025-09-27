# SmartSoil: Soil Suitability Prediction Using Machine Learning

## Overview

Soil evaluation forms the scaffolding for construction planning, as geotechnical properties of the soil strongly influence the **structural integrity** and **long-term durability** of civil infrastructure.
Traditional geotechnical surveys are often time-consuming, labor-intensive, and dependent on laboratory testing, leading to project delays and increased costs.

This repository proposes a **Machine Learning (ML)-based predictive framework** to assess soil suitability for construction. The approach leverages open-access soil profile data and integrates preprocessing, model training, and evaluation to deliver a cost-effective and efficient decision-making pipeline.

We compare multiple ML models — **Logistic Regression (LR), Random Forest (RF), XGBoost (XGB), Support Vector Classifiers (SVC), and Artificial Neural Networks (ANN)** — to identify the best-performing classifier.

### Key Findings

* **XGBoost** achieved the highest performance with:

  * Accuracy: 94%
  * ROC-AUC: 98%
  * PRC-AP: 92%
* **Random Forest** was the second-best performing model.
* Results highlight the computational potential of ML in reducing human reliance and enabling timely construction planning.

---

## Features of This Repository

* Upload and merge **project data** with **soil property datasets**.
* Preprocessing with scaling and one-hot encoding.
* Model training and testing with **5-fold cross-validation**.
* Evaluation with:

  * Classification metrics (Accuracy, Precision, Recall, F1-score).
  * Error metrics (MAE, RMSE, R²).
  * Visualization (Confusion Matrix, ROC Curve, Precision-Recall Curve).

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/SmartSoil-ML.git
cd SmartSoil-ML
---

## Usage

1. Run the Jupyter Notebook or Python scripts in **Google Colab**.
2. Upload the **project dataset** and **soil dataset** when prompted.
3. The pipeline will:

   * Merge data by `WISE_ID`.
   * Train ML models.
   * Display evaluation metrics and plots.
   * Save outputs (e.g., confusion matrix, ROC/PR plots).

---

## Example Outputs

* **Confusion Matrix**
* **ROC Curve**
* **Precision-Recall Curve**

Evaluation plots are saved automatically as high-resolution `.png` files for publication-quality reporting.


## License

This project is released under the MIT License. See `LICENSE` file for details.
