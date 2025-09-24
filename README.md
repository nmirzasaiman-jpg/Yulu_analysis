# 🚴‍♂️ Yulu Case Study — Analysis & Business Insights

---

## 📌 Project Overview

This project analyzes **bike rental patterns for Yulu** to uncover how demand varies across weekdays, weekends, weather conditions, and seasons. Using **EDA** and **statistical hypothesis testing**, we identify the primary demand drivers and propose **data-driven strategies** for operations, marketing, and pricing.

---

## 📂 Notebook Source

* `Yulu_casestudy2.ipynb`

---

## 🎯 Problem Statement

To understand the **factors influencing Yulu’s bike rental demand** and design strategies for:

* ⚙️ Fleet management
* 💰 Pricing optimization
* 📣 Customer engagement

---

## 🔎 Data Analysis Workflow

### 1. Data Import & Structure

* Explored dataset using `.shape`, `.info()`, `.describe()`

### 2. Data Cleaning

* Missing values → handled via `.isnull()`, `.fillna()`
* Duplicates → checked with `.duplicated()`
* Outliers → treated via Boxplots & IQR

### 3. Exploratory Data Analysis (EDA)

* **Numerical Variables** → Histograms, Distplots
* **Categorical Variables** → Countplots, Pie charts
* **Relationships** → Correlation heatmap

### 4. Hypothesis Testing

* ✅ **Weekday vs Weekend demand** → 2-Sample T-test
* ✅ **Demand across Weather** → One-way ANOVA
* ✅ **Demand across Seasons** → One-way ANOVA
* ✅ **Season vs Weather dependency** → Chi-square test

---

## 📊 Key Findings

1. **📅 Weekday vs Weekend** → No significant difference. Demand is stable throughout the week.
2. **🌦️ Weather Impact** → Rentals drop sharply in adverse weather (rain, snow).
3. **🍂 Seasonal Demand** → Higher in summer & fall, lower in winter.
4. **⛅ Season–Weather Link** → Strong dependency → forecasting must include both.

---

## 💡 Business Recommendations

### 1. 🚲 Bike Allocation & Maintenance

* Maintain **consistent fleet size** on weekdays & weekends.
* Use rainy/winter months for **bike servicing & maintenance**.

### 2. 💰 Dynamic Pricing

* Discounts during **low-demand weather/seasons**.
* Surge pricing in **peak seasons (summer/fall)**.

### 3. 📣 Marketing & Promotions

* Seasonal campaigns → *“Summer Fitness Rides”*, *“Autumn Scenic Tours”*.
* Bundle offers with **cafes/parks** in high-demand periods.

### 4. ⚙️ Operational Planning

* Align fleet deployment with **weather forecasts**.
* Extra bikes for **sunny weekends**.

### 5. 😀 Customer Experience

* Offer **weather-friendly gear** (ponchos, helmets).
* Launch **loyalty/membership programs** to retain riders.

---

## 🛠️ How to Run

1. Install required Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`
2. Open `Yulu_casestudy2.ipynb` in JupyterLab/Notebook
3. Run cells sequentially

---

## ⚡ Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scipy
* statsmodels

---

## ✅ Conclusion

Yulu’s **demand is steady across weekdays/weekends** but highly **sensitive to weather and seasonality**. By adapting **operations, pricing, and promotions** to these patterns, Yulu can:

* 🚴 Improve fleet utilization
* 💹 Boost revenue
* 😀 Enhance customer satisfaction

---


