
## Olympic medal count predictions by country

- This project aims to predict the number of medals that different countries will win in the Olympics using various machine learning models. The dataset includes information about the teams, their participation in different years, and their previous performances.




## Dataset & Features

'athlete_events.csv' - This file is the original athlete-level data. It includes detailed information about each athlete who has participated in the Olympics, such as their demographics, events, and performances. 
- URL - https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results.
####

'teams.csv' - We created this file from the above main file, which contains the team-level data that we use in this project. It provides information about the different teams that participated in the Olympics. The dataset teams.csv contains the following columns:

- team: The team code.
- country: The country name.
- year: The year of the Olympics.
- events: Number of events the country participated in.
- athletes: Number of athletes representing the country.
- age: Average age of the athletes.
- height: Average height of the athletes.
- weight: Average weight of the athletes.
- medals: Number of medals won.
- prev_medals: Number of medals won in the previous Olympics.
- prev_3_medals: Average number of medals won in the previous three Olympics.





## Libraries

- pandas
- seaborn
- numpy
- matplotlib
- scikit-learn
## Analysis Steps

1. Data Loading and Inspection - Load the dataset and inspect its structure and content using Pandas.

2. Data Preprocessing - Select relevant columns, handle missing values, and prepare the dataset for analysis.

3. Correlation Analysis - Calculate the correlation matrix to identify relationships between features and medals won.

3. Visualization - Use Seaborn to create visualizations to better understand the relationships in the data.

4. Train-Test Split - Split the dataset into training and testing sets based on the Olympic year.

5. Model Training and Evaluation - Train various regression models to predict the number of medals and evaluate their performance using Mean Absolute Error (MAE).

## ML Models Used 

- Linear Regression 
- Random Forest Regressor 
- Gradient Boosting Regressor
- Support Vector Regressor 
- K-Neighbors Regressor