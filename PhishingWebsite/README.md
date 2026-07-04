# Phishing URL Detection Using Machine Learning

## Project Overview
The goal of this project is to build and compare machine learning classification models to accurately identify phishing websites based on URL-related features.

## Model Architecture
The solution compares three distinct classification models to determine the most effective approach for phishing detection:
* **Support Vector Machine (SVM)**
* **Random Forest**
* **XGBoost**

## Key Techniques Used
To ensure high accuracy and robust detection, we implemented the following:
* **Data Preprocessing:** Handled missing values, removed non-predictive columns (like IDs), and performed feature scaling using `StandardScaler`.
* **Feature Engineering:** Analyzed URL-based features such as domain structure, hyperlinks, redirects, and HTML characteristics.
* **Model Evaluation:** Evaluated performance using comprehensive metrics, including Accuracy, Precision, Recall, F1-score, and AUC.

## Results
The models demonstrated high performance in identifying malicious URLs:
* **Random Forest:** Achieved the highest accuracy at **98.55%**.
* **XGBoost:** Achieved **98.45%** accuracy with excellent recall.
* **SVM:** Achieved **96.90%** accuracy.

## Key Takeaways
* Ensemble models (Random Forest and XGBoost) proved most effective for this dataset.
* URL structure and domain characteristics are critical indicators for distinguishing phishing sites from legitimate ones.

## Contributors
* Sara Alrowaily
* Jumana Alothman
* Samar Alfallaj
* Lama Almughamis
* Razan Alenazi