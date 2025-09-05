# Project-1-GTC
# 🏨 Hotel Booking Analysis

## 📌 Overview
This is a **training project** done as part of the **GTC AI/ML Training Program**.  
The goal was to practice **data cleaning, exploratory data analysis (EDA), outlier detection, and feature engineering** on the Hotel Booking Demand dataset.

## 📂 Dataset
- **Source**: Provided by **GTC Training**. 
- **Rows**: ~119,390  
- **Columns**: 32 features (numerical & categorical)  
- **Target Variable**: `is_canceled` (1 = booking canceled, 0 = not canceled)

## 🛠️ Steps Done
1. **Data Cleaning**
   - Removed columns with excessive missing values (e.g., `company`).
   - Handled missing values in `children`, `country`, and `agent`.
   - Removed/handled outliers in `adr`, `children`, and `babies`.

2. **Exploratory Data Analysis (EDA)**
   - Checked distributions of numerical & categorical variables.
   - Visualized booking trends by hotel type & month.
   - Analyzed cancellation patterns.
   - Outlier detection using **IQR & Boxplots**.

3. **Feature Engineering**
   - Created `total_guests = adults + children + babies`.
   - Added `is_family` flag (1 if booking includes children/babies).

## 📊 Visualizations
- Distribution of ADR (Average Daily Rate).
- Cancellation rate vs. confirmed bookings.
- Hotel type distribution.
- Monthly booking trends.
- Boxplots for outlier detection.

## 🚀 Next Steps
- Encode categorical variables (Label Encoding / Frequency Encoding).
- Perform correlation analysis.
- Build predictive models to forecast cancellations.

## 🖥️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 👩‍💻 Author
- **Maryam Ahmed**  
- 📧 maryamahmedadel365@gmail.com  

