# league-of-legends-analysis
### What is this?
Me and @nathanmargni did a small analysis on what are the best strategies to win more games of League of Legends. Using a dataset found on Kaggle (this one: https://www.kaggle.com/datasnaek/league-of-legends). We explored the data and produced some visualizations in Tableau.

### But, what did we discover?
Based on the dataset, that included data for the 9th season of LoL (meaning 2018), we found out that the best strategy is to first look what are the champions with the highest win/lose ratio, and compare this choice with the pick and ban ratio. We also looked into the win rate based on the various objectives of the game.
There are 6 main objetives:
* First Blood
* First Tower
* First Rift Herald
* First Dragon
* First Baron
* First Inhibitor

For those who already plays the game, they already know that being the first team to destroy the enemy inhibitor is a won game (even if there are some exceptions), but this may be not obvious for everyone!
Since **First Tower** and **First Blood** are the first objectives that you can achieve as soon as the game starts, and giving you a nice *60+%* of win probability (meaning that if you are the firs one to kill an enemy champion, you gain a 10.3% probability of winning the game), we concluded that those are the ones you should aim at the start of the match. 
Obviously once the match is starting to shift towards end-game, you and your team should try to push the enemy team in order to arrive at their inhibitors, destroy them and winning the game.

**Short disclaimer:** quite clearly these are not the rules to follow, we are just presenting our findings of this dataset.

# Sources
Kaggle dataset link: https://www.kaggle.com/datasnaek/league-of-legends
Author of the dataset: Mitchell J, Github: https://github.com/mitchelljy, website: https://mitchelljolly.com/
