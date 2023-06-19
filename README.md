# EDA_Mini_Project
                                             Sports Analytics-FIFA

A new football club named ‘Brussels United FC’ has just been inaugurated. This club does not have a team yet. The team is looking to hire players for their roster. Management wants to make such decisions using a data-based approach. During a recent hiring drive, you were selected for the Data Science team as a Junior data scientist. Your team has been tasked with creating a report which recommends players for the main team. To start with, a total of 15 players are required. Player data for all teams has been acquired from FIFA. This data contains information about the players, the clubs they are currently playing for, and various performance measures.
There is a limited budget for hiring players. The team needs 20 possible players to choose from. You have been requested to formulate a report in order to help the management make a decision regarding potential players.

**Data:**
The data contains details for over 18,000 players playing in various football clubs in Europe. It contains information on age, skill rating, wages, player value, etc. The files provided are as follows: 
fifa.csv – data file.
fifa_ variable_information.csv - information on individual variables.

**Data Preprocessing:**
1.	Import the necessary libraries and read the data.
2.	Drop any columns that you deem unnecessary for analysis.
3.	The following columns need to be converted for further analysis:
![Capture](https://github.com/royalbaswan/EDA_Mini_Project/assets/132448830/c40d693a-8b2b-4d4d-bde4-23e759c7253c)

4.	Check for missing values and do a mean imputation where necessary.

**Exploratory Analysis:**

1.	Plot the distribution of Overall ratings for all players. 
2.	Generate pair plots for the following variables:
* Overall, Value, Wage, International Reputation, Height, Weight, Release Clause
3.	Generate a table containing the top 20 players ranked by Overall score and whose contract expires in 2020.
  
  a) What would the average wage for this set of players be?
  b)	What is the average age?
  c)	Is there a correlation between the Overall rating and Value for these players?

4.	Generate tables containing the top 5 players by Overall rating for each unique position.
  a)	Are there any players appearing in more than one Table? Please point out such players.
  b)	What is the average wage one can expect to pay for the top 5 in every position?
