# credit-card-fraud-detection
Credit card fraud detection using supervised machine learning algorithms with performance evaluation using F1-score, ROC-AUC, and confusion matrix.


OVERVIEW


This project foucus on detecting fradulent credit card detection transctions using supervised machine learning algorithms. It address real world challenges such as highly imbalance data, false-positives and model optimization.
Build as a part of Data Science project, this solution demonstrates end-to-end implementation from data prepration, data training, evaluation and deployment readiness.


BUSINESS PROBLEM


Credit card fraud is a major issue in the financial sector, causing billions in losses globally. 
The key challenges include imbalance dataset(very few farud cases), high cost of false nagatives (missed fraud) and need real time detection. This project aims to build  a robust fraud detection model that minimize risk while maintaining high accuracy.


DATASET

1. Source: Kaggel Credit card fraud detection 

2. Record: 2,84,807 transactions 

3. Features: 30 (Time, Amount, V1-V28 anonymized features)

4. Target Varriable: 0=Legitime and 1=Fraud


TECH STACK

Programming: Python 

Libraries: Pandas, NumPy, Scikit-learn, Imbalance-learn

Visualization: Matplotlib, Seaborn

Deplyment Ready: Flask API


PRJECT WORKFLOW

1. Data preprocessing

   1.1 Feature Handling using RobustScaler

   1.2 Handling missing values

   1.3 Correlation analysis

2. Handling Imbalance data

   2.1 Random Under-Sampling

   2.2 Random Over-Sampling

   2.3 SMOTE (Synthetic Minority Over-sampling Technique)

3. Model Traning

   The following supervised learing models were implemented:

   3.1 Logestic Regression

   3.2 Decision Tree Classifier

   3.3 Random Forest Classifier

4. Model Evalution

   Models were evaluted using:

   4.1 Accuracy

   4.2 Precision

   4.3 Recall

   4.4 F1 Score

   4.4 ROC-AUC Curve


RESULTS
     Model                             Proformance Summary

Logistic Regression            Good baseline but affected by imbalance

Decision Tree                  High accuracy but prone to overfitting

Random Forest                  Best performance overall



KEY FINDINGS
1. Random Forest provided the most balanced and reliable performance
2. SMOTE significantly improved fraud detection recall
3. Feature scaling improved model consistency
4. Evalution metrics beyond accuracy are critical in fraud detection


 PROJECT VISUALIZATIONS
 1. ROC-AUC cuve
 2. Confussion Matrix
 3. Feature Correlation Heatmap
 4. Transaction Distribution Graphs


DEPLOYMENT (OPTIONAL API)
A simple API can be created using Flsak
python app.py
Endpoint:
POST /predict


BUSINESS IMPACT 
This system can help:
1. Bank detect fraudulent transactions in real-time
2. Reduce financial losses
3. Improve customer trust
4. Support decision-making with data-driven insights


FUTURE IMPROVEMENTS
1. Real-time fraud detection system
2. Deep Learning models (CNN,RNN)
3. Explainable AI (XAI)
4. Cloud deployment (AWS/Azure)


👨‍💻 Author
Irfan Khalid
Data Scientist | Machine Learning Enthusiast
📍 Open to opportunities in Saudi Arabia (KSA)
📫 irfan.khalid821@gmail.com 
🔗 https://www.linkedin.com/in/irfan-khalid-muhamad-khalid-8b0679130
💻 https://github.com/irfankhalid821-stack

IF YOU FOUND THIS PROJECT USEFUL
Give it a ⭐ on github and feel free to connect!


