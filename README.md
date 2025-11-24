**Delivery Data Cleaning & Preprocessing – Python Project**

This project focuses on cleaning, transforming, and preparing a delivery dataset for further analysis.
The goal is to ensure the dataset is accurate, consistent, and ready for downstream analytics or modeling.

📌 Project Objective

**To clean raw delivery data by:**

1.Fixing incorrect formats

2.Handling missing or inconsistent values

3.Removing outliers

4.Extracting time-based features

5.Improving the dataset structure for analysis

**This project highlights essential data-wrangling skills using Python and Pandas.**

🛠 Tools & Libraries

Python

Pandas

NumPy

Jupyter Notebook / Google Colab

📁 Dataset Overview

The dataset contains delivery-related features such as:

order_time

city

delivery_time_mins

rating

Delivery partner information

🔧 Steps Performed
1. Data Loading

Imported and previewed the dataset to understand structure, column types, and initial issues.

2. Data Cleaning

Performed essential cleanup steps:

Converted order_time to datetime

Standardized column types

Checked and handled missing values

Cleaned inconsistent entries

3. Feature Engineering

Created useful new columns:

hour – extracted from timestamp

date – used for daily trend analysis

Additional derived fields (optional)

Example Code:

df['hour'] = df['order_time'].dt.hour
df['date'] = df['order_time'].dt.date

4. Outlier Removal

Removed unrealistic delivery times to avoid skewed results.

Code Used:

df = df[df['delivery_time_mins'] <= 180]


This ensures data quality and reliability.

5. Data Quality Checks

Verified no invalid values remain

Confirmed consistent city entries

Ensured all rows follow correct formats

📈 Key Insights (From Clean Dataset)

(Even without visualization, you can mention observations from cleaned data)

Evening hours show higher order frequency

Ratings tend to drop for higher delivery times

Some cities consistently show faster delivery service

Outliers significantly inflated average delivery time before cleaning

▶️ How to Run the Project

Install required packages:

pip install pandas numpy


Open the notebook:
Food_Delivery_Analysis.ipynb

Run cells in order to reproduce cleaning steps.

👤 Author

Masilamani D
Aspiring Data Analyst
