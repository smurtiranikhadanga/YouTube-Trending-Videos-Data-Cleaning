# 🎥 YouTube Trending Videos Data Cleaning

## 📌 Project Overview

This project focuses on cleaning and preprocessing the **YouTube Trending Videos Dataset** obtained from Kaggle. The objective is to improve data quality by identifying and resolving missing values, duplicate records, inconsistent data formats, and outliers while ensuring overall data integrity.

The cleaned dataset is prepared for Exploratory Data Analysis (EDA), visualization, and machine learning applications.

---

## 📂 Dataset

* **Dataset:** YouTube Trending Videos Dataset
* **Source:** Kaggle
* **Country:** United States (USvideos.csv)
* **Records:** 40,949
* **Features:** 16

---

## 🎯 Objectives

* Ensure data accuracy and integrity
* Handle missing values appropriately
* Remove duplicate records
* Standardize data formats
* Detect and treat outliers
* Validate the cleaned dataset
* Prepare data for analysis and machine learning

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📋 Data Cleaning Workflow

### 1. Dataset Inspection

* Loaded the dataset
* Examined dataset structure
* Checked data types
* Generated descriptive statistics

### 2. Data Integrity Checks

* Verified data types
* Checked for invalid values
* Validated numerical columns
* Performed consistency checks
* Verified duplicate records

### 3. Missing Value Handling

* Identified missing values
* Analyzed missing data patterns
* Filled missing descriptions using appropriate replacement values
* Verified successful handling of missing values

### 4. Duplicate Removal

* Detected duplicate records
* Removed duplicate entries while preserving data uniqueness

### 5. Data Standardization

* Removed unnecessary whitespace
* Converted date columns to datetime format
* Standardized text formatting
* Ensured consistent data representation

### 6. Outlier Detection

* Visualized outliers using boxplots
* Applied the Interquartile Range (IQR) method
* Identified extreme values
* Created a cleaned dataset after outlier treatment

### 7. Final Validation

* Verified missing values
* Checked duplicate records
* Validated dataset dimensions
* Calculated overall data quality score

---

## 📊 Visualizations

The following visualizations were created during the data cleaning process:

* Missing Values Bar Chart
* Missing Values Heatmap
* Boxplot Before Outlier Removal
* Boxplot After Outlier Removal
* Histogram of Views
* Correlation Heatmap
* Top 10 Video Categories
* Distribution of Likes
* Distribution of Comment Counts

---

## 📈 Data Cleaning Techniques Applied

* Data Integrity Verification
* Missing Value Imputation
* Duplicate Detection & Removal
* Data Standardization
* Date-Time Conversion
* Outlier Detection using IQR
* Data Validation
* Quality Assessment

---
## Dataset

The dataset used in this project is too large to be included in this repository.

You can download it from Kaggle:

https://www.kaggle.com/datasets/datasnaek/youtube-new
(import kagglehub
# Download latest version
path = kagglehub.dataset_download("datasnaek/youtube-new")
print("Path to dataset files:", path)
)
After downloading, place the `USvideos.csv` file in the project folder before running the notebook.

## 📁 Project Structure

```
YouTube-Data-Cleaning/
│
│
├── notebook/
│   └── YouTube_Data_Cleaning.ipynb
│
├── images/
│   ├── missing_values_bar_chart.png
│   ├── missing_values_heatmap.png
│   ├── boxplot_before_outlier_removal.png
│   ├── boxplot_after_outlier_removal.png
│   ├── histogram_views.png
│   ├── correlation_heatmap.png
│   ├── top10_categories.png
│   ├── likes_distribution.png
│   └── comments_distribution.png
│
├── report/
│   └── Data_Cleaning_Report.pdf
│
└── README.md
```

---

## 📌 Key Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Data Validation
* Data Integrity
* Missing Data Handling
* Duplicate Removal
* Data Standardization
* Outlier Detection
* Exploratory Data Analysis (EDA)
* Data Visualization
* Python Programming
* Pandas
* NumPy

---

## 🚀 Results

* Successfully cleaned and validated the YouTube Trending Videos dataset.
* Improved data quality by handling missing values and removing duplicate records.
* Standardized data formats for consistency.
* Detected and treated outliers using the IQR method.
* Generated a clean dataset suitable for visualization, statistical analysis, and machine learning.

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Building a complete data cleaning pipeline
* Applying real-world data preprocessing techniques
* Performing data quality assessments
* Creating meaningful visualizations
* Preparing datasets for analytics and machine learning workflows

---

## 📬 Contact

If you have any suggestions or feedback, feel free to connect with me through GitHub or LinkedIn.
