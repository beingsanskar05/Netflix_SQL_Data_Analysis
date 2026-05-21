# Netflix SQL Data Analysis Project

![Logo](https://github.com/beingsanskar05/Netflix_SQL_Data_Analysis/blob/main/logo.png)

## Overview

This project focuses on analyzing Netflix Movies and TV Shows dataset using PostgreSQL and SQL.  
The goal of this project is to solve real-world business problems, perform data analysis, and extract meaningful insights from Netflix content data.

The project demonstrates practical implementation of SQL concepts including:
- Window Functions
- CTEs
- Aggregate Functions
- String Functions
- Date Functions
- CASE Statements
- Pattern Matching
- PostgreSQL-specific functions

---

# Objectives

- Analyze Movies vs TV Shows distribution
- Identify the most common ratings
- Explore country-wise content trends
- Analyze genres, actors, and directors
- Perform year-wise Netflix content analysis
- Categorize content based on keywords
- Practice advanced SQL querying techniques

---

# Dataset Information

The dataset contains:
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
- Genres
- Description

Dataset Source: Netflix Titles Dataset

---

# Database Schema

```sql
DROP TABLE IF EXISTS netflix;

CREATE TABLE netflix
(
    show_id VARCHAR(10),
    type VARCHAR(15),
    title VARCHAR(200),
    director VARCHAR(210),
    casts VARCHAR(2000),
    country VARCHAR(200),
    date_added VARCHAR(50),
    release_year INT,
    rating VARCHAR(10),
    duration VARCHAR(15),
    listed_in VARCHAR(250),
    description VARCHAR(300)
);
```

---

# SQL Concepts Used

- SELECT Statements
- WHERE Clause
- GROUP BY
- ORDER BY
- Aggregate Functions
- Window Functions
- CTEs
- CASE Statements
- Pattern Matching (`LIKE` & `ILIKE`)
- String Functions
- Date Functions
- Type Casting
- PostgreSQL Functions

---

# PostgreSQL Functions Used

```sql
RANK()
UNNEST()
STRING_TO_ARRAY()
SPLIT_PART()
TO_DATE()
EXTRACT()
CASE WHEN
ILIKE
```

---

# Business Problems Solved

### 1. Count Movies vs TV Shows

### 2. Find Most Common Rating for Movies & TV Shows

### 3. List Movies Released in 2020

### 4. Top 5 Countries with Most Netflix Content

### 5. Identify the Longest Movie

### 6. Find Content Added in Last 5 Years

### 7. Find Content by Director 'Rajiv Chilaka'

### 8. TV Shows with More Than 5 Seasons

### 9. Count Content Items by Genre

### 10. Year-wise Average Content Release in India

### 11. List Documentary Movies

### 12. Find Content Without Director

### 13. Salman Khan Movies in Last 10 Years

### 14. Top 10 Actors in Indian Netflix Content

### 15. Categorize Content as Good or A-Rated

---

# Key Insights

- Movies dominate Netflix content compared to TV Shows
- India is among the top contributors to Netflix content
- Drama and International Movies are highly common genres
- TV-MA is one of the most frequent ratings
- Netflix content significantly increased after 2015

---

# Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin 4
- Kaggle Dataset

---

# Project Structure

```bash
Netflix_SQL_Data_Analysis/
│
├── netflix_sql_project.sql
├── README.md
├── logo.png
└── dataset/
    └── netflix_titles.csv
```

---

# Future Improvements

- Create Power BI Dashboard
- Add Tableau Visualizations
- Optimize Queries
- Create SQL Views
- Add Stored Procedures
- Build Recommendation Analysis

---

# About Me

## Sanskar Pandey

Aspiring Data Analyst passionate about:
- SQL
- Power BI
- Python
- Data Analytics
- Machine Learning

---


# Project Outcome

This project helped strengthen:
- SQL Query Writing
- Business Problem Solving
- Data Cleaning & Transformation
- PostgreSQL Query Optimization
- Analytical Thinking

