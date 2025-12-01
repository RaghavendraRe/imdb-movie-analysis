🎬 IMDb Regional Movie Analysis – Full Data Analytics Project

Tools: Python (Pandas, Selenium, BeautifulSoup), Power BI, Excel
Duration: Mar 2025 – Apr 2025
Project Type: End-to-End Data Analytics + Web Scraping + EDA + Dashboard

📌 Project Overview

This project analyzes the Indian movie market by scraping data from IMDb, cleaning and transforming it, performing EDA, and visualizing insights using an interactive Power BI dashboard.

I collected 600+ movie records across multiple Indian languages (Hindi, Tamil, Telugu, Malayalam, Kannada) and analyzed trends in ratings, revenue, genres, runtime, and star performance.

The final dashboard reveals key market insights such as:
✔ Malayalam films having the highest average ratings
✔ Hindi movies leading in gross worldwide revenue
✔ Strong link between votes & box office performance
✔ Genre-wise trends in revenue and movie popularity

🛠️ Project Workflow
1️⃣ Web Scraping (Python + Selenium + BeautifulSoup)

File: Notebooks/testing.ipynb

Scraped 600+ movie records from IMDb

Extracted title, year, runtime, rating, votes, revenue, language, genre

Automated multi-page scraping using Selenium

2️⃣ Data Cleaning & Transformation

File: Notebooks/datacleaning.ipynb

Cleaned messy fields (revenue, votes, runtime, genres)

Removed duplicates

Standardized language & genre labels

Fixed missing values

Saved final cleaned dataset: datasets/imdb01cleaned.csv

3️⃣ Exploratory Data Analysis (EDA)

File: Notebooks/EDAlMDB.ipynb

Examined rating distribution

Genre vs gross revenue analysis

Language-wise movie performance

Top production companies

Top 10 actors by ratings

Correlation between audience votes and revenue

4️⃣ Power BI Dashboard

Folder: Power BI Dashboards/
Includes PNG previews of the dashboard pages:
📊 overview dashboard.png
📊 Success Factor Analysis.png
📊 genre and content analysis.png
📊 directors.png

Dashboard features:

Overview metrics (total movies, avg rating)

Rating vs revenue visualization

Votes vs revenue correlation

Genre-wise performance

Director-wise total revenue

Language-wise comparisons

🎯 Key Insights

Malayalam movies hold the highest avg rating (7.47)

Hindi movies dominate in box office revenue

Sport & Biography genres generate the highest revenue

Telugu/Tamil movies have longer runtimes

Production companies like UTV Motion Pictures & Yash Raj Films lead in revenue

🚀 Tech Stack Used
Python

Pandas

NumPy

Selenium

BeautifulSoup

Matplotlib / Seaborn

Power BI

DAX

Data Modeling

Interactive Visuals

Filters & Drilldowns

Excel

Supporting data validation & cleanup

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
│    ├── Sucess Factor Analysis.png
│    ├── genre and content analysis.png
│    └── directors.png
│
├── 📁 datasets
│    └── imdb01cleaned.csv
│
└── README.md

▶️ Dashboard Demo (YouTube Video)

https://youtu.be/rYgmKZyrnUA
