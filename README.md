# IPL 2008-2019 EDA
![](https://github.com/SDS7695/Images/blob/master/IPL_2019.jpg)


# Introduction

IPL(Indian Premier League) is a tournament where players from all around the world come and take part in world's largest cricket league. More the number of players, more the data is and hence this dataset was chosen for the Analysis.

# Problem Statement

There were number of questions answered during the analysis which are present in the notebook 

# Dataset Description

Two datasets were available for data analysis:

**matches.csv** : This file contains the details of each match played in IPL from 2008 to 2019

| Variable          |                     Definition                            |
| ----------------- | --------------------------------------------------------- |
| id	              | Unique match id                  |
| city       |	Venue of the match                         |
| team1       |	first team of the match                           |
| team2       |	second team of the match                                  |
| toss_winner      | team who won the toss                  |
| toss_decision      |	Decision taken by captain after winning the toss                         |
| result       |	                           |
| dl_applied       | Was Duckworth Louis method applied for deciding winner (0-No, 1-Yes)                                  |
| winner              | winner of the match                  |
| win_by_runs      |	Win margin in terms of runs                       |
| win_by_wickets |	Win margin in terms of wickets                     |
| player_of_the match       |	Man of the match                                  |
| venue            | Venue f the match                  |
| Umpire1      |	Field Umpire 1 |
| Umpire2 |	Field Umpire 2 |
| Umpire 3       |	T.V. Umpire 3 |

**deliveries.csv** : This file contains the details of each ball bowled in IPL from 2008 to 2019

| Variable          |                     Definition                            |
| ----------------- | --------------------------------------------------------- |
| match_id	              | Unique match id                  |
| inning     |	Inning of the match                         |
| batting_team      |	Team batting in the inning                          |
| bowling_team |	team bowling in the inning                            |
| over      | over of the match                 |
| ball      | ball of the over                         |
| batsman       |	 batsman facing the ball               |
| non_striker      | batsman at the non-striker end                                  |
| bowler              | bowler          |
| is_super_over     |	Over is super over or not(0-No, 1-Yes)                       |
| wide_runs |	Runs scored in the ball as wide                     |
| bye_runs       |	Runs scored in the ball as Byes                     |
| legbye_runs          | Runs scored in the ball as Leg Byes                  |
| noball_runs     |	Runs scored in the ball as No Ball |
| penalty_runs |	Runs scored in the ball as penalty |
| batsman_runs       |	Runs scored in the ball by the batsman  |
| extra_runs | total extra runs score in the ball |
| total_runs | total runs scored in the ball of the match |
| player_dismissed | Whether the batsman was dismissed by bowler or not (0-No, 1-Yes) |
| dismissial_kind | How was the player dismissed in the ball |
| fielder | fielder involved in the batsman dismissal |  
