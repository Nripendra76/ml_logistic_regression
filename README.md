# ml_logistic_regression
📌 Overview

This project demonstrates a complete implementation of Logistic Regression including:

✔ Binary Classification
✔ Hyperparameter Tuning
✔ Multiclass Classification
✔ Imbalanced Dataset Handling
✔ ROC Curve & AUC

📊 Dataset
Synthetic dataset using make_classification
1000 samples, 10 features


⚙️ Tech Stack
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
📈 Results Summary
Model Type	Accuracy
Base Model	91.67%
GridSearchCV	92%
RandomizedSearchCV	92.66% 🚀
Multiclass Model	79%
Imbalanced Dataset	99.2% ⚠️
⚡ Hyperparameter Tuning
🔹 Best GridSearchCV Params
C = 0.01
penalty = elasticnet
solver = saga
l1_ratio = 0.5
🔹 Best RandomizedSearchCV Params
C = 0.1
penalty = l1
solver = liblinear
📉 ROC Curve & AUC
Dummy Model AUC: 0.5
Logistic Model AUC: 0.8776
5
⚖️ Imbalanced Dataset Insight
Accuracy: 99.2%
But recall for minority class is low ⚠️
👉 Shows why accuracy alone is misleading
▶️ How to Run
git clone https://github.com/your-username/logistic-regression.git
cd logistic-regression
pip install -r requirements.txt
jupyter notebook
💡 Key Learnings

✔ Logistic Regression is powerful for classification
✔ Hyperparameter tuning boosts performance
✔ ROC-AUC is better than accuracy for evaluation
✔ Handle imbalanced data carefully

🚀 Future Improvements
Add feature scaling pipeline
Use cross-validation properly
Try advanced models (XGBoost, Random Forest)

Deploy with Streamlit
⭐ Support

If you like this project, give it a ⭐ on GitHub!
