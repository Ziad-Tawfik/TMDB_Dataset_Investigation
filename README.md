# TMDB_Dataset_Investigation

The primary goal of the project is to go through the dataset and the general data analysis process using numpy, pandas and matplotlib.
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

## Project Overview
In this project, you will analyze a dataset and then communicate your findings about it. You will use the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier.

## What do you need to install?
You will need an installation of Python, plus the following libraries:

* pandas
* NumPy
* Matplotlib
* csv

## Why this Project?
In this project, you'll go through the data analysis process and see how everything fits together. Later Nanodegree projects will focus on individual pieces of the data analysis process.

You'll use the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier! Not only that, these are sought-after skills by employers!

## What will you learn?
After completing the project, you will:

- Know all the steps involved in a typical data analysis process
- Be comfortable posing questions that can be answered with a given dataset and then answering those questions
- Know how to investigate problems in a dataset and wrangle the data into a format you can use
- Have practice communicating the results of your analysis
- Be able to use vectorized operations in NumPy and pandas to speed up your data analysis code
- Be familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently
- Know how to use Matplotlib to produce plots showing your findings

## Exploratory Data Analysis
Tip: Now that you've trimmed and cleaned your data, you're ready to move on to exploration. Compute statistics and create visualizations with the goal of addressing the research questions that you posed in the Introduction section. It is recommended that you be systematic with your approach. Look at one variable at a time, and then follow it up by looking at relationships between variables.

## Research Questions

1. What is distribution of Gross Revenue and the relation between Net Profit, Popularity and Rating?
2. Actors with the most appearances
3. Which Movies have the highest net profit, budget, revenue
4. Which Movies have the Lowest net profit, revenue
5. Which genres are most popular from year to year?
6. What is movies' average run time?

## Conclusions

### Question 1: What is distribution of Gross Revenue and the relation between Net Profit, Popularity and Rating

    - From Scatter plots we can see that the relation is direct proportional between the 3 variables

### Question 2: Actors with the most appearances

    - As per barblot we conclude that the top actors with the most movies are Robert De Niro, Bruce Willis, Samuel L. Jackson, Nicolas Cage and Matt Damon.

### Question 3: Which Movies have the highest net profit, budget, revenue

    - As per barplots we conclude that Avatar is the most profitable movie as per dataset in terms of (Net Profit)

### Question 4: Which Movies have the Lowest net profit, budget, revenue

    - As per barplots we conclude that The Warrior's Way is the most loss-making movie as per dataset in terms of (Net Profit)

### Question 5: Which genres are most popular from year to year?

    - As per scatterplot we conclude can find that science fiction is the most popular genre in the last 3 years in the dataset, meanwhile since 1999 till 2005 the most popular genre was Fantasy, noting that the most filmed genre was Drama followed by Comedy, Thriller and Action movies.

### Question 6: What is movies' average run time?

    - It's concluded that average run time for movies is around 110 mins and the histogram is right skewed, with the shortest movie is 15 mins long and the longest movie is 338 mins.


