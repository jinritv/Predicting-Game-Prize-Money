# Predicting-Game-Prize-Money
Let's predict the prize money for tournaments from all over the world!
Random programming stream on Twitch.tv/jinritv

### Description of what this project is about:
https://clips.twitch.tv/SuperPhilanthropicDogeStoneLightning

So basically, I have recently started learning machine learning for my grad class and decided to predict something fun.
I have started watching Esports tournament since 2000 (Starcraft with SlayerSBoxer <3) and noticed the increase in prize money.
So this made me wonder by different countries and time, how much prize money has increased from before also because League of Legend became so popular with Faker senpai being super cool! However, there are still many parents out there that believe that gaming only has negative affects in future life, so I wanted to prove to them that they are wrong with data!

I hope by doing so, we can get some parents thinking positively about becoming a progammer or working in the gaming industry!!!

## contributors:
YMF292, blazers15, Chohonggam, 

*if you want to participate, join anytime when I code in stream and help out with any coding and give me a headsup!*

## HOMEWORK
- Future work:
  - Team/Indiv vs Prize Money (Histogram)
  - On/Off vs prize money (histogram)
  - Duration vs prize money (bar graph)
  
# Programming Log
## NOV 2019:
- Started this project of predicting Esports tournament prize money.
- Scrapped data from Esports Earnings into CSV (https://www.esportsearnings.com/games)

## DEC 2019:
- Data Reconstruction
  - Added New columns: Years, Month, Duration, On/Off
- worked on getting location to only show the countries

## FEB 2020:
- Data Reconstruction
  - Tried GEOCODER to get countries
    ~FAILED... I was able to get only 50 data per day... not possible~
  - Used spliting method to create a separate CSV file and identify the Countries (FEAT. YMF292)
DONE WITH DATA CONSTUCTION!!!!! (Prize Predict_LEE.csv)
- Start of Github *(Help needed, looking for Github helpers)*
- EDA (Explanatory Data Analysis)
  - Prize to Month: Total amount of prize in each Month

  - Tournament count to time for top 20 games in prize money
 
## MAR 2020:
- EDA continues
  - Tournament count to time for top 20 games in prize money
  - Country to Prize Money: How much total prize money each country spent between the data points
  - Online|Offline vs Prize Money
  - Team play|solo vs Prize Money
  - Top 5 games vs prize money

## APR 2020:
- LETS FINISH EDA!!
  - Changed online|offline vs Prize money to line graph in terms of years
  - Changed Team|solo vs Prize money to line graph in terms of years
  - Count of Online|Offline Stacked line graph
  - Count of team | Solo stacked line graph
- Correlation of the graph has been created!! :D
