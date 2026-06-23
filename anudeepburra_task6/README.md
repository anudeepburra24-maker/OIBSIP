# Fraud Detection using Machine Learning

## Oasis Infobyte Data Analytics Internship - Level 2 Task

### Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning classification algorithms. Fraud detection is a critical application in the banking and financial sector, where machine learning helps identify suspicious transactions while minimizing false alarms.

The project compares the performance of three classification models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Objectives

- Load and explore the credit card fraud dataset.
- Perform data preprocessing and cleaning.
- Analyze class distribution.
- Split the dataset into training and testing sets.
- Train multiple machine learning classification models.
- Evaluate model performance using various metrics.
- Compare model accuracies.
- Visualize results using confusion matrices and charts.

---

## Dataset

**Dataset:** Credit Card Fraud Detection Dataset

The dataset contains anonymized credit card transactions with the following information:

- Time
- V1 to V28 (PCA transformed features)
- Amount
- Class
  - 0 → Legitimate Transaction
  - 1 → Fraudulent Transaction

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Explore Dataset
4. Check Missing Values
5. Analyze Class Distribution
6. Feature Selection
7. Train-Test Split
8. Model Training
9. Prediction
10. Model Evaluation
11. Accuracy Comparison
12. Feature Importance Analysis
13. Data Visualization

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Visualizations

The project includes:

- Fraud vs Legitimate Transaction Distribution
- Correlation Heatmap
- Confusion Matrix
- Model Accuracy Comparison
- Top Feature Importance (Random Forest)

---

## Key Insights

- The dataset is highly imbalanced, with fraudulent transactions representing only a small fraction of the total data.
- Random Forest achieved the best overall performance among the evaluated models.
- Decision Tree provided fast predictions but was more prone to overfitting.
- Logistic Regression served as a strong baseline model.
- Feature importance analysis highlighted the most influential variables for fraud detection.

---

## Business Recommendations

- Deploy machine learning models for real-time fraud monitoring.
- Continuously retrain models using newly available transaction data.
- Address class imbalance using techniques such as SMOTE or undersampling to improve fraud detection.
- Combine machine learning predictions with rule-based systems for enhanced accuracy.
- Regularly monitor model performance and update it as fraud patterns evolve.

---

## Project Structure

```
Fraud_Detection/

│── Fraud_Detection.ipynb
│── creditcard.csv
│── fraud_detection_model.pkl
│── model_accuracy.csv
│── README.md
│── requirements.txt
```

---

## How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

3. Open the Jupyter Notebook.

4. Run all cells sequentially.

---

## Learning Outcomes

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Binary Classification
- Fraud Detection
- Machine Learning Model Building
- Model Evaluation
- Feature Importance Analysis
- Data Visualization

---

## Future Improvements

- Apply SMOTE to balance the dataset.
- Perform hyperparameter tuning using GridSearchCV.
- Experiment with XGBoost and LightGBM.
- Build a real-time fraud detection API using Flask or FastAPI.
- Deploy the model on cloud platforms for production use.

---

## Author

**Burra Anudeep**

Data Analytics Intern

Oasis Infobyte Internship

**LinkedIn:** https://www.linkedin.com/in/anudeep-burra-6705a838b

---
