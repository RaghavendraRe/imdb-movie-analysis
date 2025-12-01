# 🎬 IMDb Regional Movie Analysis – Full Data Analytics Project

**Tools:** Python (Pandas, Selenium, BeautifulSoup), Power BI, Excel  
**Project Type:** End-to-End Data Analytics • Web Scraping • EDA • Dashboard

---

## 📌 Project Overview

This project analyzes the Indian movie market by scraping IMDb data, cleaning it, performing Exploratory Data Analysis (EDA), and building an interactive Power BI dashboard.

A total of **600+ movies** were collected across Indian languages (Hindi, Tamil, Telugu, Malayalam, Kannada).  
The analysis focuses on:

- Ratings  
- Revenue  
- Genres  
- Runtime  
- Top actors  
- Production companies  

---

## 🔍 Key Insights

- ⭐ **Malayalam films** have the highest average ratings  
- 💰 **Hindi movies** lead in gross worldwide revenue  
- 📈 Audience votes show a **positive correlation** with revenue  
- 🎭 **Sport & Biography** genres earn the highest revenue  
- 🎥 Telugu & Tamil films have **longer runtimes**  
- 🎬 UTV Motion Pictures & Yash Raj Films **dominate production revenue**

---

## 🛠️ Project Workflow

### 1️⃣ Web Scraping (Python + Selenium + BeautifulSoup)
**File:** `Notebooks/testing.ipynb`

- Scraped 600+ Indian movie records from IMDb  
- Extracted: title, year, runtime, rating, votes, revenue, language, genre  
- Automated multi-page scraping using Selenium  

---

### 2️⃣ Data Cleaning & Transformation
**File:** `Notebooks/datacleaning.ipynb`

- Cleaned revenue, votes, runtime, and genre columns  
- Removed duplicates & fixed missing values  
- Standardized language/genre fields  
- Final cleaned dataset saved as: `datasets/imdb01cleaned.csv`

---

### 3️⃣ Exploratory Data Analysis (EDA)
**File:** `Notebooks/EDAIMDB.ipynb`

Performed in-depth EDA:

- Rating distribution  
- Genre vs revenue  
- Language-wise performance  
- Top actors  
- Top production companies  
- Votes ↔ revenue correlation  
- Visualizations (Matplotlib & Seaborn)

---

### 4️⃣ Power BI Dashboard
**Folder:** `Power BI Dashboards/`

Includes PNG previews:

- `overview dashboard.png`
- `Success Factor Analysis.png`
- `genre and content analysis.png`
- `directors.png`

#### Dashboard Highlights
- KPIs (Total Movies, Avg Rating)  
- Rating vs Revenue trend  
- Votes vs Revenue trend  
- Genre-wise insights  
- Director revenue word cloud  
- Filters, drilldowns, slicers  

---

## 🚀 Tech Stack Used

- **Python**  
- Pandas, NumPy  
- Selenium  
- BeautifulSoup  
- Matplotlib / Seaborn  
- **Power BI**  
- DAX  
- Excel  
- Data Modeling  
- ETL Concepts  

---

# 📁 Repository Structure


📦 IMDb-Regional-Movie-Analysis

├── 📁 Notebooks
│ ├── EDAIMDB.ipynb
│ ├── datacleaning.ipynb
│ └── testing.ipynb

├── 📁 Power BI Dashboards
│ ├── overview dashboard.png
│ ├── Success Factor Analysis.png
│ ├── genre and content analysis.png
│ └── directors.png

├── 📁 datasets
│ └── imdb01cleaned.csv

└── README.md


---

# ▶️ Dashboard Demo (YouTube Video)

📽️ **Watch here:** https://youtu.be/rYgmKZyrnUA




