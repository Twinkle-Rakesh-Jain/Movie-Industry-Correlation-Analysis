# Movie-Industry-Correlation-Analysis

## Description:
The Movie Industry Correlation Analysis project aims to explore and analyze a dataset containing information about 6,820 movies spanning from 1986 to 2016. Each movie in the dataset is described by various attributes including budget, production company, country of origin, director, genre, revenue, rating, release date, duration, user rating, number of user votes, main actor/actress, writer, and year of release.


## Project Overview:

### Data Acquisition: 
The dataset was obtained from Kaggle and consists of detailed information about each movie.

### Data Preprocessing: 
Relevant libraries in Python were imported, and exploratory data analysis (EDA) was performed. This included checking for missing data, imputing missing values, dropping rows with missing values, checking data types, converting data types, and removing duplicates.

### Correlation Analysis: 
Various correlation analyses were conducted to understand the relationships between different variables in the dataset. Scatter plots and regression plots were used to visualize the relationship between budget and gross revenue, revealing a positive correlation. The correlation coefficient (Pearson's correlation) was calculated to quantify the strength of the correlation, which was found to be 0.745, indicating a high positive correlation. Additionally, a correlation matrix was created for all numeric columns, revealing high correlation between votes and gross revenue (correlation coefficient of 0.63).

### Categorical Data Encoding: 
Categorical columns were numerically encoded using category codes (cat codes), and correlation pairs with correlation coefficients greater than 0.5 were identified. It was discovered that the number of votes and budget exhibited the highest correlation with gross earnings.


## Key Steps:
1. Data acquisition and preprocessing.
   
2. Exploratory data analysis including missing data handling and data type conversions.
   
3. Correlation analysis using scatter plots, regression plots, and correlation coefficients.
   
4. Categorical data encoding and identification of significant correlation pairs.


## Technologies Used:
Python
Pandas
Numpy
Matplotlib
Seaborn


## Conclusion:
The Movie Industry Correlation Analysis project provides valuable insights into the relationships between various factors influencing the success of movies. By analyzing correlations between different attributes, such as budget, user votes, and gross revenue, stakeholders in the movie industry can make informed decisions and strategies to enhance the performance and profitability of their movies.



