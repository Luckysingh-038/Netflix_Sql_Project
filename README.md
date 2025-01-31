# Netflix Movies and TV Shows Data Analysis using SQL
[Netflix Logo]{https://github.com/Luckysingh-038/Netflix_Sql_Project/blob/main/Netflix%20logo.png}


This repository contains SQL queries designed to analyze Netflix data. The queries cover multiple business-related questions to explore various aspects of Netflix's content, including movies and TV shows. These analyses include counting content types, exploring ratings, identifying actors, and categorizing content based on certain keywords.

## 📋 Table of Contents

- [Overview](#overview)
- [Queries](#queries)
- [Usage](#usage)


---

## 🎯 Overview

This project demonstrates how to leverage SQL to analyze Netflix’s content data. The queries are written for **SQL Server** and are intended to be run on a database with a table called `netflix`, which holds information about Netflix's movies and TV shows.

The queries answer the following types of business questions:

- **Content Types**: Movie vs. TV Show counts, longest movie
- **Ratings & Genres**: Most common ratings, genre counts
- **Content Analysis**: Most content from specific countries, actors, directors, and more
- **Content Categorization**: Classifying content as "Good" or "Bad" based on keywords like "kill" and "violence"

---

## 📝 Queries

### 1. **Count the number of Movies vs TV Shows**
   - This query counts how many movies and TV shows are present in the `netflix` table.

### 2. **Find the most common rating for Movies and TV Shows**
   - Identifies the most frequently occurring rating for both movies and TV shows.

### 3. **List all movies released in a specific year (e.g., 2020)**
   - Retrieves all the movies that were released in 2020.

### 4. **Find the top 5 countries with the most content on Netflix**
   - Shows which countries have the highest number of Netflix content available.

### 5. **Identify the longest movie**
   - Finds the movie with the longest duration in the `netflix` table.

### 6. **Find content added in the last 5 years**
   - Retrieves content that was added to Netflix in the past 5 years.

### 7. **Find all Movies/TV Shows by director 'Rajiv Chilaka'**
   - Lists all content directed by Rajiv Chilaka.

### 8. **List all TV Shows with more than 5 seasons**
   - Shows TV shows with more than 5 seasons.

### 9. **Count the number of content items in each genre**
   - Counts the total number of content items categorized by genre.

### 10. **Find the average content release by India by year**
   - Finds the average number of content items released by India per year and returns the top 5 years with the highest average.

### 11. **List all Movies that are Documentaries**
   - Retrieves all movies that belong to the 'Documentaries' genre.

### 12. **Find all content without a director**
   - Lists all content that doesn't have a director listed.

### 13. **Find how many Movies actor 'Salman Khan' appeared in the last 10 years**
   - Finds the number of movies Salman Khan has appeared in during the last 10 years.

### 14. **Find the top 10 actors in the most movies produced in India**
   - Identifies the top 10 actors who have appeared in the highest number of movies produced in India.

### 15. **Categorize content based on keywords 'kill' and 'violence'**
   - Labels content as **Bad** if it contains keywords like 'kill' or 'violence' in the description, and **Good** otherwise.

---

## 🛠️ Usage

To use the SQL queries in this repository:

1. **Prerequisites:**
   - SQL Server or a compatible database system.
   - Access to a database that contains the `netflix` table with relevant columns (`show_id`, `title`, `type`, `director`, `casts`, `country`, `release_year`, `rating`, `listed_in`, `description`, `date_added`).

2. **Steps to Run Queries:**
   - Clone or download this repository.
   - Open **SQL Server Management Studio (SSMS)** or any SQL client connected to your database.
   - Copy and paste the desired SQL query into your query window.
   - Execute the query and analyze the output.

