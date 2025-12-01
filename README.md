🎬 IMDb Regional Movie Analysis – Full Data Analytics Project

Tools: Python (Pandas, Selenium, BeautifulSoup), Power BI, Excel
Duration: Mar 2025 – Apr 2025
Project Type: End-to-End Data Analytics • Web Scraping • EDA • Power BI Dashboard

📌 Project Overview

This project analyzes the Indian movie market by scraping data from IMDb, cleaning and transforming it, performing EDA, and visualizing insights using an interactive Power BI dashboard.

A total of 600+ movies were collected across multiple Indian languages (Hindi, Tamil, Telugu, Malayalam, Kannada).
The analysis focuses on ratings, revenue, genres, runtime, top actors, and production companies.

🔍 Key Insights

⭐ Malayalam films have the highest average ratings

💰 Hindi movies lead in gross worldwide revenue

📈 Audience votes show a positive correlation with revenue

🎭 Sport and Biography genres earn the highest revenue

🎥 Telugu & Tamil movies have longer runtimes

🎬 UTV Motion Pictures & Yash Raj Films dominate production revenue

🛠️ Project Workflow
1️⃣ Web Scraping (Python + Selenium + BeautifulSoup)

File: Notebooks/testing.ipynb

Scraped 600+ movie records from IMDb

Extracted: title, year, runtime, rating, votes, revenue, language, genre

Automated multi-page scraping with Selenium

2️⃣ Data Cleaning & Transformation

File: Notebooks/datacleaning.ipynb

Cleaned messy columns (revenue, votes, runtime, genre)

Removed duplicates

Standardized language/genre labels

Fixed missing values

Final dataset saved as → datasets/imdb01cleaned.csv

3️⃣ Exploratory Data Analysis (EDA)

File: Notebooks/EDAIMDB.ipynb

Rating distribution analysis

Genre-wise revenue patterns

Language-wise performance

Top actors & production companies

Correlation (votes ↔ revenue)

Visualizations with Matplotlib/Seaborn

4️⃣ Power BI Dashboard

Folder: Power BI Dashboards/

Includes PNG previews:

overview dashboard.png

Success Factor Analysis.png

genre and content analysis.png

directors.png

Dashboard features:

KPIs (Total Movies, Avg Rating)

Rating vs Revenue

Votes vs Revenue Trend

Genre Performance

Director Revenue Word Cloud

Language Comparisons

Drilldowns & Filters

🚀 Tech Stack Used
Python

Pandas

NumPy

Selenium

BeautifulSoup

Matplotlib / Seaborn

Power BI

Data Modeling

DAX

Interactive Visuals

Filters & Drilldowns

Excel

Pre-processing support

Data validation

📁 Repository Structure
📦 IMDb-Regional-Movie-Analysis
│
├── 📁 Notebooks
│    ├── EDAIMDB.ipynb
│    ├── datacleaning.ipynb
│    └── testing.ipynb
│
├── 📁 Power BI Dashboards
│    ├── overview dashboard.png
│    ├── Success Factor Analysis.png
│    ├── genre and content analysis.png
│    └── directors.png
│
├── 📁 datasets
│    └── imdb01cleaned.csv
│
└── README.md

▶️ Dashboard Demo (YouTube Video)

📽️ Watch here: https://youtu.be/rYgmKZyrnUA
