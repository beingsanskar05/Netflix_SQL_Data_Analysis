# Netflix SQL Data Analysis Project
![Netflix Logo](https://github.com/beingsanskar05/Netflix_SQL_Data_Analysis/blob/main/netflix.png)
This project focuses on analyzing Netflix dataset using SQL in PostgreSQL.  
The project includes real-world business problems, data exploration, content analysis, and advanced SQL queries to extract meaningful insights from Netflix content data.

---

## Project Objectives

- Analyze Movies and TV Shows distribution
- Identify popular ratings and genres
- Explore country-wise Netflix content
- Perform trend analysis on release years
- Analyze actors, directors, and categories
- Practice advanced SQL concepts using real datasets

---

## Dataset Information

The dataset contains Netflix content information including:

- Show ID
- Type (Movie / TV Show)
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

## SQL Concepts Used

This project demonstrates practical usage of:

- SELECT Statements
- WHERE Clause
- GROUP BY
- ORDER BY
- Aggregate Functions
- Window Functions
- CTEs
- CASE Statements
- STRING Functions
- DATE Functions
- Type Casting
- Pattern Matching (`LIKE` & `ILIKE`)
- Array Functions
- PostgreSQL Functions

---

## Business Problems Solved

### 1. Count Movies vs TV Shows
### 2. Most common rating by content type
### 3. Movies released in a specific year
### 4. Top 5 countries with most Netflix content
### 5. Longest movie on Netflix
### 6. Content added in last 5 years
### 7. Content by specific director
### 8. TV Shows with more than 5 seasons
### 9. Content count by genre
### 10. Year-wise content analysis in India
### 11. Documentary movies analysis
### 12. Content without directors
### 13. Salman Khan movies in last 10 years
### 14. Top actors in Indian Netflix content
### 15. Content categorization using keywords

---

## Advanced PostgreSQL Features Used

- `RANK() OVER()`
- `UNNEST()`
- `STRING_TO_ARRAY()`
- `SPLIT_PART()`
- `TO_DATE()`
- `EXTRACT()`
- `CASE WHEN`
- `ILIKE`

---

## Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin

---

## Key Learnings

- Writing optimized analytical SQL queries
- Solving business problems using SQL
- Working with real-world datasets
- Using PostgreSQL-specific functions
- Performing data cleaning and transformation

---

## Project Structure

```bash
Netflix_SQL_Data_Analysis/
│
├── netflix_sql_project.sql
├── README.md
└── dataset/
    └── netflix_titles.csv
