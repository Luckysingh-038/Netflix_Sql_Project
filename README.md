# Netflix Movies and TV Shows Data Analysis using SQL
[Netflix Logo]{}

# Netflix Data Analysis Using SQL

This repository contains SQL queries for analyzing Netflix data and answering 15 business questions related to content distribution, ratings, genres, actors, and more.

## Table of Contents
- [Overview](#overview)
- [Queries](#queries)
- [Usage](#usage)
- [License](#license)

## Overview

This project demonstrates how to use SQL to analyze data related to Netflix's content, such as movies and TV shows. The queries cover various aspects of the data, including:

- Counting the number of movies vs TV shows
- Identifying the most common ratings for content
- Finding the longest movie and content added in the last 5 years
- Analyzing actors, directors, genres, and content released by country
- Categorizing content based on keywords like 'kill' and 'violence'

The queries are written for **SQL Server** and are designed to work with a table named `netflix` which stores information about Netflix’s content.

## Queries

The following SQL queries are included in this repository:

1. **Count the number of Movies vs TV Shows**
   - Counts the number of movies and TV shows in the `netflix` table.

2. **Find the most common rating for movies and TV shows**
   - Identifies the most frequently occurring rating for each type (movie/TV show).

3. **List all movies released in a specific year (e.g., 2020)**
   - Retrieves all the movies released in the year 2020.

4. **Find the top 5 countries with the most content on Netflix**
   - Identifies the countries with the highest number of Netflix content.

5. **Identify the longest movie**
   - Finds the movie with the longest duration.

6. **Find content added in the last 5 years**
   - Retrieves content that was added to Netflix within the past 5 years.

7. **Find all the movies/TV shows by director 'Rajiv Chilaka'**
   - Retrieves all content directed by Rajiv Chilaka.

8. **List all TV shows with more than 5 seasons**
   - Finds all TV shows with more than 5 seasons.

9. **Count the number of content items in each genre**
   - Counts the total number of content items in each genre.

10. **Find each year and the average number of content released by India on Netflix. Return the top 5 years with the highest average content release**
    - Analyzes content released by India, and calculates the average number of content releases by year.

11. **List all movies that are documentaries**
    - Lists all movies that belong to the 'Documentaries' genre.

12. **Find all content without a director**
    - Retrieves all content where the `director` field is null.

13. **Find how many movies actor 'Salman Khan' appeared in the last 10 years**
    - Identifies how many movies Salman Khan has appeared in over the last 10 years.

14. **Find the top 10 actors who have appeared in the highest number of movies produced in India**
    - Identifies the top 10 actors appearing in the most movies produced in India.

15. **Categorize the content based on the presence of the keywords 'kill' and 'violence' in the description field**
    - Labels content as 'Bad' if it contains the keywords 'kill' or 'violence' in the description and 'Good' otherwise.

## Usage

To use these queries:

1. Ensure you have access to the relevant database containing the `netflix` table with content data.
2. Open **SQL Server Management Studio** (SSMS) or any SQL editor connected to your database.
3. Copy and paste the SQL queries from this repository into your editor.
4. Execute the queries and review the results.

### Prerequisites:
- SQL Server or a compatible database system
- Access to a dataset that resembles or matches the structure of the `netflix` table

## License

This repository is available under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

Feel free to contribute or open an issue if you encounter any problems or have suggestions for improvement!



