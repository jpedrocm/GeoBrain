# GeoBrain
Geobrain is a simple game developed in C/C++ which uses world geography data to train memorization skills.

#How it works
The game is composed by 3 rounds and each round by multiple stages. When the user starts one round, he receives a small list of cities from a given country of the world. On each stage, the user has to select a city from the list. If he selects a city he has not chosen before, he goes to the next stage, when one more city of that country is added to the list of cities he has to choose from. If he selects a city he has already chosen, he loses, receives a score for that round, and a new round is started with a new list.

A round can also end after 2 minutes, or if the player correctly chooses all cities from the list.

This game offers some users rankings.

#Data
This repo does not provide any data, but this is the recommended data format you should follow if you do not want to modidy the code:
countries.txt --> each line: [COUNTRYCODE] COUNTRY NAME
cities.txt --> each line: [COUNTRYCODE] CITY NAME

#License
This project is under the MIT License. Please, read the LICENSE.md for detailed information.