# 🎬 Cinematic Trends: Exploring Movie Metadata and Viewer Preferences

![Power BI](https://img.shields.io/badge/Visualization-PowerBI-yellow?style=for-the-badge&logo=powerbi)
![Python](https://img.shields.io/badge/Preprocessing-Python-blue?style=for-the-badge&logo=python)
![Kaggle](https://img.shields.io/badge/Data-Kaggle-lightgrey?style=for-the-badge&logo=kaggle)
![HTML](https://img.shields.io/badge/Website-HTML5-orange?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/Interactive-JavaScript-yellowgreen?style=for-the-badge&logo=javascript)

---

## 📌 Overview

This project aims to uncover what makes a movie successful by analyzing metadata and viewer ratings from the **TMDB (The Movie Database)** datasets. Using **Power BI** and a **custom-built website**, we explore trends in genres, budgets, revenues, languages, and viewer preferences.

---

### 🎯 Goal

- Viewer sentiment across genres  
- Budget vs. revenue performance  
- Popularity trends over time  
- Language-based film analysis  
- Production company revenue efficiency  
- Deploy an interactive website for exploration

---



## 🗃️ Dataset Details

**Source:** [TMDB Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

- `movies_metadata.csv`: Movie details like title, genre, release date, budget, revenue, language, runtime, etc.  
- `ratings.csv`: Over 100,000 user ratings including user ID, movie ID, rating score, and timestamp  
- `movies_data.csv`: Final merged dataset created for Phase 2

---

## 🛠️ Tools & Technologies

| Phase        | Tools Used                                                                 |
|--------------|-----------------------------------------------------------------------------|
| Phase 1      | Python (Pandas, NumPy), Google Colab, Power BI, DAX, JSON Parsing          |
| Phase 2      | HTML, CSS, JavaScript, D3.js, Plotly.js, Power BI Embed, GitHub Pages      |

---

## ⚙️ Workflow

### Phase 1
mermaid
graph TD;
    A[Collect Data from Kaggle] --> B[Clean & Transform Data using Python];
    B --> C[Feature Engineering (Profit, ROI, Genre, etc)];
    C --> D[Export Clean Data to Power BI];
    D --> E[Create Dashboards & Visualizations];



Phase -2

graph TD;
    F[Merge Datasets (metadata + ratings)] --> G[Build Interactive Visualizations using JS];
    G --> H[Design Website with HTML & CSS];
    H --> I[Embed Power BI & D3 Charts];
    I --> J[Deploy on GitHub Pages];

Live Website

🎯 Interactive Dashboard Website:
https://sashi789.github.io/SDV_project
Explore the dashboards, filter visualizations by genre/language, and dive into interactive movie trends.


Interactive Dashboard Website:
[https://sashi789.github.io/SDV_project](https://sashi789.github.io/SDV_project/pages/team.html)

Explore the dashboards, filter visualizations by genre/language, and dive into interactive movie trends.

Visualizations Showcase

📊 Revenue vs Budget (Scatter)
⭐ Genre Ratings (Bar)
📈 Trending Popularity (Line)
🔄 Vote Count vs Rating (Bubble)
🌍 Movies by Language (Donut)
🏢 Top Production Companies (Combo)
🔥 Genre-Language Heatmap
🧮 Rating Distribution (Binned)
🧠 D3.js-based Interactive Rating Spread

This project is for educational purposes only.
TMDB data used under Creative Commons Attribution-NonCommercial 4.0.

Thank you 

