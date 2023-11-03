# IMDB Database Analysis

## Project/Goals
In this project, we aim to explore the IMDb database encompassing all movies, alongside a more detailed examination of the top 1000 list, with the goal of deriving valuable insights. The two datasets utilized can be found at the following links:

IMDb Database of All Movies: https://www.kaggle.com/datasets/komalkhetlani/imdb-dataset

Detailed IMDb Top 1000 Dataset: https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000

## Layout
- The 'data' directory includes two subfolders: one for raw data and another for processed data. 
- Additionally, it contains the complete SQL database and an Entity-Relationship Diagram (ERD).
- Within the 'Notebooks' folder, there are three distinct subfolders: cleaning, EDA, and modeling. 
- The notebooks are organized within these folders without any specific order.

## Process
1. The larger database was delivered in seven separate CSV files, necessitating the initial step of cleaning and loading them into an SQL database.
2. Exploratory Data Analysis (EDA) - Initially, we conducted several preliminary visualizations and subsequently modified each diagram to integrate them into the Tableau dashboard.
3. Utilized Linear Regression Models
4. Developed a Tableau dashboard to present and showcase our discoveries.

## Exploring
1. Is there a correlation between a movie's budget and its rating?
2. Have the popularity trends of various genres changed over time, particularly during significant events like the COVID-19 pandemic or the 2008 real estate crash?
3. To what extent can actors and directors influence a movie's rating?
4. Is it possible to create a predictive model that estimates a movie's rating based on other contributing factors?

## Results
- Unfortunately, the models failed to achieve a sufficiently high R-Squared to be considered useful. However, one intriguing find was the impact of each genre on the average rating. The highest impact was observed in the Documentary genre, which contributed a +0.9, while the lowest impact was found in the Horror genre, resulting in a -1.
- Refer to the Tableau dashboards for comprehensive insights on top directors and movies.
  
## Challenges 
- The database's substantial size has led to frequent crashes and slow loading times in both Excel and Tableau.
- Numerous movies in the database are either in foreign languages or have multiple titles listed for localized releases.
- Additionally, the database contains TV show episode data, which is unnecessary for our purposes.
- Gross revenue information is available for only the top 1000 movies.

## Future Goals
- We encountered challenges aligning the years, removing the duplications with different language titles within the dataset. Moving forward, we aim to improve our process to minimize such errors in future analyses.
- We are eager to conduct API searches for data up to 2023 to enhance our statistical tests and gain further insights.
