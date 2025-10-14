# 🚗 Car Dataset Analysis – Fuel, Performance & Market Insights

This project explores the car dataset to uncover relationships between vehicle specifications, fuel efficiency, pricing, and market segmentation. It combines data cleaning, feature engineering, and visual analytics to deliver actionable insights.

---

## 🔍 Objective

To analyze how vehicle attributes like horsepower, drivetrain, transmission type, and size influence MSRP and fuel efficiency, and to identify patterns that reflect consumer targeting and performance trade-offs.

---

## 📁 Files

- [`Project_Car_Dataset.ipynb`](https://github.com/reharabi/Car-Dataset-Analysis/blob/main/Project_Car_Dataset.ipynb) – Main Colab notebook  
- [`data (2).csv`](https://github.com/reharabi/Car-Dataset-Analysis/blob/main/data%20(2).csv) – Original dataset


---

## 🧪 Workflow Summary

### 1. Data Cleaning
- Handled missing values with median imputation and placeholder text
- Filtered vehicles from 1995 onward
- Standardized string formatting and removed duplicates

### 2. Feature Engineering
- Created `Total MPG` (average of city and highway MPG)
- Created `Price per HP` (MSRP divided by Engine HP)

### 3. Exploratory Data Analysis
- Descriptive statistics for key numeric columns
- Grouped MSRP and Popularity by Driven Wheels, Vehicle Size, and Engine Cylinders
- Visualizations:
  - Histogram of city MPG
  - Bar chart of MSRP by Vehicle Size
  - Scatter plot of Engine HP vs MSRP
  - Boxplot of MSRP by Driven Wheels
  - Line plot of MPG trends by Transmission Type
  - Correlation heatmap

---

## 📊 Key Visual Insights

### 🔹 Engine HP vs MSRP
- Strong positive correlation: more powerful engines cost more
- Dominant market for standard-performance, budget-friendly models

### 🔹 MSRP by Driven Wheels
- Rear-wheel drive vehicles have the highest MSRP
- Front-wheel drive vehicles are the most affordable
- Clear pricing hierarchy based on drivetrain type

### 🔹 Transmission Type & Fuel Efficiency
- Direct-drive (likely electric) vehicles show superior MPG
- Conventional transmissions have similar MPG across types
- Highway MPG consistently exceeds city MPG

### 🔹 Correlation Matrix
- Engine HP & MSRP: strong positive correlation
- City MPG & Highway MPG: very strong positive correlation
- MSRP & MPG: weak negative correlation
- Popularity: no meaningful correlation with other variables

---

## 🧠 Strategic Insights

- **Fuel Efficiency Distribution**: Most vehicles achieve 15–30 city MPG, with few exceeding 30
- **Performance vs Cost Trade-off**: Higher horsepower and premium drivetrains increase MSRP but reduce fuel efficiency
- **Electric Advantage**: Direct-drive vehicles outperform others in MPG, reinforcing the shift toward electrification
- **Market Segmentation**: Vehicle size, drivetrain, and transmission type are strong indicators of pricing tiers and consumer targeting

---

## 🛠 Tools Used

- Python (pandas, numpy)
- Visualization: seaborn, matplotlib
- Environment: Google Colab

---

## 📬 Author

Created by **Reha Rabi**  
For questions or collaboration, feel free to connect via GitHub or LinkedIn.

