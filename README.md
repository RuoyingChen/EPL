# EPL
Problem Statement
The purpose of this project is to figure out the effectiveness of player’s personal stats, and its impact on game result. By calculating the average goals of each team’s starting lineup, we should be able to make a prediction of the game result.
Data Description
All the data are retrieved from http://www.espn.com/soccer/league/_/name/eng.1/
Name: Name	APP: Appearances	FC: Fouls Committed
POS: Position	SUBIN: Substitute Appearances	FA: Fouls Suffered
Age: Age	G: Total Goals	YC: Yellow Cards
HT: Height	A: Assists	RC: Red Cards
WT: Weight	SH: Shots	S: Saves
NAT: Nationality	ST: Shots on Target	GC: Goals Conceded
Methodology
First, calculate the average goals for each starting lineup player in current season, then calculate the average goals of 11 lineup players’ personal stats. By comparing the result for both teams, we can make a prediction of the game.
Result
I chose the game between Chelsea and Watford in May 5th as a test. Based on the calculation, the average goals for Chelsea’s starting lineup is 0.131, and the average goals for Watford’s starting lineup is 0.112. The actual result of the game is Chelsea beat Watford with 3:0.
Conclusion
In this particular test sample, the project did accurately predict the result. 
