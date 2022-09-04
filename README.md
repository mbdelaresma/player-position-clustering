# Scouting the EPL: Player Clusters in the English Premier League

Data Mining and Wrangling Course Submission

See full report [HERE](https://github.com/mbdelaresma/player-position-clustering/blob/main/FinalReport.ipynb)

![image](https://user-images.githubusercontent.com/71246479/188297372-d7b2f86e-cd44-4ca8-944b-98d073334fad.png)

# Executive Summary

With close to four billion fans around the world, football has become a worldwide phenomenon. Competition has been topnotch as leagues have been investing heavily in their players and their programs. The English Premier League is one of the top-tier leagues that boasts of having the best players in the world. Acquisitions and transfers are common in the world of football since all teams want to ramp up their chances of winning the coveted title. The quality and diversity of players have also improved in recent years, signalling better inclusion and a higher caliber of players. With the recent digital age, teams and leagues now have means to gather information on player statistics. Websites such as FBREF.com are good examples of legitimate sources of game data.

In this technical paper, our group analyzed various player and game statistics from FBREF.com. Data was extracted using manual webscraping, stored in a database, cleaned, and normalized. The data was divided into two dataframes; one for numerical statistics and the other for information like team, name, and positions. The first dataframe was used for dimensionality reduction and clustering while the latter was utilized for data exploration and analysis. Principal Component Analysis was performed to determine the correlation between features and to reduce the number of dimensions. Clustering was then executed via Ward's method of clustering. The team identified twelve new clusters; four unique clusters for each playing position. For Forwards, there are All-Around Forwards, Natural forwards, Aerial Forwards, and Defensive-Minded Forwards. For Midfielders, there are Utility Midfielders, Wide Midfielders, Holding Midfielders, and Attacking Midfielders. Finally, for Defenders, there are the Wing Backs, Full Backs, Ball-Playing Defenders, and Ball-Winning Defenders. The newly-formed clusters can be utilized by sports teams, coaches, managers, analysts, scouts, and fans for scouting, acquisitions, competition, and research.

This paper features data for players and statistics only in the 2020-2021 season of the English Premier League. We recommend future researchers to expand the scope of player statistics and go beyond the last football season. We suggest that they cover football leagues beyond the English Premier League such as the Italian Serie A, the Spanish La Liga, the FIFA World Cup, and even the Olympics. We also encourage future proponents to delve into more advanced data science techniques such as machine learning models so as to span more ground with their study and investigation. Finally, we recommend exploring other clustering methods and possibly looking into soft clusters for deeper analysis, relevant insights, and timely recommendations

# Contributors

dela Resma, Marvee

Punzalan, Paolo
