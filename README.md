# Final-year-project
Mental Health Treatment Recommendation System
Using Gradient Boosting & Machine Learning

This project presents a Machine Learning–based Mental Health Treatment Recommendation System, developed as part of an academic research publication. The system predicts whether an individual may require mental health treatment based on demographic, employment, and workplace-related factors.

It uses a Gradient Boosting Classifier, supported by advanced preprocessing and a complete ML pipeline, achieving a prediction accuracy of 79.7%.

Abstract

Modern society faces increasing mental health challenges, highlighting the need for intelligent early-detection systems.
This project uses machine learning to recommend whether a person is likely to need mental health treatment. The model leverages demographic attributes, workplace support data, and mental health history to predict treatment needs with high reliability.

Key steps include:

Comprehensive data cleaning & preprocessing

One-hot and label encoding

Feature scaling

Model training using Gradient Boosting

Evaluation using accuracy, precision, recall, ROC Curve & PR Curve

The system attains 79.7% prediction accuracy, demonstrating its usefulness for individuals and organizations seeking early warning indicators.

🧩 Features

✔️ Predicts likelihood of needing mental health treatment

✔️ Gradient Boosting–based model

✔️ Flask-based deployment-ready API

✔️ Clean data preprocessing pipeline

✔️ Encodes both categorical & numerical features

✔️ Visualizations: Heatmap, ROC Curve, Precision–Recall Curve

✔️ Train-test split, EDA, outlier handling

✔️ Achieves industry-acceptable accuracy for early risk detection

🚀 Tech Stack

Programming: Python
Libraries:

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Flask (for deployment)

📊 Dataset Details

Total rows: 1,265

Columns: 27

Contains demographic + workplace mental health survey data.

Preprocessing Steps:

Handled missing values

Encoded categorical fields

Normalized numerical features

Outlier treatment

Exploratory Data Analysis (EDA)

Train-Test Split (80–20)

Visualizations include:

Heatmap (feature correlations)

Classification distribution

ROC Curve

Precision–Recall Curve

🏗️ Methodology
1️⃣ Data Collection

Dataset acquired from public mental health survey sources (GitHub).

2️⃣ Data Preprocessing

Cleaning & imputation

Feature encoding (Label + One-hot)

Dealing with outliers

Feature scaling

Splitting into train & test sets

3️⃣ Model Building

Evaluated multiple ML models:

Gradient Boosting Classifier

Random Forest

Decision Tree

Logistic Regression

SVM

Gradient Boosting performed best.

4️⃣ Model Evaluation

Metrics measured:

Accuracy

Precision

Recall

F1-Score

MSE

Key Results:

Accuracy: 79.7%

Strong ROC and PR curves

Good discriminative performance

📈 Results

The Gradient Boosting model demonstrated:

High accuracy in predicting mental health treatment requirement

Consistent precision and recall

Strong ability to classify treatment vs non-treatment groups

Good generalization on test data

This makes the system suitable for:

Workplace mental health screening

Early detection tools

Research analysis

Behavioral analytics

Counseling support systems

🏁 Conclusion

Predicting mental health needs is inherently complex due to diverse human factors.
However, the implemented ML model shows strong results:

79.7% accuracy

Strong performance across precision, recall & AUC

Useful for scalable organizational deployment

Supports proactive mental health intervention

The system demonstrates that ML can effectively support mental health awareness and enterprise-level decision making.

🔮 Future Scope

Enhancements planned:

Increase dataset size for higher generalization

Integrate advanced deep learning models

Real-time prediction support

User-friendly dashboards

Mobile integration

Open-source expansion

Adaptive learning based on continuous feedback

👥 Authors

Dr. G. Bharathi – Guide / Professor

Lukesh Praveen – UG Student

Vana Chandana – UG Student

Kamal Nadh Lukka – UG Student

Divya Sri – UG Student
