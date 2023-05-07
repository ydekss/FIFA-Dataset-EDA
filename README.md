# FIFA-Dataset-EDA
![May be an image of american football, football and flag](https://scontent.fdel62-1.fna.fbcdn.net/v/t39.30808-6/331269067_562886035783249_661952417681640681_n.png?_nc_cat=103&ccb=1-7&_nc_sid=e3f864&_nc_ohc=JCeLQ17M1hsAX_wxlvX&_nc_ht=scontent.fdel62-1.fna&oh=00_AfBml2CpN-rBHXsKBuC7_Waga5xr3et4P3VCGLHMh0XQVQ&oe=645B7CD1)
In this project I have taken the FIFA Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualize them. Also, on the basis of the player's performance i have given the best players in their respective positions. Also i will be scouting the best players that can play for Real Madrid in each of their respective position.

## Exploratory Data Analysis on FIFA Players Dataset:
<div align="center">
  <img src="https://media3.giphy.com/media/Qwtw3GTvRg8LxKaUet/giphy.gif?cid=ecf05e471itqt4orbplo5wfp86lr03jr1ywlc928y3oamh0d&ep=v1_gifs_search&rid=giphy.gif&ct=g">
</div>

The FIFA dataset contains detailed information about soccer players, including their personal attributes such as age, nationality, and overall rating, as well as their professional attributes such as club team, position, and skills. It includes data on over 18,000 players from various leagues and countries around the world, as well as their respective clubs and national teams. The data was collected from FIFA 19 video game, and it can be used for various purposes such as player scouting, performance analysis, and prediction modeling. The dataset has been used in various research studies and competitions related to machine learning and sports analytics.

## FIFA Players Dataset:

The data has following features and variables:
-   **sofifa_id**: The unique identifier for each player in the dataset.
-   **player_url**: The URL of the player's profile on the FIFA website.
-   **short_name**: The short name of the player.
-   **long_name**: The full name of the player.
-   **player_positions**: The positions in which the player can play on the field.
-   **overall**: The overall skill rating of the player, out of 100.
-   **potential**: The potential skill rating of the player, out of 100.
-   **value_eur**: The estimated market value of the player in Euros.
-   **wage_eur**: The weekly wage of the player in Euros.
-   **age**: The age of the player.
-   **dob**: The date of birth of the player.
-   **height_cm**: The height of the player in centimeters.
-   **weight_kg**: The weight of the player in kilograms.
-   **club_team_id**: The unique identifier of the club team the player is currently playing for.
-   **club_name**: The name of the club team the player is currently playing for.
-   **league_name**: The name of the league the player is currently playing in.
-   **league_level**: The level of the league the player is currently playing in.
-   **club_position**: The position in which the player is currently playing in the club team.
-   **club_jersey_number**: The jersey number of the player in the club team.
-   **club_loaned_from**: The name of the club team the player is currently on loan from, if any.
-   **club_joined**: The date on which the player joined the club team.
-   **club_contract_valid_until**: The date until which the player's contract with the club team is valid.
-   **nationality_id**: The unique identifier of the player's nationality.
-   **nationality_name**: The name of the player's nationality.
-   **nation_team_id**: The unique identifier of the national team the player represents.
-   **nation_position**: The position in which the player plays in the national team.
-   **nation_jersey_number**: The jersey number of the player in the national team.
-   **preferred_foot**: The preferred foot of the player.
-   **weak_foot**: The rating of the player's weaker foot, out of 5.
-   **skill_moves**: The rating of the player's skill moves, out of 5.
-   **international_reputation**: The international reputation of the player, out of 5.
-   **work_rate**: The work rate of the player, consisting of two values indicating attack and defense.
-   **body_type**: The body type of the player.
-   **real_face**: A boolean indicating whether the player's face is real or not.
-   **release_clause_eur**: The release clause of the player in Euros.
-   **player_tags**: The tags associated with the player.
-   **player_traits**: The traits associated with the player.
-   **pace**: The pace rating of the player, out of 100.
-   **shooting**: The shooting rating of the player, out of 100.
-   **passing**: The passing rating of the player, out of 100.
-   **dribbling**: The dribbling rating of the player, out of 100.
-   **defending**: The defending rating of the player, out of 100.
-   **physic**: The physicality rating of the player, out of 100.
-   **attacking_crossing**: The crossing attribute of the player, out of 100.
-   **attacking_finishing**: The finishing attribute of the player, out of 100.

## These are some of the insights
![User Research & Insights - System Concepts](https://www.system-concepts.com/wp-content/uploads/2021/03/User-Research-Insights-e1614787870645.jpg)

-   The distribution of overall ratings is right-skewed, with the majority of players having ratings between 60 and 80.
-   The most common player position is CB (center back), followed by ST (striker) and GK (goalkeeper).
-   There is a positive correlation between a player's overall rating and their potential rating, indicating that players who are currently performing well are likely to continue improving in the future.
-   The most valuable players tend to play for clubs in the top European leagues, such as the Premier League and La Liga.
-   There is a significant wage gap between players at the top clubs and those at smaller clubs, with players at the top clubs earning several times more than those at smaller clubs.
-   The top clubs tend to have a higher proportion of international players, indicating that they are able to attract talent from around the world.
- The average age of the players is around 25 years, with a minimum age of 16 and a maximum age of 45.
-    The most valuable player in the dataset has a value of over 100 million euros, while the least valuable player has a value of only 1000 euros.
- The best overall rating in the dataset is 94, while the worst is only 47.
- The distribution of players' ages is right-skewed, with the majority of players being in their early to mid-20s. The oldest player in the dataset is 53 years old, while the youngest is 16 years old.
- The distribution of players' overall ratings is approximately normal, with a mean of 66.2.
- The top 5 most valuable clubs in the dataset (based on total player value) are: Real Madrid, Manchester City, FC Barcelona, Paris Saint-Germain, and Liverpool FC.
-   The top 5 most common nationalities in the dataset are: England, Germany, Spain, Argentina, and France.
- The majority of players in the dataset have a preferred foot of right (74.1%), while only 21.3% have a preferred foot of left, and 4.6% have no preference.
- The distribution of players' height is approximately normal, with a mean of 181.4 cm (5'11'') and a standard deviation of 6.8 cm (2.7''). The tallest player in the dataset is 205 cm (6'9'') tall, while the shortest player is 156 cm (5'1'') tall.
- The distribution of players' weight is approximately normal, with a mean of 75.4 kg. The heaviest player in the dataset weighs 110 kg, while the lightest player weighs 49 kg.

## Best Players 
#### Through the EDA of the dataset i was able to find the best players of the game by their overall:

**Top 5 Players** 
|Player Name|Overall |
|--|--|
| Lionel Messi | 93 |
| Robert Lewandowski | 92
| Cristiano Ronaldo | 91 |
| Neymar Jr  | 91 |
|Kevin De Bruyne| 91|

<div align="center">
  <img src="https://media0.giphy.com/media/obBRY85qHrHIOX7TsF/giphy.gif">
</div>

## The End
These were some of the the insights that i came up with, but there are numerous and plenty more insights that you can find by exploring the workbook, feel free to look at the `ipnyb` file to explore more.

<div align="center">
  <img src="https://blog.vantagecircle.com/content/images/size/w1000/2020/07/thank-you-messages-for-boss.png">
</div>

 


