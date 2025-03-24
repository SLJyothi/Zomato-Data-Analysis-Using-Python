# Zomato-Data-Analysis-Using-Python
This project provides an in-depth analysis of a Zomato restaurant dataset using Python. The dataset includes various features of restaurants such as whether they offer online ordering, table booking, their ratings, the number of votes, and the approximate cost for two people. Through this analysis, insights are drawn regarding customer preferences, restaurant pricing, ratings, and much more.

## Table of Contents
- [Project Overview(#project-overview)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visualization](#visualization)
- [Insights](#insights)
- [Conclusion](#conclusion)
- [License](#license)

## Project Overview

This project aims to analyze the Zomato dataset and uncover hidden patterns and insights. The dataset includes information like restaurant names, online order availability, table booking options, ratings, votes, cost estimates, and types of listings. The goal is to:

- Clean and preprocess the data
- Perform exploratory data analysis (EDA)
- Visualize trends and correlations in the data
- Derive actionable insights based on analysis

## Technologies Used

This project utilizes the following technologies:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Usage
After setting up the environment, open the Jupyter Notebook (zomato_analysis.ipynb) file.
Run the cells in the notebook to explore the dataset, perform data preprocessing, and visualize the analysis.
You can also modify the code to perform further analysis or work with different datasets.

## Data Preprocessing
Before performing any analysis, the data goes through the following preprocessing steps:
Handling missing values by filling them with the mean or median where appropriate.
Ensuring that columns like ratings, votes, and cost are in their correct data types (e.g., integers or floats).
Converting categorical columns like online_order, book_table, and listed_in(type) to numeric or appropriate formats for analysis.

## Exploratory Data Analysis (EDA)
EDA involves:
Checking for missing values and getting basic statistics of the dataset.
Exploring unique values for categorical columns.
Identifying trends in ratings, number of votes, and other variables.
Creating new features like is_online_order, is_book_table, and price_category.


## Visualization
Several data visualizations are created to uncover insights:
1. Distribution of Ratings: A histogram showing how the ratings are distributed across the restaurants.
2. Online Orders and Table Booking: Count plots showing the availability of online ordering and table booking across restaurants.
3. Rating vs Price Category: A box plot to show the relationship between restaurant ratings and their price categories.
4. Top Restaurants by Votes: A bar plot of the top 10 restaurants based on votes.

## Insights
From the analysis, the following insights were obtained:

1. Online Ordering: A large proportion of restaurants offer online ordering, and there seems to be a correlation between offering online orders and higher ratings.
2. Price Range: Restaurants in the medium price category seem to attract the highest number of customers and also provide good ratings.
3. Customer Engagement: A higher number of votes does not always correlate with higher ratings. More votes often imply higher popularity.
4. Cost Insights: Lower-cost restaurants tend to have higher ratings, possibly due to better value for money.

## Conclusion
This data analysis provides useful insights into Zomato's restaurant dataset, such as customer preferences for online ordering, table booking, and price sensitivity. These insights can be helpful for both restaurant owners to improve their business strategies and for customers to make informed decisions based on restaurant offerings.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
