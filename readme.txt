META CRITIC SCORES
https://www.kaggle.com/datasets/brunovr/metacritic-videogames-data
name: The name of the game
platform: Platform it was released
r-date: date it was released
score: average score given by critics (metascore)
user score: average score given by users in the website
developer: game developer
genre: genre of the game (can be multiple)
players: Number of players (some games don't have this information)
critics: number of critics reviewing the game
users: Number of metacritic users that reviewed the game


Video Games Sales Dataset
https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset/data?select=Video_Games_Sales_as_at_22_Dec_2016.csv

STEPS. 
1. Column name for ['platforms','name'] for both set match 
2. "platform" unique values matched
3. Remove r-data, developer, players,
4. Merge scores to sales using "game name" & "platform"