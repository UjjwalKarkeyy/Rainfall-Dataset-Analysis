# 🌧️💻 India is Blessed by Indra!

## 📁 Project: Analyzing Rainfall Trends Using SQL (with some unexpected discoveries!)

I recently dove into a rainfall dataset using **MySQL** — and let me tell you, I’ve never appreciated monsoons this much!

---

### ✅ Main Goals

- Identify which states and districts receive the **most and least rainfall**
- Spot **seasonal variations** (winter, summer, spring, fall)
- Compare months (e.g., is July rainier than June?)
- Detect anomalies and edge cases using:
  - `CASE WHEN`
  - `ROW_NUMBER()`
  - `PARTITION BY`

---

### 📊 Key Findings That Stood Out

- 🌧️ **Uttar Pradesh** recorded the highest total rainfall  
- 🌦️ **Meghalaya** had the highest average rainfall per district  
- 🏞️ **Tamenglong** emerged as the rainiest district  
- 🌵 **Sri Ganganaga, Rajasthan** saw only 3mm of rain in October  
- ⚠️ Over **52 districts** had July rainfall > 600mm  
- 🌪️ **83 districts** had more rain in **Jan–Feb** than in **Oct–Dec**!

---

### 🧹 What I Did in SQL

- Imported the dataset using `LOAD DATA INFILE`
- Cleaned NULL values dynamically via `INFORMATION_SCHEMA`
- Removed duplicates using `ROW_NUMBER() OVER PARTITION BY`
- Ran full EDA using:
  - `GROUP BY`, `SUM()`, `AVG()`
  - `CASE`, `HAVING`, `ORDER BY`

---

### 🧠 Fun Realization While Running the Final Query

> “Turns out SQL doesn’t just **SUM** rainfall — it also **FLOODS your brain with insights**.”

---

### ❓ Your Turn

> If this were your dataset,  
> **what’s one unexpected or creative question you’d ask using SQL?**

👇 Comment below and let’s brainstorm some rainy-day queries!

---

### 👨‍💻 Author

**Ujjwal Karki**  
*Rain-lover turned Data Analyst ☔*
