# 👋 Sridhar Parshana | Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sridharparshana)  
📧 **Email**: parshanasridhar@gmail.com  
📱 **Mobile**: +91 7288075492  

---

## 📊 About Me

I’m a **Data Analyst** with over **3 years of experience** in solving real-world business problems using **Power BI**, **Python**, **MySQL**, and **Advanced Excel**. I specialize in **data modeling**, **data visualization**, and **report automation**. I’m passionate about transforming data into insights that drive performance and profitability.

---

## 🚀 Skills & Expertise

**Languages**: SQL, Python, DAX  
**Databases**: MySQL (Joins, Procedures, Triggers, CTEs, Window Functions)  
**Visualization**: Power BI (Dashboards, Reports, DAX, Power Query)  
**Python Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
**Statistics**: Hypothesis Testing, Regression, Probability, Predictive Modeling  
**Tools**: ZOHO Books, Excel (Pivot, T-tests, Correlation, Data Validation)  

---

## 🧰 Tools in My Toolbox

- 💻 **Power BI**: ETL, Gateway, Refresh Schedules, Fabric Warehouse Integration  
- 🐍 **Python**: Web Scraping, Data Analysis, Predictive Modeling  
- 📈 **Excel**: Advanced Formulas, Forecasting, Statistical Analysis  

---

## 💼 Experience Snapshot

### 🏢 **Nova Web Innovations Pvt Ltd**  
📅 _Feb 2023 – Present_  
**Data Analyst**  
- Automated sales & stock reports across Amazon, Walmart, Shopify — increased productivity by 25%  
- Designed regional demand prediction models — resulted in 20% sales growth  
- Developed real-time Power BI dashboards for stock & order flow tracking  
- Conducted seasonal & customer-based segmentation to guide marketing and procurement  

### 🧑‍💻 **Trainity**  
📅 _Nov 2022 – Feb 2023_  
**Data Analyst Intern**  
- Built SQL-Power BI data pipelines; improved customer analytics and reporting efficiency  

### ⚙️ **Sujata Forge Pvt Ltd**  
📅 _Dec 2021 – Sep 2022_  
**Quality Engineer**  
- Led defect-reduction initiatives through root cause analysis and SPC methods  

---

## 🏆 Certifications

- ✅ **Google Data Analytics Specialization** – Coursera (08/2022)

---

## 🎓 Education

**B.Tech in Mechanical Engineering**  
JNTU Hyderabad (2017 – 2021) | CGPA: **8.0**

---

## 💡 Featured Projects

### 🔹 [📊 Sales Intelligence Dashboard (Power BI)](https://github.com/sridharparshana/BI-reports/blob/myones/Interactive%20Power%20BI%20Project.pdf)
> Built a full-scale Power BI dashboard for 100K+ records  
> ⮕ Regional stock allocation using dynamic DAX formulas  
> ⮕ Product & order movement insights for business decisions

---

### 🔹 [📦 Shopify + ShipStation API Integration](https://github.com/sridharparshana/python_projects/blob/myones/importing%20the%20orders%20using%20API.py)
> 🛠 Python script to import & modify eCommerce orders via API  
> ⮕ Data filtered and transformed for localized database use  
> ⮕ SQL stored procedures attached per entry

---

### 🔹 [🧠 LinkedIn Job Classification (ML Project)](https://github.com/sridharparshana/python_projects/blob/myones/Linkedin_Job_Classification.ipynb)
> 🔍 Analyzed and classified engineering job roles from a large LinkedIn dataset using NLP and ML.  
> ✅ **Open in Colab** ready, Kaggle integrated  
> ✅ Full pipeline: TF-IDF → Label Encoding → Model Training (Logistic, RF, XGBoost, SVM)  
> ✅ EDA visualizations and Feature Importance plots included

```python
# Sample snippet: Data import and exploration
import pandas as pd
df = pd.read_csv('/kaggle/input/linkedin-data-jobs-dataset/clean_jobs.csv')
df['target'] = df['title'].apply(lambda x: 1 if 'engineer' in str(x).lower() else 0)
