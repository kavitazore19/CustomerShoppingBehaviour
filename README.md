# 🛍️ Customer Shopping Behaviour Analysis

## 📌 Project Overview

**Customer Shopping Behaviour Analysis** is a data analytics project that focuses on understanding customer purchasing patterns, preferences, and shopping trends using **Python, SQL, and Power BI**.

The project follows an end-to-end data analysis workflow, starting from data cleaning and exploratory analysis in Python, followed by business-oriented analysis using SQL and finally presenting insights through an interactive Power BI dashboard.

---

## 🎯 Objectives

* Analyze customer shopping and purchasing behaviour.
* Identify trends and patterns in customer purchases.
* Understand customer preferences and spending behaviour.
* Perform business-oriented analysis using SQL.
* Create an interactive dashboard using Power BI.
* Generate meaningful insights that can support business decision-making.

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                                    |
| -------------- | ---------------------------------------------------------- |
| **Python**     | Data cleaning, preprocessing and exploratory data analysis |
| **Pandas**     | Data manipulation and analysis                             |
| **SQL**        | Business queries and customer behaviour analysis           |
| **MySQL**      | Database for storing the cleaned customer data             |
| **Power BI**   | Interactive dashboard and data visualization               |

---

## 📊 Dataset

The dataset contains information about **3,900 customers** with **18 original columns** related to customer shopping behaviour.

The data includes information that can be used to analyze areas such as:

* Customer demographics
* Purchase behaviour
* Purchase frequency
* Ratings
* Discounts
* Promotional offers
* Shopping preferences
* Customer spending patterns

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Insights & Business Understanding
```

---

## 🐍 Python Analysis

Python was used for data cleaning, preprocessing, and exploratory analysis.

### Main tasks performed:

* Loaded the dataset using Pandas.
* Checked the structure and data types.
* Handled missing values.
* Standardized column names.
* Created new analytical features.
* Removed redundant columns.
* Performed exploratory data analysis.

### Data preprocessing examples:

* **37 missing Review Rating values** were filled using the **category-wise median**.
* Created an **Age Group** feature.
* Created a **Purchase Frequency (Days)** feature.
* Removed the redundant `promo_code_used` column because it contained information matching `discount_applied`.

---

## 🗄️ SQL Analysis

After cleaning the data, it was loaded into a **PostgreSQL** database.

The cleaned data was stored in the:

```text
customer_behavior
```

database, using the:

```text
customer
```

table.

SQL was then used to perform business-oriented analysis and answer questions related to customer behaviour, purchases, preferences, and trends.

---

## 📈 Power BI Dashboard

Power BI was used to create an interactive dashboard for visualizing the analyzed customer shopping data.

The dashboard helps understand:

* Customer behaviour
* Purchase trends
* Customer preferences
* Spending patterns
* Ratings
* Promotional and discount-related behaviour

The dashboard provides an easy-to-understand visual representation of the analysis.

---

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning using Python
* Data preprocessing using Pandas
* Exploratory Data Analysis
* SQL querying and business analysis
* PostgreSQL database handling
* Data visualization using Power BI
* Converting raw data into meaningful insights
* Presenting analytical findings

---

## 📁 Project Structure

```text
Customer-Shopping-Behaviour/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

> The folder names can be adjusted according to the actual files in the repository.

---

## 🚀 Project Highlights

* **3,900 customer records** analyzed.
* Data cleaning and preprocessing performed using **Python/Pandas**.
* Missing values handled using a suitable statistical approach.
* New features created to improve analysis.
* Cleaned data stored in **PostgreSQL**.
* Business analysis performed using **SQL**.
* Interactive visualizations created using **Power BI**.
* Complete project documentation and presentation prepared.

---

## 👩‍💻 Author

**Kavita Zore**

M.Sc. Industrial Mathematics with Computer Applications (IMCA)
Fergusson College, Pune

### Skills Demonstrated

`Python` • `Pandas` • `SQL` • `PostgreSQL` • `Power BI` • `Data Analysis` • `Data Visualization`

---

## ⭐ Project Summary

This project demonstrates an end-to-end approach to **customer shopping behaviour analysis**, combining Python for data preparation, SQL for business analysis, and Power BI for interactive visualization.
