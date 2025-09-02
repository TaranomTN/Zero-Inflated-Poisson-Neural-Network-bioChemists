# ZIP-Neural-Network

## Article Publications Model Comparison

This project compares the performance of three machine learning models on the **Article Publications dataset**, focusing on predicting the number of scientific articles published by researchers. The target variable exhibits high zero-inflation (30.05%), making it ideal for **Zero-Inflated Poisson (ZIP)** modeling.

Models compared:
- Poisson Regression
- Classical Zero-Inflated Poisson (ZIP)
- **ZIP Neural Network**

---

### 📁 Files

- `Zero_Inflated_Poisson_Neural_Network_bioChemists.ipynb`: Colab notebook containing data preprocessing, model training, and results comparison.
- `article_publications.csv`: Dataset used in the notebook (preprocessed).

---

### 📊 Evaluation Metrics

| Model                  | MAE  | MSE  | RMSE |
|------------------------|------|------|------|
| **ZIP NN**              | 1.22 | 2.95 | 1.72 |
| Poisson Regression      | 1.30 | 3.05 | 1.75 |
| Classical ZIP           | 1.30 | 3.28 | 1.81 |

> ✅ Our proposed **ZIP Neural Network** outperforms both baseline models across all evaluation metrics.

---

### 🔧 Requirements

- Python 3.x
- Colab (or Jupyter Notebook)
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `torch`, `statsmodels`

Install dependencies:
```bash
pip install pandas numpy scikit-learn torch statsmodels
```
## 📬 Contact

Created by [Taranom Torabi](mailto:taranom.torabi1377@gmail.com) — feel free to reach out with any questions or feedback!
