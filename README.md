This is my first project using BOTH excel and tableau.

After Joel Embiid's lack of productivity and shenanigans, I decided it would be fun to find a replacement center.
Similar to looking at undervalued stocks, I looked for undervalued players based on a few metrics.

Here are some of the metrics I find useful in finding efficent and underrated players:
1. True Shooting Percentage (TSP): Tells us how offensively skilled a player is.
   - TS% = (Tot Pts) / (2*(FGA + 0.44 * FTA))
      > PTS = Points Scored
      > FGA = field goal attempts
      > TA = free throw attempts
2. Points Per 100 Possessions (PPP): Measures how efficiently a player scores per 100 possessions > This can reveal high-impact scorers who don’t take a lot of shots.
   - PPP = Points Scored / Possessions Used
3. Usage Rate (USG%): Shows how much of the team’s plays a player is involved in when they are on the court. A low usage rate with high efficiency could indicate an underrated player.
   - USG% = (FGA+0.44×FTA+TOV)×Team Minutes) / ​Player Minutes×(Team FGA+0.44×Team FTA+Team TOV)
4. Assist-to-Turnover Ratio (A/T): Evaluates a player’s playmaking efficiency. Players with high A/T ratios often go unnoticed in traditional stats.
5. Defensive Box Plus-Minus (DBPM): Assesses a player’s impact on defense compared to an average player. Underrated players often excel here.
6. Defensive Win Shares (DWS): Estimates the number of wins a player contributes to the team via defense.
7. Total Rebound Percentage (TRB%): Measures the percentage of available rebounds a player grabs while on the court.
8. Player Efficiency Rating (PER): Comprehensive metric that factors in all positive contributions and subtracts negatives, adjusted for pace.
9. Value Over Replacement Player (VORP): Estimates the value a player adds compared to a replacement-level player. Players with high VORP but low visibility can be underrated.
10. Win Shares Per 48 Minutes (WS/48): Calculates a player’s contribution to team wins per 48 minutes. Higher WS/48 often correlates with underrated players
11. Effective Field Goal Percentage (eFG%): Adjusts FG% to account for the added value of three-pointers.
12. Free Throw Rate (FTr): Shows how often a player gets to the line relative to shot attempts. High FTr can indicate efficient scoring.

Steps:
1. Export data from Basketball Reference and Import into Excel
2. Clean data and create custom filter (using conditional formating, VLookup, etc)
3. Create Visualization on Tableau

Data Source: The statistics are from Basketball Reference > https://www.basketball-reference.com/ 
