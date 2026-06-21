# Data Cleaning using Airbnb NYC 2019 Dataset

## Oasis Infobyte Data Analytics Internship – Level 1 Task 3

### Project Overview

This project demonstrates the process of cleaning and preprocessing the Airbnb NYC 2019 dataset to improve data quality and prepare it for analysis. Data cleaning is a critical step in the data analytics pipeline, ensuring that datasets are accurate, consistent, complete, and suitable for meaningful analysis and machine learning applications.

---

## Objectives

* Load and inspect the Airbnb NYC 2019 dataset.
* Identify and handle missing values.
* Detect and remove duplicate records.
* Standardize column names and data formats.
* Perform descriptive statistical analysis.
* Detect potential outliers using visualization techniques.
* Export the cleaned dataset for future analysis.

---

## Dataset

**Dataset:** Airbnb NYC 2019

The dataset contains information about Airbnb listings across New York City, including:

* Listing ID
* Listing Name
* Host ID and Host Name
* Neighbourhood Group
* Neighbourhood
* Latitude & Longitude
* Room Type
* Price
* Minimum Nights
* Number of Reviews
* Last Review Date
* Reviews Per Month
* Calculated Host Listings Count
* Availability (365 Days)

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Explore Dataset Structure
4. Identify Missing Values
5. Remove Duplicate Records
6. Handle Missing Data
7. Standardize Column Names
8. Perform Descriptive Statistics
9. Detect Outliers
10. Visualize Data
11. Export the Cleaned Dataset

---

## Data Cleaning Techniques

* Removed duplicate records to improve data integrity.
* Handled missing values using appropriate strategies.
* Converted date columns into proper datetime format.
* Standardized column names for consistency.
* Verified the dataset after cleaning.
* Exported the cleaned dataset for further analysis.

---

## Data Visualizations

The project includes the following visualizations:

* Price Distribution
* Price Box Plot (Outlier Detection)
* Room Type Distribution
* Neighbourhood Group Distribution
* Correlation Heatmap

---

## Key Insights

* Missing values were successfully identified and treated.
* Duplicate records were removed to improve dataset quality.
* Price distribution contains several high-value outliers representing premium listings.
* Entire home/apartment is the most frequently listed room type.
* Manhattan and Brooklyn have the highest concentration of Airbnb listings.
* The cleaned dataset is ready for exploratory data analysis and machine learning applications.

---

## Business Recommendations

* Validate datasets before performing any analysis.
* Remove duplicate records to maintain consistency.
* Handle missing values appropriately rather than deleting data unnecessarily.
* Investigate outliers before building predictive models.
* Maintain standardized data formats and naming conventions across datasets.

---

## Project Structure

```text
Task3_Data_Cleaning/
│
├── anudeepburra_task3.ipynb
├── AB_NYC_2019.csv
├── cleaned_AB_NYC_2019.csv
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook.
4. Run all notebook cells sequentially.

---

## Learning Outcomes

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Duplicate Removal
* Data Standardization
* Outlier Detection
* Exploratory Data Analysis (EDA)
* Data Visualization

---

## Author

**Burra Anudeep**

Data Analytics Intern | Oasis Infobyte

**LinkedIn:** https://www.linkedin.com/in/anudeep-burra-6705a838b

**GitHub:** https://github.com/anudeepburra24-maker

---

## Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Analytics Internship**. It provided practical experience in data preprocessing, cleaning techniques, exploratory data analysis, and preparing high-quality datasets for analytics and machine learning applications.

