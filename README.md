# EDA-of-IPL-Matches
![image.jpg](Images/IPL-Image.jpg)

## INTRODUCTION
The dataset consist of the information about all the matches played between each teams in 11 editions of IPL(2008-2018). Various variables are present in the dataset includes id, season, teams, toss winner, decision, match results, player of the match, venue, umpire 1 , umpire2, umpire3 etc.

It comprises of 696 observation.

## DATA
| Column Name | Description |
| --- | --- |
| `Id` | Numerical Value |
| `Season` | Numerical Value |
| `City` | (Cities where match has played: - 'Hyderabad', 'Pune', 'Rajkot', 'Indore', 'Bangalore', 'Mumbai', 'Kolkata', 'Delhi', 'Chandigarh', 'Kanpur', 'Jaipur', 'Chennai', 'Cape Town', 'Port Elizabeth', 'Durban', 'Centurion', 'East London', 'Johannesburg', 'Kimberley', 'Bloemfontein', 'Ahmedabad', 'Cuttack', 'Nagpur', 'Dharamsala', 'Kochi', 'Visakhapatnam', 'Raipur', 'Ranchi', 'Abu Dhabi', 'Sharjah',' Mohali', 'Bengaluru') |
| `Date` | DATE (on which date match played) |
| `Team`| team1 and team2 are two columns between match played|
| `Toss Winner` | (team name who won the toss) |
| `Toss Decision` | (decision what caption decides after winning the toss) |
| `Result` | (Result of Match whether it’s normal, tie or no result) |
| `DL Applied` | (0=NO, 1=YES) |
| `Winner` | (team name who won the match) |
| `Win by runs` | (by how many runs team won the match) |
| `Win by wickets` | (by how many wickets team won the match) |
| `Player of Match` | (which player contributes more for team) |
| `Venue` | (stadium name where match was played) |
| `Umpire 1` | (umpire 1 name – on ground umpire) |
| `Umpire 2` | (umpire 2 name – on ground umpire) |
| `Umpire 3` | (umpire 3 name – TV umpire) |
## PROJECT ANALYSIS
| Description | Analysis |
| --- | --- |
| ipl_data.head | ![image.png](Images/head1.png) |
| ipl_data.head | ![image.png](Images/head2.png) |
| missing value | ![image.png](Images/miss.png) |
| After replacing missing values | ![image.png](Images/fillmissingvalue.png) |

### Analysis Result
- Performance of each team in 11 IPLs (2008-18) and also found the best player for each team.
- Performance of each team on home ground matches and away matches.
- Performance of team after winning the toss, if they won the toss what they elected batting or fielding.
- Performance of team while batting 1st and bowling 1st.
- Number of matches where decision was taken by DL method
- Saw the results of match whether it's normal, tie(decision was taken bt super over), no result(Match abandon)
- Done year wise performance of each team from 2008-2018.
- Number of teams participated in each year of IPL from 2008-2018.
