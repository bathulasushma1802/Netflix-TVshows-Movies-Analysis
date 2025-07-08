🎬 Netflix Movies & TV Shows Analysis and Dashboard (Python + Power BI)

An end-to-end data analysis project using **Python** for data cleaning and **Power BI** for creating an interactive dashboard. Based on the [Netflix Movies and TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows), this project showcases data cleaning, transformation, and business storytelling.

---

## 🧰 Tools & Technologies Used

- 🐍 Python (Pandas, NumPy)
- 📓 Jupyter Notebook
- 📊 Power BI (DAX, Slicers, KPIs, Cards)
- 🧹 Excel (optional visualization testing)

---

## 📁 Project Structure

<pre> ```Netflix-TVshows-Movies-Analysis/
├── data/
│ ├── Netflix_original_Data.csv
│ └── Netflix_cleaned_Data.csv
├── analysis/
│ └── Netflix_Project.ipynb
├── dashboard/
│ ├── Netflix Project power bi.pbix
│ └── Netflix Shows_Dashboard.pdf
└── README.md ``` </pre>

---

## 🔬 Python Analysis

📄 [`Netflix_Project.ipynb`]( Netflix_Project.ipynb)

Key operations performed:

- Removed invalid or misaligned rows (e.g., wrong `show_id`)
- Extracted:
  - `main_genre` from `listed_in`
  - `duration_value` and `duration_type` from `duration`
- Fixed `rating` issues (e.g., replaced `64 min` and few others with `Not Rated`)
- Handled null `date_added` and `year_added`
- Cleaned and exported the final dataset for Power BI

---

## 📊 Power BI Dashboard

📁 [`Netflix Project power bi.pbix`](Netflix Project power bi.pbix)  
📄 [`Netflix Shows_Dashboard.pdf`](Netflix Shows_Dashboard.pdf)

### Dashboard Features:

- ✅ KPI Cards: Total Movies, TV Shows, Average Duration
- 📅 Trend: Content Added Per Year
- 🎭 Top 10 Genres
- 🌍 Country-wise Content Distribution
- 🔞 Rating-wise Breakdown
- ⏱️ Average Duration by Genre
- 🔍 Interactive Filters: Type, Genre, Country, Rating, Year

---

## 📦 Dataset Source

- [Netflix Movies and TV Shows Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---


## 🙋‍♀️ Created By

**Sushma Bathula**  
🎓 B.Tech, NIT Calicut | Aspiring Data Analyst  
📫 [LinkedIn Profile](https://www.linkedin.com/in/sushma-bathula/)

---

## ⭐ If you found this project helpful...

Give it a ⭐ star and connect with me on LinkedIn!
