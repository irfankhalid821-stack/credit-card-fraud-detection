💳 Credit Card Fraud Detection System


🚀 Business Problem

Credit card fraud is a growing global issue, causing billions in financial losses. Detecting fraudulent transactions is challenging due to highly imbalanced data and evolving fraud patterns.


🎯 Objective

To build and evaluate machine learning models for accurate fraud detection using real-world transaction data.


📊 Dataset

Source: Kaggle Credit Card Dataset

Transactions: 284,807

Fraud Cases: ~0.17% (highly imbalanced)


⚙️ Methodology

Data preprocessing and scaling

Feature analysis (Time, Amount, PCA features)

Handling class imbalance using:
SMOTE
Random Over/Under Sampling

Models implemented:
Logistic Regression
Decision Tree
Random Forest
Hyperparameter tuning using GridSearchCV


📈 Model Evaluation
Models were evaluated using:
Accuracy
Precision
Recall
F1-Score
ROC-AUC


🏆 Key Results
Random Forest achieved the best overall performance
SMOTE significantly improved fraud detection recall
Trade-off observed between precision and recall


🔍 Key Insights
Class imbalance is the biggest challenge in fraud detection
Ensemble models outperform single models
Proper preprocessing significantly improves results


🧠 Skills Demonstrated
Machine Learning (Scikit-learn)
Data Preprocessing & Feature Engineering
Imbalanced Data Handling
Model Evaluation & Optimization
Data Visualization


🖥️ Tech Stack

1. Python
2. Pandas 
3. NumPy 
4. Scikit-learn
5. Matplotlib
6. Seaborn


💡 Business Value

Helps financial institutions detect fraudulent transactions early
Reduces financial loss and improves customer trust
Can be adapted for real-time fraud detection systems


📂 Project Structure


/data /notebooks /src preprocessing.py models.py evaluation.py 




▶️ How to Run
pip install -r requirements.txt jupyter notebook
