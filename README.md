# EPL-2020-2021
Analysis of the 2020-2021 Premier League

Overview

	This is a EDA of the 2020-2021 Premier League season. Data has been captured by the Fantasy premier legaue API - 'https://fantasy.premierleague.com/api/bootstrap-static/' and player data has been captured from API - https://fantasy.premierleague.com/api/element-summary/.



Motivation

	With the pandemic going on, i took an intererst in data analysis and decided to learn modules like pandas,matplotlib,seaborn and even Machine learning and nothing better than to use it in something im addicted to - 'FOOTBALL'.




Data

	1)FPL_2020-2021_agg_stats.xlsx - consists aggregate data of stats for each player throughout season

	2)FPL_2020-2021_weekly_stats.xlsx - consists of weekly data of stats for each player throughout season	





Feature definitions

FPL_2020-2021_agg_stats.xlsx

	1) team = team id (1='Arsenal',2='Aston Villa',3='Brighton',4='Burnley',5='Chelsea',6='Crystal Palace',7='Everton',8='Fulham',9='Leeds',10='Leicester',11='Liverpool',12='Man City',13='Man Utd',14='Newcastle',15='Sheffield Utd',16='Southampton',17='Spurs',18='West Brom',19='West Ham',20='Wolves' 
	
	2) id = Player id
	
	3) first_name , second_name , web_name = Name of player
	
	4) element_type = player position (1='GK',2='DEF',3='MID',4='FWD')
	
	5) minutes - No. of minutes played this season
	
	6) goals_scored = Goals scored this season
	
	7) Assists = Assists this season
	
	8) Clean_sheets = Clean sheets this season
	
	9) goals_conceded = goals conceded this season
   
    10) penalties_missed = Penalties missed this season
   
    11) penalties_saved = Penalties saved this season
   
    12) own_goals = own goals this season
   
    13) yellow_cards = yellow cards this season
   
    14) red_cards = red cards this season
   
    15) now_cost = FPL price as of end of season
   
    16) influence =  Metric that evaluates the degree to which that player has made an impact on a single match or throughout the season.
   
    17) creativity = Metric that assesses player performance in terms of producing goalscoring opportunities for others. It can be used as a guide to identify the players most likely to supply assists.
   
    18) threat = Metric that examines a player's threat on goal. It gauges individuals most likely to score goals
   
    19) ict_index = Metric created from influence , creatvity and threat
   
    20) status = status of the player ('a' - available ,'u' - unavailable (left league/on loan out of league) ,'d' - doubtful , 'i' - injured , 's' - suspended , 'n' - not eligible(to play parents club when on loan))
   
    21) bps = bonus points system
   




FPL_2020-2021_weekly_stats.xlsx
	
	1)element - player_id (same as id in FPL_2020-2021_agg_stats.xlsx)
	
	2)round - gameweek number

	3)was_home - if game was at home(Boolean)

	4)team_h_score - Home team score

	5)team_a_score - Away team score
	
	Other columns are same as the ones in FPL_2020-2021_agg_stats.xlsx