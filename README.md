# IMDB Database Analysis

## Project/Goals
In this Project we will explore the imdb database of all movies, as well as a more detailed top 1000 list to see if we can gain any insights. 
The two datasets used are here:
https://www.kaggle.com/datasets/komalkhetlani/imdb-dataset
https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000


## Layout
- The data folder contains one folder for the raw data and another for the processed data.  The complete sql database is also there along with an ERD
- The Notebooks folder is seperated into 3 steps: cleaning, EDA, and modeling.  There is no specific ordering within the folders.
## Process
1. The Larger database came in 7 seperate csv files, so the first step was to clean those and load it into a sql database. 
2. EDA
3. Linear Regression Models
4. Created a tableau dashboard to display our findings

### Exploring
While exploring the data some questions we came up with were:
- Is a movies budget correlated to its rating?
- Did the popularity of different genres change over time? ex: covid or the 2008 real estate crash
- How much can actors and directors influence a movies rating?
- Can we make a model that will predict a movies rating based on other factors?





## Results
- Unfortunately the models did not have a high enough R-Squared to be useful.  One interesting find is the effect each genre will have on the average rating, with the highest (Documentary) giving +0.9 and the lowest (Horror) giving -1
- 

## Challenges 
- The database is quite large and caused lots of crashes and slow loading in excel and tableau
- Many of the movies are in foreign languages, or have multiple titles listed for localized releases
- TV show episode data is in there too which we dont need
- Gross revenue for each movie was only available for the top 1000


## Future Goals
