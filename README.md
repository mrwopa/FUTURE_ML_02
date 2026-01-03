📉 Customer Churn Prediction System

An end-to-end Machine Learning system designed to predict customer churn using supervised learning models.
Built as part of a Machine Learning internship, this project focuses on real-world business impact, model evaluation, and decision-driven insights.

🚀 Project Overview

Customer churn is one of the most critical challenges businesses face — retaining existing customers is often more cost-effective than acquiring new ones.

This project builds and evaluates multiple machine learning models to predict whether a customer is likely to churn, enabling businesses to take proactive retention actions.

🎯 Objectives

Predict customer churn with high reliability

Compare multiple ML algorithms

Evaluate models using business-relevant metrics

Identify the best-performing model for deployment

Provide insights that support decision-making

🧠 Models Implemented

Three supervised learning models were trained, tested, and compared:

1️⃣ Logistic Regression

Baseline interpretable model

Strong for understanding feature influence

Performance:

Accuracy: 75.94%

ROC-AUC: 0.829

Precision (Churn): 0.50

Recall (Churn): 0.72

2️⃣ Random Forest Classifier

Ensemble method for capturing non-linear relationships

Improved generalization over baseline

Performance:

Accuracy: 78.28%

ROC-AUC: 0.844

Precision (Churn): 0.54

Recall (Churn): 0.70

3️⃣ XGBoost (Extreme Gradient Boosting)

High-performance boosting algorithm

Best balance between bias and variance

Performance:

Accuracy: 78.35%

ROC-AUC: 0.832

Training Accuracy: 95.42%

Testing Accuracy: 78.35%

📊 Evaluation Metrics Used

To ensure realistic business insights, the following metrics were used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC-AUC

Precision-Recall AUC (PR-AUC)

⚠️ Emphasis was placed on Recall for churned customers, as missing a churn-prone customer can be costly.

📈 Key Results Summary
Model	Accuracy	ROC-AUC	PR-AUC
Logistic Regression	75.9%	0.829	0.567
Random Forest	78.3%	0.844	0.624
XGBoost	78.4%	0.832	0.623

✅ Random Forest and XGBoost emerged as the top performers, offering strong predictive power and stability.

🛠️ Tech Stack

Programming Language: Python

Libraries & Tools:

scikit-learn

XGBoost

Pandas

NumPy

Matplotlib / Seaborn

Modeling: Logistic Regression, Random Forest, XGBoost

Evaluation: Confusion Matrix, ROC-AUC, PR-AUC

Environment: Jupyter Notebook / Google Colab

📂 Project Structure
📁 Churn-Prediction-System
│
├── Churn_prediction_system.ipynb   # Full ML pipeline
├── README.md                       # Project documentation

💡 Business Insights

The models effectively identify customers at risk of churn

Ensemble models outperform linear models

A ~78% accurate model with strong recall is more valuable than a highly overfitted model

Results can be used to:

Trigger retention campaigns

Improve customer engagement strategies

Optimize marketing spend

🧪 What I Learned

Real-world data is noisy and imbalanced

Accuracy alone is not enough — ROC-AUC & Recall matter

Trade-offs between interpretability and performance

How to compare models objectively

End-to-end ML workflow from data preprocessing to evaluation

🤝 Collaboration

This project was built with support from a colleague, highlighting the importance of team collaboration in applied machine learning environments.

📌 Future Improvements

Feature importance analysis

Hyperparameter tuning (GridSearch / Optuna)

Model explainability (SHAP, LIME)

Deployment as an API or dashboard

Handling class imbalance with SMOTE

📜 Disclaimer

This project was developed for educational and internship purposes and demonstrates applied machine learning concepts in a real-world business scenario.

📬 Contact

Babalola Samuel Olamilekan
📧 Email: babalolas111@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/babsam1

💻 GitHub: https://github.com/mrwopa
