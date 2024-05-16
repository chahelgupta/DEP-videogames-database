# Video Game Sales with Ratings Data Extraction and Processing

## About the Dataset

- **Dataset Title**: Video Game Sales with Ratings
- **URL for Dataset Download**: [Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings/data)

The "Video Game Sales with Ratings" dataset is a comprehensive collection of information related to video games. It includes details about various aspects of each video game, such as sales figures in different regions, ratings from both critics and users, information about the development of the games, and their ESRB ratings. This dataset is valuable for exploring and analyzing trends in the video game industry, understanding how various factors influence game sales and ratings, and gaining insights into the relationships between critic and user reviews and sales performance. It can be used for data exploration, preprocessing, and visualization to uncover valuable information about the video game market.

## Data Exploration

### Libraries Used:
- NumPy (np)
- Pandas (pd)
- Seaborn (sns)
- Matplotlib.pyplot (plt)

### Key Steps:
- Read the CSV file into a Pandas DataFrame.
- Checked the dimensions and data types of the DataFrame.
- Provided summary information about the DataFrame.
- Displayed the first 10 and last 5 rows of the DataFrame.
- Retrieved column names and unique values from specific columns.
- Checked for null values and data types in each column.
- Provided descriptive statistics for numerical columns.

## Data Pre-Processing

### Steps Taken:
- Created a copy of the original data to preserve it.
- Dropped rows with null values in 'Name' and 'Genre' columns.
- Removed duplicate entries based on the combination of 'Name' and 'Platform'.
- Converted 'User_Score' to float and standardized it.
- Handled missing values in 'User_Count' and 'Critic_Count' columns by filling them with mean values.
- Dropped columns deemed irrelevant for analysis ('Rating' and 'Publisher').
- Ignored null values in the 'Developer' column.

## Data Visualization

### Key Visualizations:
- Number of Games Released Each Year
- Most Used Platforms for Video Games
- Most Played Game Genres
- Distribution of Ratings Among Games
- Top 10 Developers
- Game Sales of Different Genres in Various Regions
- Heatmap on Global Sales with Different Genre and Platform

## Conclusion

The data extraction and processing involved thorough exploration, preprocessing, and visualization of the "Video Game Sales with Ratings" dataset. Null values were handled, duplicate entries were removed, and relevant columns were selected for analysis. Visualizations provided insights into trends such as the number of games released over the years, popular platforms and genres, distribution of ratings, top developers, and regional sales dynamics. This comprehensive analysis enhances our understanding of the video game market and lays the foundation for further exploration and insights.
