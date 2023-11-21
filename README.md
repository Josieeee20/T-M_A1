# The introduction of the dataset
The dataset contains information about the100 lowest ranked movies from the IMDb site and provides information about the 100 lowest ranked movies, including their rankings, details such as release year and duration etc.

## The table of the varieable
| Variable      | Description                                     | DataType           |
| ------------- | ----------------------------------------------- | ------------------ |
| Rank          | The ranking position of the celebrity           | Numeric            |
| Name          | The name of the celebrity                        | String             |
| Year          | The year of release of the movie                 | Numeric            |
| Certification | The viewership certification/rate of the movie   | String   |
| Duration      | Duration of the movie                            | Numeric            |
| Rating        | Rating of the movie out of 10                    | Numeric            |
| Review_count  | Number of reviews or number of users who reviewed the movie | Numeric |
| Director      | Name of the director(s) of the movie             | String             |
| Writer        | Name of the writer(s) of the movie               | String             |
| Genre         | Genre or category of the movie                   | String             |
| Stars         | Stars/Celebrities in that movie                 | String             |

## The creator
Lakshay Jain

## The source about the dataset
The data has been collected through web scraping from the 'https://www.imdb.com/chart/bottom/' webpage.

# Discription of the project

Exploring the lowest-rated 100 movies on the IBMD website is crucial for understanding commonalities among poorly rated films, the significance of audience preferences in the evaluation system, and the factors influencing audience choices. Reddy (2020) suggests a potential correlation between the ratings of low-scoring movies and the internet's movie recommendation mechanism. Building on this, Kotkov (2022) emphasizes the impact of movie tags on influencing movie rating decisions. This study aims to explain why audiences give films low ratings and its potential trend.

Reddy, M. M., Kanmani, R. S., & Surendiran, B. (2020, February). Analysis of Movie Recommendation Systems; with and without considering the low rated movies. In *2020 International Conference on Emerging Trends in Information Technology and Engineering (ic-ETITE)* (pp. 1-4). IEEE.

Kotkov, D., Medlar, A., Satyal, U. R., Maslov, A., Neovius, M., & Glowacka, D. (2022, April). Rating consistency is consistently underrated: An exploratory analysis of movie-tag rating inconsistency. In *Proceedings of the 37th ACM/SIGAPP Symposium on Applied Computing* (pp. 1355-1364).


## Research Question (RQ):

What are the common characteristics or patterns observed in the lowest-rated 100 movies on IBMD ?

## Hypothesis:

Movies with lower ratings on IBMD may exhibit a convergence of factors such as unrasonable rating mechanism and weak narrative structures, substandard performances, and technical flaws.

## Exploration and Addressing RQs:

To explore this topic, a comprehensive analysis of the lowest-rated 100 movies on IBMD can be conducted. This involves data collection, categorization, and comparative analysis of various features such as plot complexity, acting quality and audience engagement.

## Data Requirements:
Movie Information: Title, release year, genre, duration.

Audience Ratings: Ratings on IBMD.

Production Details: Director, writer, budget.

Audience Engagement: Review count, comments, and user reviews.


## Tools and Methods:
Web Scraping: Utilize web scraping tools to collect data from IBMD website.

Data Analysis: Employ statistical tools (e.g., Python with Pandas ) to analyze the collected data.

Visualization: Create visualizations (e.g., charts, graphs) to present patterns and trends.

Text Analysis: For analyzing user reviews and comments, natural language processing tools (e.g., NLTK ) can be employed.

By employing these tools and methods, the research can systematically explore the identified patterns in the lowest-rated movies, providing insights into the factors contributing to their low ratings and how these align with existing theoretical claims.
