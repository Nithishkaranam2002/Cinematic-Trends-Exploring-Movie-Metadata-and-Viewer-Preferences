# 🎬 Cinematic Trends: Exploring Movie Metadata and Viewer Preferences

![Power BI](https://img.shields.io/badge/Visualization-PowerBI-yellow?style=for-the-badge&logo=powerbi)
![Python](https://img.shields.io/badge/Preprocessing-Python-blue?style=for-the-badge&logo=python)
![Kaggle](https://img.shields.io/badge/Data-Kaggle-lightgrey?style=for-the-badge&logo=kaggle)

## 📌 Overview

This project aims to uncover what makes a movie successful by analyzing metadata and viewer ratings from the **TMDB (The Movie Database)** datasets. Using interactive Power BI dashboards, we visualize trends in genres, budgets, revenues, languages, and user preferences.

🎯 **Goal:** Deliver insights into:
- Viewer sentiment across genres
- Budget vs. revenue performance
- Popularity trends over time
- Language-based film analysis
- Production company revenue efficiency

---

## 🗃️ Dataset Details

**Source:** [TMDB Movie Dataset on Kaggle](https://www.kaggle.com/datasets)

- `movies_metadata.csv`: Movie details like title, genre, release date, budget, revenue, language, runtime, etc. (includes nested JSON)
- `ratings.csv`: 100,000+ user ratings including user ID, movie ID, rating score, and timestamp

---

## 🛠️ Tools & Technologies

- **Python (Pandas, NumPy)** – Data preprocessing & cleaning
- **Google Colab** – Interactive analysis
- **Power BI** – Dashboard creation
- **JSON Parsing** – Extracting nested fields
- **DAX** – Custom measures for KPIs

---

## ⚙️ Workflow

```mermaid
graph TD;
    A[Collect Data from Kaggle] --> B[Clean & Transform Data using Python];
    B --> C[Feature Engineering (Profit, ROI, Genre, etc)];
    C --> D[Export Clean Data to Power BI];
    D --> E[Create Dashboards & Visualizations];
