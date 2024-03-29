----

title: Predicting the 2024 NBA champions
authors: Adalo Gusa
subtitle: NCSSM Open Source J-term project
date: 2024/01/23
    


----

 


With each year the NBA brings new and exciting basketball content to basketball fans around the world. Each of the 30 teams battle each other for the chance at an NBA championship title. By the end of the regular season, only the top 8 teams in each conference advance to the playoffs. The goal of this project is to use stats and advanced data from the regular season so far to predict who will win the chip this year. Although we are only halfway through the season, there is already plenty of data that we can use to determine who will win it all. When researching the most important stats that a team needs to win games I used which nba statistics translate to wins by Chinmay Vaidya to determine which stats I would look at  My goal is to continuously update the data as the season goes on so that at the end of the regular season there is a clear champion. This data will not take into account the possibility of injuries that may impact season outcomes. 

## Background
To start off analyzing the data, I had to isolate the contending teams. Each year the top 8 teams make it to the playoffs. The top 6 ranked teams in each conference automatically make it to the playoffs. However, the 7th-10th ranked teams have to battle it out in the play-in tournament. The results of this decide which 2 teams make became the 7th and 8th seed in the playoffs. Last year the number 10th ranked team the miami heat were able to win their playin game and make it all the way to the NBA finals, so we can never count the play in teams out. 


This data does show how much better the championship contenders are then the play in contenders.Right now the Boston celtics currently have the best win percentage in the NBA winning 76.2 percent of their games so far. After around the top 5 teams the in percentage begins to drop drastically. The worst play in contender team has a win percentage of just 42.9% meaning they have a losing record. 

![](#my-cell)

## Betting odds

An interesting way I decided to look at who people think are going to win the NBA title is by looking at betting odds. Using an equation that I found online we can use betting odds to turn into percentages for who NBA fans thnk will win the championship. The equation is listed below.

```{math}
:label: my-equation
percentage = (100/ +number + 100) * 100 
```
We can see that the Boston celtics are the overwhelming favorite with 26% of fans believing they will win it all. The celtics are followed by the Denver Nuggets, who were the 2023 NBA champions, with 20%.  The Miuakee bucks are the last obvious pick with 17%. The rest of the teams on this list are still champion contenders. 

## Offesive and Defensive Rating

Lets return back to actual data obtained from nba.com. The Offensive and Defensive ratings stat is one of the most significant stats as it shows how many points the offensive is scoring and how many points the defense is giving up each game. I isolated 4 championship contenders, 2 from each conference, to compare ratings. We can see that the milwaukee bucks have the highest offensive rating with 120.7. They are closely followed by the boston celtics with 120.3. The Minesota timberwolves have the best defensive rating with 108.5, and once again the celtics closely follow with 110.6. Based on these charts we cna conclude the Boston celtics have a great balance of both offensive and defense that is contributing to their extremely high win percentage as the number 1 ranked team. 

## Field Goal Percentage

The last factor I am currently looking at is FG%. Certain teams might put up more shots then others, but if their percentages can make or break them. With the same 4 contenders as above we can see that their FG%, 3P%, and FT% are all extremely similar. To determine who has the greatest percentage of shots we can look at True shoooting percentage. The miluake bucks and the Oklahoma city thunder are tied for the highest TS% with 61.5. But like always, the Boston celtics are not far off with their 60.1 TS%.




## Conclusion

Halfway through the season  I think it is safe to conclude that the Boston celtics have the highest chance of becoming the 2024 NBA champions. They have the best record, a great mix of players with team chemistry, and advanced stats that are neck and neck with the best team in that category. Since this is only walfway through the season, injuries to stars like Jayson Tatum could derail their season. But, as of now the Celtics only need to continue this level of play and they will win it all this year.


## References

https://www.espn.com/nba/futures

https://watchstadium.com/which-nba-statistics-actually-translate-to-wins-07-13-2019/

https://www.nba.com/stats/teams/traditional

https://www.nba.com/standings

https://www.nba.com/stats/teams/advanced


