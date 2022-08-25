# UCDPA_CliodhnaMcNamara
Data Anlysis of survival percentages on multiple factors in the Titanic dataset

Intro
I chose the Titanic as it is really interesting how much high-quality data is available for a renowned historic event that occurred over a hundred years ago and shaped the ship building industry from then on. There is a good spread of data that has been gathered regarding this event. A certain level of data quality is guaranteed with the Titanic as it is a much-studied tragedy. The integrity of the data allows for a more accurate analysis, and this was a big draw. The data available also acted as a social commentary for the period. It was revealing that there were stark differences between ticket classes, age range and sex. Analysing these events of the past gives us a better understanding of a time gone by.

Data
Survived – Integer, 0 = No, 1 = Yes, Whether the passenger survived or not.
Pclass – Integer, 1 = 1st, 2 = 2nd, 3 = 3rd, The ticket class of the passenger.
Name – object, The name of the passenger.
Sex – object, The gender of the passenger.
Age – float, The age of the individual.
SibSp – Integer, The number of siblings and spouses on board.
Parch – Integer, The number of parents and children on board.
Ticket – Object, The ticket number.
Fare – Float, The price of the ticket.
Cabin – Object, The cabin number.
Embarked – Object, C = Cherbourg, Q = Queenstown, S = Southampton, the port from where the passenger embarked.


Insights
1.	The age range of 20 – 49 years had the highest death rate and the highest survival rate.
2.	50 – 80 years had the second highest death rate.
3.	0 – 19 years looks to have equal number of deaths as survivals in the range.
4.	50 – 80 years and 0 – 19 years have the same number of survivals.
5.	The higher the class the higher the survival rate of a passenger. This would have been due to getting priority for the lifeboats but also being closer to the deck of the boat. The lower the class the lower down in the boat the passengers’ rooms were. When the ship started to sink it would have been the lower class that would have been hit first.
6.	There was a higher survival rate in females over males. Women and children would have been prioritised over men for getting onto the lifeboats.
7.	In all the different family sizes, the family size of 3 had a higher survival rate.
8.	Over 50% of survivors embarked from Cherbourg. Nearly four times the amount of people that embarked from Cherbourg, embarked from Southampton yet there was a higher survival rate from Cherbourg passengers.

