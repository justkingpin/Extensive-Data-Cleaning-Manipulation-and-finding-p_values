# Extensive-Data-Cleaning-Manipulation-and-finding-p_values

Description
In this project, i will read in a file of metropolitan regions and associated sports teams from assets/wikipedia_data.html and answer some questions about each metropolitan region. Each of these regions may have one or more teams from the "Big 4": NFL (football, in assets/nfl.csv), MLB (baseball, in assets/mlb.csv), NBA (basketball, in assets/nba.csv or NHL (hockey, in assets/nhl.csv). Please keep in mind that all questions are from the perspective of the metropolitan region, and that this file is the "source of authority" for the location of a given sports team. Thus teams which are commonly known by a different area (e.g. "Oakland Raiders") need to be mapped into the metropolitan region given (e.g. San Francisco Bay Area). This will require some human data understanding outside of the data that's been provided(i had to hand-code some names, and needed to google to find out where teams are)!

For each sport I would answer the question: what is the win/loss ratio's correlation with the population of the city it is in? Win/Loss ratio refers to the number of wins over the number of wins plus the number of losses. I calculated the correlation with pearsonr, so, I sent in two ordered lists of values, the populations from the wikipedia_data.html file and the win/loss ratio for a given sport in the same order. I found the average of the win/loss ratios for those cities which have multiple teams of a single sport. I only used data from year 2018 for my analysis

NOTES
I did not include data about the MLS or CFL in any of the work, because I was only interested in the Big 4 in this project.
I tackled the four correlation questions in the order NHL, NBA, MLB, NFL
It's fair game to talk with peers about high level strategy as well as the relationship between metropolitan areas and sports teams.
