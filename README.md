# Uber Ride Analysis — Python Project

## Project Overview
This project performs a complete **Exploratory Data Analysis (EDA)** on 500 Uber rides recorded from **January to May 2024**.
The goal is to analyze ride patterns, revenue trends, customer behavior, and cancellation insights using Python.

---

## 📊 Dataset Information
| Feature | Details |
|---|---|
| Total Rides | 500 |
| Time Period | January 2024 – May 2024 |
| Total Columns | 18 |
| Missing Values | None |
| Duplicates | None |

**Key Columns:** `trip_date`, `pickup_hour`, `day_of_week`, `city`, `ride_type`, `weather`, `traffic_level`, `distance_km`, `duration_min`, `surge_multiplier`, `fare`, `ride_status`, `payment_method`, `customer_rating`

---

## 🔍 Analysis Performed

### 1. Time Series Analysis
- Daily, Weekly, and Monthly revenue trends
- Revenue by hour of day
- Revenue by day of week (peak vs low days)

### 2. Categorical Analysis
- Revenue and ride count by city
- Most popular ride types
- Cancellation rate by city
- Average customer rating by city and ride type
- Payment method preferences

### 3. Relationship Analysis
- Distance vs Fare (scatter plot)
- Duration vs Fare
- Surge Multiplier vs Fare
- Distance vs Fare per KM (feature engineering)
- Distance vs Fare grouped by ride type (seaborn)

### 4. Distribution Analysis
- Fare distribution (histogram + KDE plot)
- Duration distribution
- Outlier detection using Boxplots (overall + by ride type)

### 5. Correlation Analysis
- Heatmap of all numerical features

---

## 💡 Key Insights

- **Friday** generates the highest revenue; **Sunday** the lowest — people prefer rides for weekend outings
- **Monthly revenue is stable** (~₹35,000–₹37,000) across Jan–Apr; May appears low because the data only covers 4 days of May
- **Higher distance = higher fare** — a clear positive relationship confirmed via scatter plot
- **Fare per KM decreases** as distance increases — longer rides offer better value per km
- **Surge multiplier** directly impacts fare — late night and high-demand rides cost more
- Most rides are completed successfully with a **low cancellation rate**

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, groupby operations |
| Matplotlib | Line charts, bar charts, scatter plots, histograms, boxplots |
| Seaborn | Advanced charts — heatmap, KDE plot, categorical barplots |
| NumPy | Numerical support |
| Jupyter Notebook | Interactive analysis environment |

---


## 🔗 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kanishk-kumar-808509305)
[![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/analyticswithkanishk)

---

*This is my first Python data analysis project. Feedback and suggestions are always welcome!* 
