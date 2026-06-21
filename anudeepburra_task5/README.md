# Wine Quality Prediction using Machine Learning

## Oasis Infobyte Data Analytics Internship - Level 2 Task 2

### Project Overview

This project focuses on predicting the quality of wine based on its chemical properties using machine learning classification algorithms. The objective is to analyze various physicochemical characteristics of wine and build predictive models that can accurately classify wine quality.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and performance comparison.

---

## Objectives

* Load and explore the wine quality dataset.
* Perform data cleaning and preprocessing.
* Analyze relationships between chemical properties and wine quality.
* Train multiple machine learning classification models.
* Compare model performance using evaluation metrics.
* Visualize patterns and insights from the dataset.

---

## Dataset

**Dataset:** Wine Quality Dataset (WineQT.csv)

The dataset contains physicochemical properties of wine, including:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality (Target Variable)

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Algorithms

The following classification algorithms were implemented and compared:

* Random Forest Classifier
* Stochastic Gradient Descent (SGD) Classifier
* Support Vector Classifier (SVC)

---

## Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Data Exploration
4. Handle Missing Values
5. Remove Duplicate Records
6. Exploratory Data Analysis (EDA)
7. Feature Selection
8. Split Dataset into Training and Testing Sets
9. Train Classification Models
10. Predict Wine Quality
11. Evaluate Model Performance
12. Compare Classifier Accuracy
13. Visualize Results

---

## Data Visualization

The project includes the following visualizations:

* Correlation Heatmap
* Wine Quality Distribution
* Alcohol vs Quality
* Volatile Acidity vs Quality
* Confusion Matrix
* Model Accuracy Comparison

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

Among the three models, the **Random Forest Classifier** achieved the highest prediction accuracy and provided the best overall performance.

---

## Key Insights

* Alcohol content shows a positive relationship with wine quality.
* Higher volatile acidity is generally associated with lower-quality wines.
* Most wines in the dataset belong to quality levels 5 and 6.
* The dataset is imbalanced, with fewer samples in extreme quality classes.
* Random Forest outperformed SGD and SVC for this classification task.

---

## Business Recommendations

* Improve production processes to optimize important chemical characteristics such as alcohol content and acidity.
* Collect more samples for underrepresented quality categories to improve model performance.
* Use machine learning models to support quality control in wine production.
* Perform regular model retraining using updated datasets for improved prediction accuracy.
* Explore advanced ensemble learning techniques for enhanced performance.

---

## Project Structure

Task5_Wine_Quality_Prediction/

* BurraSandeep_Task5.ipynb
* WineQT.csv
* README.md
* requirements.txt

---

## How to Run

1. Clone this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook.
4. Run all notebook cells sequentially.

---

## Learning Outcomes

* Machine Learning Classification
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Selection
* Model Training
* Model Evaluation
* Data Visualization
* Performance Comparison of Multiple Classifiers

---

## Author

**Burra Anudeep**

Data Analytics Intern

Oasis Infobyte Internship


LinkedIn: https://www.linkedin.com/in/anudeep-burra-6705a838b/

---

## Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship**. It provided valuable hands-on experience in applying machine learning classification algorithms to solve a real-world prediction problem and strengthened my understanding of predictive analytics, model evaluation, and data-driven decision-making.
