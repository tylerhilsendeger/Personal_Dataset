# MLB Through the Years


## Motivation
Ever since I can remember, baseball has always been my life. I have been a fan since I could understand the game, and a player since I could grip a bat. I am far from the only kid like this in America, though. Baseball has ran through the blood of Americans since the late 1800's. Over the course of this time, the game has evolved time and time again, creating some very clear trends in player statistics. Living in the time we do now, it is no seceret that pretty much every player is trying to hit a home run most times they are at bat. Has it always been like this, though? How has the game really shifted throughout the last roughly 150 years? There are definitely trends to be found, and my goal was to illustrate how the offensive goals of baseball have shifted since the early days of the game.

# Data Source
I gathered all of my data from the statistics database, [Baseball Reference](https://www.baseball-reference.com/). This website has a complete library of every player in the history of the league, along with their game by game stats and their career stats. The team statistics are also available on this site for every team in the leagues history. They make it really easy to export the data from their website, as I just copied the stats as a .csv file and used excell to view and clean it. For this project, I downloaded the career statistics for 4 players who were considered "the best" during different eras of the game, Rogers Hornsby, Ted Williams, Barry Bonds, and Ken Griffey Junior.

# Processing Steps
This data did not require very much processing/cleaning to make it useful. As I mentioned above, it was very simple to acquire the data from Baseball Reference's website, and it comes as a organized .csv file. There were some columns of data included in the data sets that were unnecessary, so i removed them from the data. These columns were the "Team", "League", and the "Pos" (Position) columns. These were removed because they are unrelated to the question I was trying to answer and overcomplicated the dataset. I also removed some of the rows included that showed the career totals for each stat and the totals for each team that player was on. I removed these because while they are related to the question, I was interested in per year values, rather than career totals so they didnt help my research. The last processing step that I made was adding columns for "WAR" (Wins above replacement) and "RAR" (runs above replacement). These were not included in the original datasets that i downloaded, but they were included in a different one that each player had on Baseball Reference. I chose to add these values to my data because they are a good measure of how valuable the player really is compared to an average player.

# Visualization
![](https://github.com/tylerhilsendeger/Personal_Dataset/blob/master/Images/HvsHR.png?raw=true) 
This graph is a representation of how homeruns became more popular in the MLB throughout the history of baseball, with a peak in the 1990's aka the "steroid era". It shows the correltion between hits(x-axis) and homeruns(y-axis) for four different players throughout their careers. The first player, and the one who had the least strong correlation between hits and homeruns, is Rogers Hornsby. He played from 1915 to 1937, and won two MVP awards. The next player with a slightly stronger correlation is Ted Williams. He is often reffered to as the best hitter ever, and he also won two MVP awards from 1939 to 1960. The third player is Barry Bonds. He is undoubtably the best hitter of the 1990's, a seven time MVP, and the player shown with the highest correlation between his hits and home runs. He was also one of the many stars of that era caught using steroids and is forbidden from joining the hall of fame because of it. The last player, and the one whose hits led to the second most home runs of the players shown, is named Ken Griffey Junior. He played from 1989 to 2010, and represents the trend of home runs being hit slightly less often after the steroid era.

![](https://github.com/tylerhilsendeger/Personal_Dataset/blob/master/Images/HRperSZN.png?raw=true)
This box plot is a visualization of each players amount of home runs hit per season. Each player's box represents the five mumber summarry of their seasonal home run totals. Rogers Hornsby, who played during an era where home runs were very hard to come by, hit the least amount of home runs per year. Ted Williams, who played after Hornsby, hit almost 20 more home runs than him every year. Barry Bonds had a higher average than Williams, however his lower extreme and first quartile values are lower than Williams'. This can be attributed to the years earlier in his career before he started using steroids. He also had an outlier that I chose to keep in the data because it represents his record setting year when he hit 73 home runs. Ken Griffey Junior had lower values for all five components of the box plot than Bonds did, which is to be expected and represents the entire league beginning to hit less home runs with more strich PED rules.

# Description of Code and Materials
The visualizations of this data can be found in the [Images](https://github.com/tylerhilsendeger/Personal_Dataset/tree/master/Images) folder. The raw data downloaded as a .csv from Baseball Reference is located in the [RawData](https://github.com/tylerhilsendeger/Personal_Dataset/tree/master/RawData) folder. I applied some processing steps to each of the players' data sets to get a workable spreadsheet. These final data sets can be found in the [ProcessedData](https://github.com/tylerhilsendeger/Personal_Dataset/tree/master/ProcessedData) folder.

# References
