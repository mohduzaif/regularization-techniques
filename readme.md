# ML Regularization

This repository provides a practical and conceptual understanding of
regularization techniques in machine learning. It demonstrates how
regularization helps control overfitting, improve generalization, and
handle multicollinearity in linear models.

The implementation is dataset-agnostic, meaning the techniques shown
here can be applied to any suitable regression dataset.

---

## 📂 Repository Structure

```text
ml-regularization/
│
├── Notebooks/
│   ├── Ridge_Regularization.ipynb
│   ├── Lasso_Regularization.ipynb
│   └── Elastic_net_Regularization.ipynb
│
├── NOTES/
│   ├── Regularization_Overview.pdf
│   ├── Ridge_Lasso_ElasticNet.pdf
│   └── Bias_Variance_Tradeoff.pdf
│
├── requirements.txt
└── README.md
```


## Regularization Techniques Covered

- Linear Regularization (Baseline)
- Ridge Regularization (L2 Regularization)
- LASSO Regularization (L1 Regularization)
- Elastic Net Regularization (L1 + L2 Regularization)

---

## Learning Objectives

- Understand overfitting and underfitting
- Learn why regularization is required
- Observe the effect of L1 and L2 penalties on model coefficients
- Compare Ridge, LASSO, and Elastic Net models
- Understand the bias–variance tradeoff

---

## Dataset

No dataset is fixed for this repository.

You may use:
- Any regression dataset from sklearn
- Kaggle datasets
- Custom or academic datasets

The notebooks are written in a way that they can be easily adapted to
different datasets with minimal changes.

---

## Requirements

Install the required libraries using:

pip install -r requirements.txt

---

## How to Use

1. Clone the repository
2. Install dependencies
3. Open the notebooks inside the Notebooks folder
4. Run the notebooks in sequential order (01 → 05)

---

## Key Takeaways

- Ridge regression reduces model variance by shrinking coefficients
- LASSO regression performs feature selection by setting coefficients to zero
- Elastic Net combines the strengths of Ridge and LASSO
- Feature scaling is critical when using regularization techniques

---

## 👨‍💻 Author  
**Mohd Uzaif**  
🎓 *M.Tech (AI & ML), Jamia Millia Islamia University*   
---

⭐ *If you find these notebooks useful, consider giving this repo a star — it helps and motivates continuous learning!*  
EOF
