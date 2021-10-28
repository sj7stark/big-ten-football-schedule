# big-ten-football-schedule
a mixed integer program for creating a Big Ten (B1G) football schedule

# Information

* The B1G Conference has two 7 team divisions
    * West Division
    * East Division
* There are 13 weeks in the season. Each team has 
    * A bye week
    * 3 Non-conference games
    * 9 Conference games
        * 6 In-division Games (East team plays East team, West team plays West team)
          * 3 home in-division games
          * 3 away in-division games
        * 3 Crossover games (a West team playing an East team)
        * 4 or 5 home conference games
    

# Requirements

In order to run the model, you will need the following:
* Python
* The Python Library PuLP: https://coin-or.github.io/pulp/
* The Python Library Pandas: https://pandas.pydata.org/
* Jupyter Notebook

# Model

The notebook in this repository contains the model formulation, along with the corresponding code.

# Future Work

* Create a nice output file for the complete schedule
* Create a dashboard
* Make program that allows for additional constraints
    * Michigan plays against Ohio State in week 13
