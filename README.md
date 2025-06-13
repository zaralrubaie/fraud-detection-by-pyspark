fraud-detection-by-pyspark
# 💳 Fraud Detection using PySpark

This project uses **PySpark** to build a machine learning model for fraud detection on financial transaction data. It involves extensive data cleaning, feature engineering, handling class imbalance, and pipeline-based modeling for scalability.

---

## 📁 Project Files

- `sampled_100k_fraud.csv`: A sampled and cleaned dataset used due to hardware constraints.
- `part-00000-*.csv`: The output file containing predictions (predicted vs actual labels).
- `predictions_val_vs_actual.txt`: A plain text log file showing sample predictions and their evaluation.

---

##Objective
To detect fraudulent transactions using machine learning with PySpark and practice handling big data pipelines, feature transformation, model evaluation, and deployment-readiness on limited computing resources.

---
#Technologies & Tools
- **PySpark**
- **Pandas** (used for sampling before Spark load)
- **MLlib** (Spark ML pipeline for training)
- **Skewness handling** with `log1p`
- **Evaluation Metrics**: AUC, Confusion Matrix

---
# Challenges Faced
 1. Data Volume can not be handled by the laptop that the model was created on
-
