**Data-Analysis-Project**

Analyzed food delivery data using Python to study delivery times, customer ratings, and city-wise performance. Cleaned data, removed outliers, extracted time features, and created insights on peak hours, delivery speed, and rating patterns to understand and improve delivery efficiency.

**📌 Project Overview**

This project analyzes food delivery performance and customer satisfaction across different cities.
The goal is to understand:

• Delivery time patterns

• City-wise performance

• Rating distribution

• Peak order hours

• Relationship between speed & customer ratings

• Impact of outliers on insights


**🛠️ Tools & Technologies**

• Python

• Pandas

• NumPy

• Matplotlib / Seaborn

• Google Colab

**📁 Dataset Used**

The dataset includes:

• Order time

• City

• Delivery time (mins)

• Customer rating

**Delivery partner details**

📊 Key Steps in the Project
**1. Data Cleaning**

Converted order_time to datetime

Extracted new time-based features (hour, date)

Removed outliers:

df = df[df['delivery_time_mins'] <= 180]


Handled missing values and corrected data types

**2. Feature Engineering**

Extracted hour, date, weekday

Created city-level metrics

Calculated average delivery time & rating per city

Prepared datasets for visualization

**3. Exploratory Data Analysis (EDA)**

• Delivery time distribution

• City-wise performance

• Rating distribution

• Peak ordering hours

• Delivery time vs rating relationship

**4. Visualizations Created**

Bar chart: average delivery time by city

Bar chart: city-wise rating comparison

Hour-wise ordering pattern

Scatter plot: delivery time vs rating

Distribution plots for delivery time & ratings

**📈 Insights**

• Some cities consistently deliver faster.

• Faster deliveries receive higher customer ratings.

• Evening hours show peak order volume.

• Removing outliers improves clarity of insights.

**▶️ How to Run the Project**

1. Install Required Libraries
pip install pandas numpy matplotlib seaborn

2. Open the Notebook

Open:

Food_Delivery_Analysis.ipynb

3. Run All Cells

View visualizations

Interpret insights

**👤 Author**

Masilamani D
Aspiring Data Analyst
