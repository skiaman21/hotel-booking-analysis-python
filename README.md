# 🏨 Hotel Booking Analysis using Python

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on hotel booking data using Python. The analysis focuses on understanding booking patterns, cancellation behavior, hotel performance, Average Daily Rate (ADR), market segments, and customer reservation trends.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** for data cleaning, analysis, and visualization.

---

## 🎯 Objectives

* Analyze hotel reservation and cancellation patterns.
* Compare **City Hotel** and **Resort Hotel** performance.
* Analyze **Average Daily Rate (ADR)** trends.
* Identify monthly reservation and cancellation patterns.
* Find the countries with the highest number of cancelled reservations.
* Analyze different market segments.
* Generate visual insights from the hotel booking dataset.

---

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

---

## 📂 Dataset

The project uses a hotel booking dataset containing information about hotel reservations, including:

* Hotel type
* Reservation status
* Reservation status date
* Arrival and booking information
* Average Daily Rate (ADR)
* Country
* Market segment
* Cancellation status

---

## 🔍 Data Cleaning

The following preprocessing steps were performed:

* Converted `reservation_status_date` into a datetime format.
* Checked the dataset structure, columns, and data types.
* Identified missing values.
* Removed the `company` and `agent` columns.
* Removed remaining missing values.
* Removed records with unusually high ADR values (`adr >= 5000`).

---

## 📊 Analysis & Visualizations

### 1. Reservation Status

Analyzed the overall proportion of **cancelled and non-cancelled reservations** to understand the booking cancellation pattern.

### 2. Reservation Status by Hotel Type

Compared cancellation patterns between:

* City Hotel
* Resort Hotel

This helps identify which type of hotel experiences a higher proportion of cancellations.

### 3. Average Daily Rate (ADR)

Analyzed the average daily rate over time and compared ADR trends between City Hotels and Resort Hotels.

### 4. Monthly Reservation Status

Analyzed reservation cancellations across different months to identify seasonal patterns in hotel bookings.

### 5. ADR per Month

Examined monthly ADR patterns for cancelled reservations to understand how pricing varies throughout the year.

### 6. Countries with the Highest Cancellations

Identified the **top 10 countries** based on the number of cancelled reservations.

### 7. Market Segment Analysis

Analyzed the distribution of reservations across different market segments and examined cancellation patterns within these segments.

### 8. ADR: Cancelled vs Not Cancelled

Compared the average daily rate of cancelled and non-cancelled reservations over time to identify differences in pricing patterns.

---

## 📈 Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Handling Missing Values
* Datetime Analysis
* GroupBy & Aggregation
* Data Filtering
* Statistical Analysis
* Data Visualization
* Business Insight Generation

---

## 📁 Project Structure

```text
hotel-booking-analysis-python/
│
├── Hotel Booking Analysis.ipynb
├── hotel_bookings 2.csv
└── README.md
```

---

## 🚀 Future Scope

* Build a dashboard using **Power BI** or **Tableau**.
* Develop a machine learning model to predict booking cancellations.
* Perform deeper customer and market-segment analysis.
* Analyze factors influencing hotel pricing and cancellations.

---

## 👨‍💻 Author

**Aman Singh Rawat**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

---

⭐ If you find this project useful, consider giving the repository a star!
