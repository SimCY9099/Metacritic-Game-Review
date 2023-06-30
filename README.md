# Data Analysis Project by Excel: Steam Game Dataset

## Goal:
- To evaluate the latest released video games and identify the most popular video games genre.

## Dataset Description:
- The dataset for this project is from Kaggle(https://www.kaggle.com/datasets/gruffgemini/steam-games-dataset). This dataset includes information on about 60000 video games from Steam platform. The dataset provides comprehensive information about various video games available on the Steam platform. Here's a brief overview of the dataset's contents:
  1. id - Game ID on Steam platform.
  2. name - Game Name as appear on Steam platform.
  3. year - Release year of the game
  4. metacritic_rating - Rating from Metacritic(https://www.metacritic.com/game/pc)
  5. reviewer_rating - Game rating given by users on the 0-10 scale (lowest - highest).
  6. positivity_ratio - Number of positive review divided by the number of negative review.
  7. to_beat_main - Time required to beat the main plot of the game.
  8. to_beat_extra - Time required to beat the main and optional objectives of the game.
  9. to_beat_completionist - Time required to complete every single objective of the game including gathering all collectibles.
  10. extra_content_lenght - The difference between completionist time and extra time.

### Data preprocessing:
- Clean the dataset by removing duplicate values. In this dataset, any missing value related to ratings (reviewer_rating) has been change to "NotRated". By assigning "NotRated" to these values, it allows for a consistent representation and ensures that the absence of a rating is clearly indicated in the dataset.
- The dataset has been enhanced with a new column called 'major_type' to facilitate easier analysis and grouping of games based on their major genre or type. This column aims to provide a simplified categorization of games by consolidating the multiple tags or genres associated with each game into a single, more general category.

## Analysis:
### 1. The Growing Trend in the Gaming Industry
- Analyzed the distribution of games released over the years to understand the trend and identify the latest period with the highest number of releases. This highlights the continuous growth and expansion of the gaming industry.

### 2. Game Rating by Year
- The analysis of game ratings by year provides insights into the evolution of the gaming industry in terms of game quality and player satisfaction. It helps identify whether the overall quality of games has improved, remained consistent, or fluctuated over time.

### 3. Review Rating Vs Positivity Ratio
- By analyzing the rating vs. positivity ratio, we can gain insights into how user sentiment and positive reviews align with the overall ratings given to games. This analysis can help determine whether higher positivity ratios contribute to higher ratings, indicating a stronger correlation between positive user feedback and the perceived quality of games.

### 4. Top 10 Excellent Genre
- By identifying the top 10 excellent genres, we can gain insights into the genres that have consistently received high ratings in the excellent category. This analysis highlights the genres that have resonated well with users and are perceived as outstanding in terms of gameplay, quality, and overall experience.
