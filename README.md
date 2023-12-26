# WPL_DATA_ANALYSIS
By the help of Analytical tools and programming we retrieve the WPL 2023 data set and try to analyze them to select the Best Playing 11 of the whole WPL 2023 

# Women's Premier League Dream 11 Predictor
This is a project to predict the best playing 11 for the recently concluded Womens Premier League (WPL) 2023 cricket tournament.
(https://github.com/DaxGupta/WPL_DATA_ANALYSIS)


### ESPNCricinfo Data Collection:
- The project utilizes BeautifulSoup (bs4) to scrape data from the ESPNCricinfo website.
- Specifically, data is scraped from the [Women's Premier League 2022-23](https://www.espncricinfo.com/records/tournament/team-match-results/women-s-premier-league-2022-23-15174) tournament page.
- Match details, batter details, bowler details, and player details are extracted from the HTML structure of the webpage.
- The collected data is structured in the form of a dictionary, where each entry represents a specific match, batter, bowler, or player.
- The dictionary is then converted to JSON for easier handling and storage.

### WPL Website Data Collection:
- Player details and images are collected from the official WPL website located at [wplt20.com/teams](https://www.wplt20.com/teams).
- BeautifulSoup is used to extract relevant information such as player names, teams, and images from the webpages.
- The collected data is added to the existing dictionary in JSON format.

### Data Preprocessing:
- The JSON data is loaded into the Data Preprocessing.ipynb file for further processing.
- Pandas is utilized for data preprocessing tasks.
- The JSON data is loaded into pandas dataframes, enabling easy manipulation and analysis.
- Data cleaning operations are performed to handle missing or inconsistent values, ensuring the data is in a suitable format for analysis.
- Additional data transformations may be applied, such as converting categorical variables into numerical representations.

### Data Modeling:
- The preprocessed dataframes are converted to CSV files for further modeling.
- Power Query is used for data transformation, merging, and filtering, to create refined datasets.
- DAX (Data Analysis Expressions) is employed in Power BI to perform advanced calculations, define relationships between tables, and create measures and calculations for the desired predictive models.

By following this data collection, preprocessing, and modeling pipeline, the Women's Premier League Dream 11 Predictor project ensures that the collected data is transformed into a suitable format for analysis and prediction. This empowers users to make informed decisions while selecting their dream teams for the WPL.
## Technologies Used

- Python 3
- BeautifulSoup (bs4)
- Pandas
- NumPy
- Data Modeling 
- Power Query
- DAX
- Power BI

## Methodology

- Data collection and cleaning
- Exploratory data analysis
- Feature engineering
- Model selection and training
- Model evaluation and validation

## Dashboard

### Player Performance Evaluation: 
- I have conducted comprehensive analyses of individual player performances throughout the tournament, evaluating batting averages, strike rates, bowling economy, wicket-taking abilities, and fielding efficiencies. These insights help teams identify standout performers, identify areas for improvement, and make informed decisions when it comes to team selection and player roles.

### Team Strategy Optimization: 
- By analyzing team performance metrics, such as run rates, partnerships, bowling variations, and fielding strategies, I have identified winning patterns and strategies employed by successful teams in the WPL 2023. Teams can leverage these insights to optimize their game plans, devise effective batting and bowling strategies, and enhance their chances of success in future tournaments.

### Data Visualization for Enhanced Understanding: 
- I have employed visually appealing and intuitive dashboards to present complex cricket analytics in a user-friendly manner. These interactive visualizations enable coaches, players, and analysts to grasp key trends and performance patterns at a glance, facilitating data-driven decision-making processes and enhancing communication within the team.

