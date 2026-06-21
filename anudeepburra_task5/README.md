🍷 Wine Quality Prediction using Machine Learning


📌 Project Overview

This project aims to predict the quality of wine based on its physicochemical properties using machine learning classification algorithms. It demonstrates how data science can be applied in the field of viticulture to evaluate wine quality using measurable chemical attributes.

🎯 Objective

To build a predictive model that classifies wine quality using features such as acidity, density, pH, alcohol content, and other chemical properties.

📊 Dataset Information

The dataset contains various chemical features of wine, including:

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Target variable: Wine Quality (score)
🧠 Machine Learning Models Used

The following classification models were implemented and compared:

🌲 Random Forest Classifier
📉 Stochastic Gradient Descent (SGD) Classifier
🧮 Support Vector Classifier (SVC)
🛠️ Tech Stack
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🔄 Workflow
Data Loading & Inspection
Exploratory Data Analysis (EDA)
Data Preprocessing (handling missing values, scaling, etc.)
Feature Selection & Correlation Analysis
Model Training
Model Evaluation
Performance Comparison

📈 Model Evaluation Metrics
Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix

📊 Results

Among the tested models, performance was compared based on classification metrics to identify the most effective algorithm for wine quality prediction.

🚀 How to Run the Project
# Clone the repository
git clone  https://github.com/anudeepburra24-maker/OIBSIP

# Navigate to project folder
cd wine-quality-prediction

# Install required libraries
pip install -r requirements.txt

# Run the notebook or script
python main.py


📁 Project Structure
wine-quality-prediction/
│
├── data/
│   └── wine_dataset.csv
├── notebooks/
│   └── analysis.ipynb
├── src/
│   └── model_training.py
├── requirements.txt
└── README.md


💡 Key Learnings
Understanding chemical properties and their impact on wine quality
Implementing and comparing multiple classification algorithms
Improving model performance through preprocessing and feature analysis
Visualizing data insights using Seaborn and Matplotlib


📌 Future Improvements
Hyperparameter tuning for better accuracy
Deployment using Flask or Streamlit
Adding deep learning models for comparison
Real-time wine quality prediction API


👨‍💻 Author

Burra Anudeep
