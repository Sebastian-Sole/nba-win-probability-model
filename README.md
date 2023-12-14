# NBA Win Probability Model 🏀
This is a jupyter notebook which calculates the win probability of an nba game based on a play-by-play level.

# Important ❗️
This model fetches data from the [NBA Sportradar API](https://developer.sportradar.com/docs/read/basketball/NBA_v8#nba-api-overview), which requires and API key. 
A free trial for API keys can be found [here](https://developer.sportradar.com/member/register), but note that a free trial key is limited to 1/1000 calls per second/month. 
This notebook fetches data for all games from the 2022 season, and then play-by-play data for all games, totalling in roughly 2460 calls just for data collection (their UI says ~1300 calls). 

# Datasets 📀
As stated above, the data is from the [NBA Sportradar API](https://developer.sportradar.com/docs/read/basketball/NBA_v8#nba-api-overview), which requires and API key, and I do not believe I am legally allowed to publish this data open source, so I won't.

However, the model is trained and tested on 8.5 GB of play-by-play data from all games in the 2022 NBA regular season

# How to Contribute
Create a .env file
```
SPORTRADAR_API_KEY=your-api-key
```
Send me an email if you have any contribution ideas, but do not want to purchase an API key!

# Developer Information 👨‍💻
Developed by [Sebastian Sole](https://github.com/sebastian-sole).

# Technologies and Packages Used 📟
- Python
- Jupyter Notebook
- [tqdm](https://tqdm.github.io/)
- [pandas](https://pandas.pydata.org/)

# State of the Project 🧪
This project is currently a WIP
