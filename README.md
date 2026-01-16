# 🎬 Netflix Content Acquisition Strategy Dashboard

A data-driven Power BI dashboard analyzing 2,200+ movies to identify high-potential content acquisitions by origin country, genre, and region.

## 📊 Dashboard

- [View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWY2Nzc3ZWEtNjNjNS00YjdhLThmMGYtMzk1ZGE4N2JlZWQ5IiwidCI6ImQxMjA2OTQzLWJmY2MtNGM3NC04MmQ0LTA1ZTYzYTQzMzViZiJ9)

## Planning

- [View Initial Planning Doc](https://excalidraw.com/#json=peP1kAHjSXSWdi6jEW_k8,7fgmwI0yxn_NpWrfEmPKvA)


## 🎯 Features

**Home Page - Overview**
- 6 KPIs: Subscribers, ARPU, Total Revenue, Hours Watched, Movie Count, Avg Rating
- Top 5 origin countries by average rating
- Genre performance distribution
- Revenue and subscriber trends by region
- Most viewed movies (image grid)

**Insights Page - Dynamic Analysis**
- Genre-specific performance deep-dive
- Top 5 most watched genres + movie count per genre
- Genre growth % analysis
- Movie quality vs. engagement scatter plot
- Production company performance
- Top movies from selected filters
- Dynamic insights: actionable recommendations based on growth trends

**Features Across All Pages**
- Dynamic filtering: Year, Region, Origin Country, Genre, Rating
- Drill-through to movie details
- Geographic map showing movies per origin country
- Hidden gems detection (high-rated, low-visibility content)
- Genre combination analysis

## 📈 Data Sources

- **TMDB API**: Movie metadata (budget, revenue, ratings, genres, production companies and more)
- **Watchmode API**: Netflix catalog availability
- **Netflix Reports**: Hours watched by movie by year half (2023 Q3&4 -2025 Q1&2)
- **Public Data**: Regional ARPU, subscriber counts, revenue by region

## 🛠 Tools & Skills

**Data Engineering**
- Python (pandas, requests library)
- Multi-API integration with error handling & rate limiting
- Data validation & cleaning

**Data Modeling**
- Star Schema design
- Bridge tables for many-to-many relationships
- Dimensional hierarchies (Region → Country → Movie)

**Analytics & Visualization**
- Power BI Desktop
- Advanced DAX (25+ measures)
- Custom themes & Netflix branding
- Conditional logic & dynamic filtering
- KPI cards, scatter plots, maps

## 📊 Key Insights

- Comedy dominates globally (4.4B hours watched)
- Thriller shows strongest growth (+18.1% from 2024)
- Of Countries with at least 5 Movies available, Movies from the Netherlands produce the highest average hours watched at 9.3M
- Movies from the latin america region have had the biggest growth in avg views at 34.67%

```

## 💡 Business Impact

This dashboard enables Netflix's content acquisition team to:
- Identify high-Region and origin countries producing content growing in popularity
- Produces Quick tailored and dynamic insights on top forforming genres in the selected region
- Make data-backed budget allocation decisions
- Monitor genre performance trends

## 📞 Questions?

Feel free to reach out or explore the interactive dashboard above!

