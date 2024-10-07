[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rGYtBYfw)

# Short Report 

### Overview

The Movies dataset is a collection of movie-related information, including key attributes like movie titles, ratings, votes, budgets, and revenues. This dataset allows us to analyze various aspects of films, such as audience reception and financial performance. For this analysis, we focused on the relationship between budget and popularity to understand how production investment influences audience appeal.

### Data Manipulation

###### Cleaning:
We removed columns not needed for this analysis, like overview, genres, and imdb_id, keeping only key metrics: title, vote_average, vote_count, revenue, budget, and popularity. This streamlined the dataset for focused exploration of financial performance and audience engagement.

###### Sorting:
The dataset was sorted by revenue to prioritize high-grossing films for a clearer view of their budget and popularity dynamics.

##### NumPy Operations:
We used NumPy to calculate basic statistics for budget, revenue, and popularity, helping us observe general patterns in the data.

##### Exploring Budget vs. Popularity:
We specifically analyzed whether higher budgets led to higher popularity. Some high-budget films, like Avengers: Infinity War and Interstellar, had high popularity scores, suggesting a positive correlation. However, exceptions like Guardians of the Galaxy and Deadpool showed that higher budgets do not always guarantee higher popularity.

### Key Insights
Budget Can Drive Popularity: For some films, like Avengers: Infinity War (budget: $300M, popularity: 154.340) and Harry Potter and the Philosopher's Stone (budget: $125M, popularity: 185.482), larger budgets aligned with higher popularity.

Mixed Results: Movies like Guardians of the Galaxy (budget: $170M, popularity: 33.255) and Deadpool (budget: $58M, popularity: 72.735) had high budgets but comparatively low popularity, indicating other factors might affect popularity.

Low-Budget Successes: Films like Pulp Fiction (budget: $8.5M, popularity: 74.862) show that even lower-budget movies can achieve moderate popularity, suggesting that budget alone doesn't determine a film's success with audiences.

### Limitations
Missing Data: We dropped several columns with missing values, which could have provided more context.
Small Sample Size: This analysis focuses on a small sample of 15 movies, limiting the generalizability of the findings.

### Conclusion
While higher budgets generally contribute to higher popularity, this dataset reveals that the relationship is not absolute. Several films with smaller budgets still managed to achieve moderate popularity, showing that other factors, such as storytelling, marketing, or genre, also play key roles in a movie's audience appeal.

