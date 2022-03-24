# Statcast-TIme-Series-Pitcher-Injury
Personal project using trends in a pitcher's statcast data to predict injury

Injury_History.ipynb creates a dataframe where each row is a player appearance (indexed by player_name, game_date) and contains a column for each type of unique injury where the value is the time from game_date that the injury occured in days. If the player has not had a that type of injury or if the injury occured after game date then the value is None.

Bio_data creates a dataframe where each row is a player appearance (indexed by player_name, game_date) and contains columns for the player's weight, height, and age in days on the date of the appereance.
