# Tracking User Engagement (SQL + Python)

![Last Commit](https://img.shields.io/badge/Last%20Commit-Active-blue)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![SQL](https://img.shields.io/badge/SQL-Queries-005CDB?logo=sqlite)
![Pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/numpy-Scientific%20Computing-013243?logo=numpy)

> *(Extra badges you requested)*  
![npx](https://img.shields.io/badge/npx-Build%20Tool-black?logo=npm)
![mongoose](https://img.shields.io/badge/Mongoose-ODM-7A1F5A?logo=mongoose)

---

## 📌 Project Overview

This project analyzes **user engagement patterns** using a combination of **SQL** for data extraction and **Python/Jupyter Notebook** for data cleaning, visualization, and insights.

The goal is to understand how user activity changed across different periods and to generate metrics that help evaluate user growth, retention, and overall platform engagement.

The analysis focuses on:
- Minutes watched per user  
- Distribution differences between cohorts  
- Outlier removal for more accurate trends  
- Hypothesis evaluation (engagement growth)  
- Visual insights and comparisons  

This repository works as a **mini data analytics pipeline** that converts raw SQL exports into meaningful, visual insights.

---

## 🚀 Features

- 🔄 **Data Cleaning & Transformation**  
  Process raw engagement logs into clean datasets using Pandas.

- 📊 **Trend & Distribution Analysis**  
  Visualize how user engagement changed across time.

- 🧹 **Outlier Handling**  
  Uses the 99th percentile rule to remove extreme values.

- 📈 **Metric Comparison**  
  Compare 2021 vs 2022 or any two datasets.

- ⚙️ **SQL Integration**  
  Queries written to extract the correct engagement metrics.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Data manipulation & visualizations |
| **Jupyter Notebook** | Interactive analysis |
| **SQL** | Raw data extraction |
| **Pandas** | Data wrangling |
| **Matplotlib** | Visual plots |
| *(Optional)* **npx / mongoose** | Badges added as per request |

---

## 📂 Folder Structure

Tracking-User-Engagement-SQL-Python │ ├── data/                 # CSV files extracted from SQL ├── notebooks/            # Jupyter notebooks for the analysis ├── sql/                  # SQL scripts used for data extraction ├── images/               # Plots & screenshots (add your own) ├── README.md └── requirements.txt

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/Akash5704/Tracking-User-Engagement-SQL-Python.git
cd Tracking-User-Engagement-SQL-Python

Create a virtual environment:

python -m venv .venv
source .venv/bin/activate  # macOS/Linux
.venv\Scripts\activate     # Windows

Install dependencies:

pip install -r requirements.txt

If you don't have requirements.txt, install manually:

pip install pandas numpy matplotlib jupyterlab seaborn


---

▶️ How to Run the Project

Launch Jupyter Notebook:

jupyter notebook

OR (recommended)

jupyter lab

Open the notebook:

/notebooks/engagement_analysis.ipynb

Run all the cells to:

Load raw data

Clean and process datasets

Remove outliers

Plot engagement graphs

Compare 2021 vs 2022

View final insights



---

🧪 Testing

If you include test scripts in future, you can run:

pytest

For now, there are no test dependencies.


---

📸 Screenshots (Replace with your real images)

![Analysis Preview](./images/preview.png)

You can add any Python plot screenshots.


---

📈 Key Insights (from your notebook work)

Engagement increased significantly in Q2 2022 compared to Q2 2021.

After outlier removal, averages became more realistic and normalized.

Distribution plots revealed heavy-tailed behaviour.

Hypothesis validation suggests that user engagement did improve, confirming platform growth.



---

🤝 Contributing

1. Fork this repository


2. Create a branch


3. Commit changes


4. Submit a pull request




---

📄 License

This project is licensed under the MIT License.


---

📬 Contact

If you want help improving your analysis, adding charts, or making the README even better, feel free to reach out.

---

