# 📊 A/B Testing Analysis for Marketing Campaign

## 🚀 Project Overview
This project analyzes the performance of a **digital marketing A/B testing experiment** to evaluate whether a new advertisement strategy improves user conversion rates.

Using **Python, Pandas, NumPy, SciPy, Matplotlib, and Seaborn**, the project performs **exploratory data analysis (EDA), conversion rate analysis, and statistical hypothesis testing** to determine whether the difference between experiment groups is statistically significant.

This project demonstrates practical **Data Analytics, Experimentation Analysis, and Statistical Testing skills** widely used in **product analytics, marketing analytics, and growth teams**.

---

# 🎯 Business Problem

Companies frequently run **A/B experiments** to test whether a new marketing campaign or product feature improves **user engagement and conversion rates**.

This analysis answers the following questions:

✔ Does the **new advertisement strategy** increase conversion rates?  
✔ Is the difference between **control group and test group statistically significant**?  
✔ What insights can support **data-driven marketing decisions**?

---

# 📂 Dataset Information

The dataset contains **user-level experiment data** from a marketing campaign.

| Column | Description |
|------|-------------|
| user id | Unique identifier for each user |
| test group | Indicates whether the user belongs to **control** or **test** group |
| converted | Boolean value indicating whether the user converted |
| total ads | Total number of advertisements viewed |
| most ads day | Day when the user viewed the most ads |
| most ads hour | Hour when the user viewed the most ads |

📈 **Dataset Size:**  
**588,101 rows** and **6 relevant features**

---

# 🛠️ Technologies Used

### 💻 Programming
- Python

### 📚 Libraries
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

### 📊 Data Analytics Techniques
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Conversion Rate Analysis
- A/B Testing
- Hypothesis Testing
- Statistical Significance Testing
- Data Visualization

---

# ⚙️ Project Workflow

## 1️⃣ Data Cleaning
- Removed unnecessary **Unnamed columns**
- Verified dataset structure
- Checked for missing values
- Ensured correct data types

---

## 2️⃣ Exploratory Data Analysis
Analyzed user behavior and ad exposure patterns including:

- Distribution of ads viewed
- Engagement patterns across users
- Ad exposure by **day and hour**

---

## 3️⃣ Conversion Rate Analysis

Calculated conversion rates for **control vs test group**.

```python
conversion_rate = df.groupby("test_group")["converted"].mean()
print(conversion_rate)
```

---

## 4️⃣ Statistical Hypothesis Testing

Performed **statistical testing** to evaluate whether the difference in conversion rates is significant.

Methods used:

📌 Z-Test for Proportions  
📌 Hypothesis Testing  
📌 Statistical Significance Analysis  

---

## 5️⃣ Data Visualization

Visualized experiment outcomes using:

📊 Conversion rate comparison charts  
📊 Ads exposure distribution plots  
📊 User engagement patterns  

---

# 📈 Key Insights

✔ Compared **conversion performance between control and test groups**  
✔ Evaluated the impact of **advertisement exposure on conversion behavior**  
✔ Identified patterns that support **marketing campaign optimization**  
✔ Demonstrated **data-driven decision making using statistical analysis**

---

# 💡 Skills Demonstrated

This project highlights the following **Data Analyst competencies**:

✔ Data Cleaning & Data Preparation  
✔ Exploratory Data Analysis (EDA)  
✔ Statistical Analysis  
✔ A/B Testing & Experimentation  
✔ Hypothesis Testing  
✔ Conversion Rate Optimization  
✔ Data Visualization  
✔ Business Insight Generation  
✔ Marketing Analytics  

---

# ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/YOUR_USERNAME/ab-testing-marketing-analysis.git
```

### 2️⃣ Navigate to project folder

```
cd ab-testing-marketing-analysis
```

### 3️⃣ Run the analysis script

```
python ab_testing_analysis.py
```

Or open the notebook in **Jupyter Notebook / Google Colab**.

---

# 📁 Project Structure

```
ab-testing-marketing-analysis

data/
    marketing_ab_test.csv

notebooks/
    ab_testing_analysis.ipynb

scripts/
    ab_testing_analysis.py

README.md
```

---

# 🔮 Future Improvements

🚀 Build **Power BI / Tableau dashboard** for experiment visualization  
🚀 Implement **automated A/B testing pipeline**  
🚀 Apply **machine learning models for conversion prediction**  
🚀 Deploy experiment insights into a **business intelligence workflow**

---

# 👩‍💻 Author

**Chinmayee Y**

📊 Data Analyst  
🐍 Python | SQL | Power BI | Tableau | Statistical Analysis | Marketing Analytics

---

⭐ If you found this project helpful, consider **starring the repository!**

