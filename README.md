# Videogame-sales-data
this project was completed to show the best years in gaming history. This project was completed to show data manipulation in SQL using postgre, and jupyter notebooks. we found that 2008 was the greatest year in gaming history based upon user and critic scores as well as total game sales. data taken and used from kaggle data resources.

Below are the tables and columns used in the project

game_sales

game	varchar	
platform	varchar
publisher	varchar
developer	varchar	
games_sold	float	
year	integer	

reviews

game	varchar
critic_score	float
user_score	float	


top_critic_years_more_than_four_games

year	int	Year of video game release
num_games	int	
avg_critic_score	float


top_user_years_more_than_four_games

year	int	Year of video game release
num_games	int	
avg_user_score	float
