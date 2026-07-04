# E-Commerce Customer Churn Prediction

A Machine Learning project to predict customer churn in e-commerce using Logistic Regression, Random Forest, and XGBoost.

---

## Project Overview

Customer churn is one of the biggest challenges for e-commerce businesses. This project builds a classification model to identify customers who are likely to stop purchasing, enabling businesses to take proactive retention actions.

**Result:** XGBoost achieved **98.05% accuracy** with **0.94 F1-Score**

---

## Dataset

- **Source:** Kaggle — Ankit Verma
- **Records:** 5,630 customers
- **Features:** 20 (demographic + behavioral + transactional)
- **Target:** Churn (1 = Churned, 0 = Active)
- **Churn Rate:** ~17%

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Programming Language |
| Google Colab | Development Environment |
| Pandas | Data Manipulation |
| Matplotlib / Seaborn | Data Visualization |
| Scikit-learn | ML Models and Evaluation |
| XGBoost | Best Performing Model |

---

## Project Pipeline

```
Data Loading → EDA → Missing Value Treatment → 
Feature Engineering → Train/Test Split → 
Model Training → Evaluation → Insights
```

---

## Model Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|---------|-----------|--------|---------|
| Logistic Regression | 89.08% | 0.80 | 0.75 | 0.77 |
| Random Forest | 98.05% | 0.97 | 0.91 | 0.94 |
| **XGBoost** | **98.05%** | **0.97** | **0.91** | **0.94** |

---

## Key Findings

- **Complaint history** is the strongest predictor of churn
- **Inactive customers** (high DaySinceLastOrder) are at high risk
- **Tier 3 city** customers churn more than metro customers
- **Low cashback** customers are more likely to leave
- **Single** customers churn more than married customers

---

## Business Recommendations

- Prioritize complaint resolution — it is the top churn driver
- Re-engage customers inactive for 30+ days with personalized offers
- Invest in Tier 3 city delivery and product availability
- Design cashback programs that reward long-term loyalty
- Monitor satisfaction scores and intervene proactively

---

Project Structure

```
Ecommerce-Churn-Prediction/
│
├── Ecommerce_Churn_Prediction.ipynb   # Main Colab notebook
├── E Commerce Dataset.csv             # Dataset
├── Report.pdf                         # Project report
├── Presentation.pptx                  # Project slides
└── README.md                          # This file
```


How to Run

1. Clone this repository
```bash
git clone https://github.com/yourusername/Ecommerce-Churn-Prediction.git
```

2. Open `Ecommerce_Churn_Prediction.ipynb` in Google Colab

3. Upload `E Commerce Dataset.csv` when prompted

4. Run all cells sequentially



## Author

Nidhi Sharma
UID: O24MSD110142
MSc Data Science | Chandigarh University | June 2026


## References

1. Verbeke et al. (2012) — Churn prediction in telecommunications
2. Chen & Guestrin (2016) — XGBoost: A Scalable Tree Boosting System
3. Breiman (2001) — Random Forests
4. Kaggle Dataset — Ankit Verma (2022)

