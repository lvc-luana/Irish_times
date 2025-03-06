# Irish_times
## Exploratory Analysis of the Irish Times Headlines

## Introduction
This dataset is a collection of over 1.61 million headlines posted by the Irish Times over a period of 25 years. With categories ranging from business and sports to culture, lifestyle, and opinion, this dataset offers a comprehensive overview of the happenings in Europe. The articles are dated from 1996-01-01 to 2021-06-30 and are categorized based on their headline and publication date. The dataset also includes a bonus set of observational data from Nigeria, spanning 15 months. This dataset offers researchers and data enthusiasts a valuable resource to explore and analyze trends, sentiments, and patterns in news reporting over an extended period.

## Objective
The objective of this dataset is to provide a comprehensive collection of 1.61 million headlines published by the Irish Times over a quarter of a century, spanning various categories including business, sport, culture, lifestyle, and opinion. The dataset aims to enable researchers and analysts to analyze trends and patterns in news coverage over time and across categories. 

## Tools and Libraries Used
**Python:** Primary programming language.
**Pandas:** Data manipulation and analysis.
**NumPy:** Numerical computations.
**Matplotlib/Seaborn:** Data visualization.
**TextBlob:** Sentiment analysis.
**WordCloud:** Generating word clouds.

## The analysis covers:

## Data loading and initial exploration:
Loading the dataset and performing an initial inspection of its structure and content.
Identifying the size of the dataset, the number of rows and columns, and the attributes present.

## Category analysis:
Exploring the 103 distinct categories of headlines.
Identifying the most frequent categories, with "news" being the most common.

## Handling missing values:
Detecting and removing 7 missing values in the headline_text column to ensure data consistency.

## Data transformation:
Converting the publish_date column into a datetime format.
Creating new columns for year, month, day, and day of the week for deeper temporal analysis.

## Temporal analysis:
Visualizing the number of headlines published per year using a line chart.
Observing an increasing trend in the volume of headlines over the years.

## Monthly distribution:
Analyzing the distribution of headlines by month to identify seasonal patterns.
Creating a bar chart to visualize monthly trends.

## Word clouds for Top 10 categories:
Generating word clouds for the 10 most frequent categories to highlight the most recurring terms.
Providing insights into the main topics covered in each category.

## Sentiment Analysis by Year:
Performing sentiment analysis on the headlines using the TextBlob library.
Aggregating sentiment scores by year to observe emotional trends over time.
Visualizing the evolution of average sentiment using graphs.

# Key Findings

**Temporal Trends:** The number of headlines has increased over the years, indicating growing activity or coverage by the Irish Times.

**Category Insights:** The "news" category dominates, but other categories like "sport" and "business" also show significant activity.

**Seasonal Patterns:** Monthly distributions reveal potential seasonal trends in headline publication.

**Word Frequency:** Word clouds for the top 10 categories highlight the most common terms, providing a quick overview of key topics.

**Sentiment Trends:** Sentiment analysis shows variations in emotional tone over the years, possibly linked to social, political, or economic events.
