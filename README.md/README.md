# Netflix Content Analysis Dashboard | Power BI

## 📊 Project Overview

This project analyzes Netflix movies and TV shows using Microsoft Power BI.

The dataset contains information about Netflix titles, including content type,
genres, countries, directors, ratings, release years, duration, and date added.

The goal of this project is to understand Netflix's content library and identify
important trends and patterns through interactive dashboards.

---

## 🎯 Project Objectives

- Analyze the distribution of Movies and TV Shows
- Identify the most common Netflix genres
- Analyze Netflix content by country
- Analyze content ratings
- Identify content trends by release year and date added
- Analyze movie duration and TV show seasons
- Identify top directors based on number of titles
- Build an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## 📁 Dataset

The dataset contains **8,807 Netflix titles** and includes the following fields:

- Show ID
- Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

---

## 🔄 Data Preparation

The raw Netflix dataset was prepared using Power Query.

### Data Cleaning

- Removed duplicate records
- Handled missing values
- Replaced missing text values with "Unknown"
- Corrected data types
- Cleaned text fields

### Data Transformation

- Extracted Year Added from Date Added
- Created Duration Value
- Created Duration Unit
- Prepared Genre data
- Prepared Country data

---

## 📐 DAX Analysis

Created calculated columns and measures such as:

- Total Titles
- Total Movies
- Total TV Shows
- Movie Percentage
- TV Show Percentage
- Average Movie Duration
- Year Added

---

## 📊 Dashboard Pages

### 1. Netflix Overview

Provides a high-level overview of Netflix content using:

- KPI Cards
- Movies vs TV Shows
- Content Added by Year
- Rating Analysis
- Release Year Analysis
- Interactive Slicers

### 2. Content Analysis

Analyzes:

- Top Genres
- Content Type
- Ratings
- Movie Duration
- TV Show Seasons
- Release Year Trends

### 3. Country & Director Analysis

Analyzes:

- Top Countries
- Top Directors
- Content by Country
- Movies vs TV Shows by Country
- Geographic Distribution

---

## 🎛️ Power BI Features Used

- Power Query
- Data Cleaning
- Data Transformation
- DAX
- Calculated Columns
- Measures
- Data Modeling
- KPI Cards
- Slicers
- Filters
- Interactive Visualizations
- Drill-through
- Dashboard Design

---

## 🖼️ Dashboard Preview

### Netflix Overview

![Netflix Overview](Screenshots/Page1_Overview.png)

### Content Analysis

![Content Analysis](Screenshots/Page2_Content_Analysis.png)

### Country & Director Analysis

![Country & Director Analysis](Screenshots/Page3_Country_Director.png)

---

## 💡 Key Insights

The dashboard helps identify:

- Distribution of Movies and TV Shows on Netflix
- Most common genres
- Countries contributing the most content
- Most common content ratings
- Netflix content growth over time
- Top directors by number of titles
- Average movie duration
- Differences between Movies and TV Shows

---

## 📂 Project Structure

Netflix-PowerBI-Analysis/

├── Dataset/

│   └── netflix_titles.csv

├── PowerBI/

│   └── Netflix_Content_Analysis.pbix

├── Screenshots/

│   ├── Page1_Overview.png

│   ├── Page2_Content_Analysis.png

│   └── Page3_Country_Director.png

└── README.md

---

## 👨‍💻 Project Type

Data Analytics / Business Intelligence Project

**Tool:** Power BI

**Domain:** Entertainment / Streaming Analytics