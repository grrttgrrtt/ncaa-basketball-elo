# ncaa-basketball-elo
NCAA Basketball Elo Analysis

This began as a school project, and may (hopefully) mature into a system that my friend can use to make overall winning bets on ncaa basketball games.

The system uses the chess rating system to rank teams (Nate Silver on www.fivethirtyeight.com does similar stuff). It builds a database of matchups and records differences in rating, odds set by oddsmakers, and the actual result of the game. This database can then be analyzed to look for patterns (lopsided matchups, close matchups, etc.) and make predictions about teams covering their respective spreads.

In addition to overall Elo ratings, this systems is capable of tracking Elo scores for more precise statistics, like 3-point shooting, offensive/defensive rebounding, etc.

Future Plans:
I would very much like to implement some kind of roster awareness so that the impact of individual players can be tracked. Furthermore, I would like to use the Elo ratings for shooting percentage, turnover, rebounding, etc. to build monte-carlo style game simulations to build winning percentages/probable score distributions.
