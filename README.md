# The introduction of the dataset
The dataset contains information about the100 lowest ranked movies from the IMDb site and provides information about the 100 lowest ranked movies, including their rankings, details such as release year and duration etc.

# The table of the varieable
| Variable      | Description                                     | DataType           |
| ------------- | ----------------------------------------------- | ------------------ |
| Rank          | The ranking position of the celebrity           | Numeric            |
| Name          | The name of the celebrity                        | String             |
| Year          | The year of release of the movie                 | Numeric            |
| Certification | The viewership certification/rate of the movie   | String or Numeric  |
| Duration      | Duration of the movie                            | Numeric            |
| Rating        | Rating of the movie out of 10                    | Numeric            |
| Review_count  | Number of reviews or number of users who reviewed the movie | Numeric |
| Director      | Name of the director(s) of the movie             | String             |
| Writer        | Name of the writer(s) of the movie               | String             |
| Genre         | Genre or category of the movie                   | String             |
| Stars         | Stars/Celebrities in that movie                 | String             |

# The creator
Lakshay Jain

# The source about the dataset
The data has been collected through web scraping from the 'https://www.imdb.com/chart/bottom/' webpage.

# Discription of the project

The topic of exploring the lowest-rated 100 movies on IBMD website holds significance in figuring out what the lowest-rated movies have in common, how important audience preferences are in the evaluation system, and what factors influence audience choice.

## Research Question (RQ):

What are the common characteristics or patterns observed in the lowest-rated 100 movies on IBMD, and how do these align with existing theories on film criticism?

## Hypothesis:

Movies with lower ratings on IBMD may exhibit a convergence of factors such as weak narrative structures, substandard performances, and technical flaws, aligning with previous theoretical claims regarding the determinants of low audience ratings.

## Exploration and Addressing RQs:

To explore this topic, a comprehensive analysis of the lowest-rated 100 movies on IBMD can be conducted. This involves data collection, categorization, and comparative analysis of various features such as plot complexity, acting quality, production budget, and audience engagement.

## Data Requirements:
Movie Information: Title, release year, genre, duration.
Audience Ratings: Ratings on IBMD.
Production Details: Director, writer, budget.
Audience Engagement: Review count, comments, and user reviews.

## Tools and Methods:
Web Scraping: Utilize web scraping tools or libraries (e.g., Beautiful Soup) to collect data from IBMD website.
Data Analysis: Employ statistical tools (e.g., Python with Pandas and NumPy) to analyze the collected data.
Visualization: Create visualizations (e.g., charts, graphs) to present patterns and trends.
Text Analysis: For analyzing user reviews and comments, natural language processing tools (e.g., NLTK or spaCy) can be employed.

By employing these tools and methods, the research can systematically explore the identified patterns in the lowest-rated movies, providing insights into the factors contributing to their low ratings and how these align with existing theoretical claims.
