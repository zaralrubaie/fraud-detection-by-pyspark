fraud-detection-by-pyspark
# 💳 Fraud Detection using PySpark

This project uses **PySpark** to build a machine learning model for fraud detection on financial transaction data. It involves extensive data cleaning, feature engineering, handling class imbalance, and pipeline-based modeling for scalability.

---

##Project Files
`fraud-detection-by-pyspark.ipynb`  
  ➤ The main Jupyter Notebook with full code: data loading, cleaning, feature engineering, model training, and evaluation.

- `predection results.csv`  
  ➤ Contains predicted vs actual values for the validation set.

- `model_evaluation_txt.txt`  
  ➤ Text file summarizing evaluation results (AUC, accuracy, etc.).

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
Data Volume can not be handled by the laptop that the model was created on
-
