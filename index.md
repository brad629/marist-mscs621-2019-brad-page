## Welcome to lol summoner lookup

 "lol summoner lookup" allows players of Riot Games' League of Legends to use their 
summoner name (In Game Name) to search and view their recent match history.

lol summoner lookup provides an easy way to check recent league of legends match history and statistics. since the application is browser based users can check their game history on the go, without installing the league of legends client.

### application overview

```markdown
The application consists of two parts:
 - web application
 - mongo database 

The web application is a python-flask server running on IBM's LinuxOne Community Cloud in a RedHat 
Enterprise Linux server v7.6 
- http://148.100.245.209:32000/home


The mongo databaseis running on an EC2 AWS linux image. 
- http://18.222.17.121:27017/

Users can navigate to the website and input a valid summoner name to gather recent league of legends match statistics.

   If the user is found in the database, stored information is returned.

   If the user is not yet in the database the webserver performs API queries to Riot Games API - 
   https://developer.riotgames.com/apis


```

For more details see [GitHub Readme](https://github.com/brad629/marist-mscs621-2019-bradhuntington).



### Support or Contact

Having trouble with accessing the flask server? Please reachout to me at brh6291994@gmail.com
