# movie_rating
Basic Data Manipulation
movies["fm_diff"] = movies["Fandango_Stars"] - movies["Metacritic_norm_round"]
 
from numpy import abs 
movies["fm_diff"] = abs(movies["fm_diff"])
