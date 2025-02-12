# Netflix Data Analysis Project using SQL
![Netflix Logo](https://github.com/Navin027/Netflix_SQL_Project/blob/main/logo.png)

This project explores a Netflix dataset to gain insights into content trends, popular genres, and other interesting information.  The analysis is performed using SQL queries.

## Dataset

The data for this project is sourced from the Kaggle dataset:

Dataset Link: [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

## Business Problems and Solutions

The project addresses the following business problems using SQL queries:

1. **Count the number of Movies vs TV Shows:**  Determines the proportion of movies and TV shows on Netflix.

2. **Find the most common rating for movies and TV shows:** Identifies the most frequent rating for each content type.

3. **List all movies released in a specific year (e.g., 2020):** Filters movies based on their release year.

4. **Find the top 5 countries with the most content on Netflix:**  Identifies the countries with the largest content libraries.

5. **Identify the longest movie:** Finds the movie with the maximum duration.

6. **Find content added in the last 5 years:** Filters content based on the date it was added to Netflix.

7. **Find all the movies/TV shows by director 'Rajiv Chilaka':**  Filters content by a specific director.

8. **List all TV shows with more than 5 seasons:** Filters TV shows based on the number of seasons.

9. **Count the number of content items in each genre:**  Determines the distribution of content across different genres.

10. **Find each year and the average numbers of content release in India on Netflix and return top 5 years with highest avg content release:** Analyzes content release trends in India over time.

11. **List all movies that are documentaries:** Filters movies specifically in the documentary genre.

12. **Find all content without a director:** Identifies content where the director information is missing.

13. **Find how many movies actor 'Salman Khan' appeared in the last 10 years:** Filters movies based on a specific actor and release year.

14. **Find the top 10 actors who have appeared in the highest number of movies produced in India:** Identifies the most frequent actors in Indian movie production.

15. **Categorize the content based on the presence of the keywords 'kill' and 'violence' in the description field:**  Classifies content based on potentially violent themes.

## SQL Queries

The SQL queries for each of the above problems are included in the provided script.  The queries are designed to be run against a PostgreSQL database.

## How to Run

1.  **Database Setup:** Ensure you have PostgreSQL installed and a database created.
2.  **Table Creation:** Create the `netflix` table using the provided schema.
3.  **Data Import:** Import your Netflix dataset into the `netflix` table.
4.  **Run Queries:** Execute the SQL queries against your database.

## Findings and Conclusion

1.  **Content Distribution:** The dataset contains a diverse range of movies and TV shows with varying ratings and genres.
2.  **Common Ratings:** Insights into the most common ratings provide an understanding of the content's target audience.
3.  **Geographical Insights:** The top countries and the average content releases by India highlight regional content distribution.
4.  **Content Categorization:** Categorizing content based on specific keywords helps in understanding the nature of content available on Netflix.
   This analysis provides a comprehensive view of Netflix's content and can help inform content strategy and decision-making.

