----

title: Predicting the 2024 NBA Champions
authors: Adalo Gusa
subtitle: NCSSM Open Source J-term project
date: 2024/01/23
    


----

 
## Background
With each year the NBA brings new and exciting basketball content to basketball fans around the world. Each of the 30 teams battle each other for the chance at an NBA championship title. By the end of the regular season, only the top 8 teams in each conference advance to the playoffs. The goal of this project is to use stats and advanced data from the regular season so far to predict who will win the chip this year. Although we are only halfway through the season, there is already plenty of data that we can use to determine who will win it all. The stats I will be analyzing are Win Percentage, Offensive and Defensive Rating, Field Goal Percentage, and True Shooting Percentage. These were some of the most important stats determined from a study by Dimitrije [](doi:10.1371/journal.pone.0273427). I decided to also look at a statistic few other people have used which were fan betting odds through ESPN. My goal is to continuously update the data as the season goes on so that at the end of the regular season there is a clear champion. This data will not take into account the possibility of injuries that may impact season outcomes.








## How The Playoffs Work
To start off analyzing the data, we have to isolate the contending teams. Each year the top 8 teams in the Eastern and Western conference make it to the playoffs. These 8 teams play through a tournament bracket of first to 4 series in their respective conference. Eventually, one Eastern and Western conference team face off in the finals. The top 6 ranked teams in each conference automatically make it to the playoffs. However, the addition of the new play-in tournament has the 7th-10th ranked teams in each conference battle it out. The results of the play-in tournament decide which 2 teams become the 7th and 8th seed in the playoffs. Last year the number 10th-ranked team the Miami Heat were able to win their play-in game and make it to the NBA finals, so we can never count the play-in teams out. As of my current data, the 20 teams listed below are the contenders for this year's playoffs.
![](#PlayoffContenders)




The data below shows the same 20 teams in the chart above. It puts into perspective just how much better the championship contenders are than the play-in contenders.  After around the top 5 teams, the percentage begins to drop drastically. Right now, the Boston Celtics currently have the best win percentage in the NBA winning 76.2% of their games so far. The worst play-in contender team, the Atlanta Hawks have a win percentage of just 42.9%, meaning they have a losing record.




![](#WinP)




## Betting Odds




An interesting way I decided to look at who NBA fans think is going to win the NBA title is by looking at betting odds. NBA fans all over the world believe they can win big by using all their NBA expertise to put money into who they think will become champions. Using an equation that I found online we can use betting odds to turn into percentages for who NBA fans think will win the championship. The equation is listed below.




```{math}
:label: my-equation
Percentage = (100/ (Positive Betting Odd + 100)) * 100
```
![](#BettingOdds)
We can see that the Boston Celtics are the overwhelming favorite with 26% of fans believing they will win it all. The Celtics are followed by the Denver Nuggets, who were the 2023 NBA champions, with 20%. The Milwaukee Bucks are the last obvious pick with 17% of bets being placed on them to win it all. Even though the percentages of the remaining teams are lower, they are all still champion contenders. While this data is incredibly skewed by the fan bases that some of these teams have, it is still interesting to look at what someone willing to put some of their money up thinks about the 2024 season.




## Choosing Top Contenders




This season of the NBA has been extremely close between the top 8 ranked teams. To choose who I would take a deeper look at I used some of my own NBA knowledge. There are two teams in the East and West that I will be choosing. For the East, I chose the Boston Celtics and the Milwaukee Bucks. These two teams have great rosters with veteran players as well as stars. Both teams also have a lot of playoff experience, with the Bucks winning the Championship in 2021, and the Celtics reaching the finals in 2022. Deep playoff runs have strengthened the team chemistry among their rosters. The Celtics and Bucks are currently the number 1 and 2 seed in the East. The two teams in the West I chose are the Denver Nuggets and the Minnesota Timberwolves. Both teams have veteran players and stars with great team chemistry. The Minnesota Timberwolves have shocked the NBA fans this year boasting the best record in the West. The Denver Nuggets are the reigning champions from the 2023 season and have a similar record and roster to their team last year. Although the Oklahoma City Thunder have a better record in the west than the Nuggets, they are a young team with little to no playoff experience.




## Field Goal Percentage




![](#ShootingP)
Now that we have our top contenders so far in the 2024 season, let's return to actual data obtained from nba.com. Field Goal percentage is an extremely important stat for every champion contender. Field Goal percentage can be split into three categories. Field Goals (FG) are mid-range shots and lay-ups. 3 point shots are only shots taken behind the 3-point line. Free Throws(FT) are shots awarded for any fouls the defense commits on a shot attempt. While certain teams might put up more shots than others, their shooting percentage can make or break them. With the same 4 contenders as above we can see that their FG%, 3P%, and FT% are all extremely similar.








To determine who has the greatest percentage of shots we can look at True Shooting (TS) Percentage. True Shooting Percentage is a metric that combines all shooting splits into a tangible percentage. It is calculated through the points scored divided by the total field goal attempts multiplied by 0.44 of the free-through attempts. The equation is listed below.
```{math}
:label: my-equation
True Shooting = Points/(FGA(0.44*FTA))
```
![](#TSP)




Once again each of these teams is extremely close with one another. The Milwaukee Bucks have the highest TS% with 61.5%. But like always, the Boston Celtics are not far off with their 60.1 TS%. In the Western Conference, Minnesota has a 59.6% while the reigning champs the Denver Nuggets have a smaller 59.2 TS%. Since all of these teams still have a similar shooting percentage there is one final statistic that is arguably the most important.




## Offensive and Defensive Rating




The Offensive and Defensive rating stat is one of the most significant stats as it shows how many points the offensive is scoring and how many points the defense gives up each game. Great offensive teams like the Milwaukee Bucks often reveal their weakness when it comes to defense. The Bucks have the highest offensive rating with 120.7, however, they have a defensive rating of 166.9. This is where I believe the Boston Celtics shine the most. They only slightly trail the Bucks in Offensive Rating with 120.3, but they destroy the Bucks in terms of their Defensive Rating of 110.6. In the West, the Minnesota Timberwolves have the best defensive rating in the NBA giving up only 108.5 points a game. Still, the Celtics closely follow with 110.6. The Denver Nuggets have a balanced team of offensive and defensive compared to the other top contenders. The main takeaway of these charts is that the Boston Celtics have both an elite defense and offense, contributing to their extremely high win percentage as the number 1 ranked team in the NBA.




![](#OFFDEFRTG)




## Conclusion




Halfway through the season, I think it is safe to conclude that the Boston Celtics have the highest chance of becoming the 2024 NBA champions. The competition is tough, but they have the best record, a great mix of players with team chemistry, and advanced stats that are neck and neck with the best team in that category. On top of this, stars like Jayson Tatum and Jaylen Brown are hungry for their first title after losing to the Golden State Warriors in the 2022 NBA finals. Since this is only halfway through the season, injuries to key players like Jayson Tatum could derail their season. But, as of now the Celtics only need to continue this level of play and they will win it all this year.


## Sources

https://www.espn.com/nba/futures

https://watchstadium.com/which-nba-statistics-actually-translate-to-wins-07-13-2019/

https://www.nba.com/stats/teams/traditional

https://www.nba.com/standings

https://www.nba.com/stats/teams/advanced


https://en.wikipedia.org/wiki/True_shooting_percentage
