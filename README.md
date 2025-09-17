
# Advanced Fraud Detection System using Machine Learning

## 🎯 Project Overview

A comprehensive fraud detection system built with machine learning to identify fraudulent financial transactions. The solution processes over 6.36 million transactions and achieves high AUC/recall on a severe class imbalance.

## 🚀 Key Features

- High performance: 99.98% AUC using XGBoost
- SMOTE for extreme class imbalance
- End-to-end ML workflow: Preprocessing → Modeling → Deployment
- Actionable business insights and real-time scoring readiness

## 📊 Dataset

- Over 6,362,620 transaction samples
- Features: 10+ (transaction amount, type, balances, etc)
- Target: Binary (fraud vs legitimate)
- Challenge: Highly imbalanced dataset (fraud <1%)

## 🛠️ Technical Stack

- **Pandas/Numpy** – Data loading & preprocessing
- **Scikit-learn** – Feature engineering & evaluation metrics
- **XGBoost** – Main ML model
- **SMOTE** – Class imbalance handling
- **Matplotlib/Seaborn** – Visualization
- **Colab/Jupyter** – Development environment

## 📈 Model Performance

| Metric     | Score    |
|------------|----------|
| **AUC**    | 99.98%   |
| **Recall** | 98.7%    |
| **Precision** | ~17%  |
| **F1-score** | ~29%   |

- Handles modern financial fraud detection at enterprise scale
- False negatives (missed fraud): <2% in validation

## 🔧 Installation & Usage

### Environment

- Python 3.8+
- Google Colab (recommended) or Jupyter Notebook

### Install dependencies

```

pip install xgboost imbalanced-learn pandas numpy matplotlib seaborn scikit-learn

```

### Usage

1. **Clone or download the repository**
2. **Upload `Fraud_assignment.ipynb` to Colab**
3. **Upload your CSV dataset (`dataset.csv`)**
4. **Edit the data path in the code if needed**
5. **Run all cells sequentially**

## 📋 Project Structure

```

fraud-detection-system/
│
├── Fraud_assignment.ipynb        \# Main notebook
├── README.md                     \# Project documentation
├── requirements.txt              \# Python dependencies
│
├── data/
│   └── dataset.csv               \# (user-provided) transactions file
│
├── models/
│   ├── fraud_model.pkl           \# Saved model (produced after training)
│   └── scaler.pkl                \# Saved scaler for deployment
│
└── outputs/
└── evaluation_report.txt     \# Model performance summary

```

## 🧑‍💻 How it Works

- **Data Exploration:** Previews, missing values, class ratios
- **Preprocessing:** Categorical encoding, scaling, outlier checks
- **Balancing:** SMOTE for synthetic minority fraud samples
- **Training:** XGBoost model, scaled_pos_weight to further address imbalance
- **Validation:** Confusion matrix, precision/recall/F1/AUC, ROC curve plotting
- **Feature Importance:** Ranked impact of variables in prediction
- **Business Insights:** Thresholds, auto-actions, monitoring strategy

## 💼 Business Value

- Production-ready fraud classification for large-scale financial institutions
- Real-time scoring compatible
- Recommended: Automated blocks/flags for high-risk scores
- Integration-ready: API/batch processing

## 📞 Contact

**Author:** Suman Banerjee  
**Email:** indsumanttt2002@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/suman-banerjee-394822261/

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

⭐️ *If you found this helpful, please star the repository!* ⭐️
```

