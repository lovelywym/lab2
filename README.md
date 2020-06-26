# VG 101 Project
## Proposal
1.Group number: 3


2.Group member: 
|Student name|Student ID|
|:-:|:-:|
|Linran Yang|519370910021|
|Siyu Li|519370910144|
|Yiming Wang|519370910080|


3.Project Name: Constructing passageways between cities


4.Intended language: MATLAB


5.Summary of our project: The project works out a scheme for constructing passageways between given cities according to their sizes and terrain and represent it in a plot.The constructed system of passageways is expected to be relatively efficient.


6.Motivation：We have played a game before called mini metro that designs metro ways between cities and keep putting trains on it to transport objects from city to city.The whole system is supposed to run well with no objects piling up at any one of the cities if the metro ways are designed in a wise way. We thus decide to work out a simplified version of the game that only includes the road-designing part.


7.Tentative Design of our project


Features:Our software takes the information of cities as input and outputs a designed system of passageways between them along with average efficiency w.r.t. unit length of the road.


In our project, the first step will prompt the user to enter a number n to create an empty map of n by n, which should not be too small considering the size and number of cities, otherwise the map will be too simple. Then we will generate m random cities of different sizes, and part of the blue area will be generated to represent the lake. Depending on the size of the city and whether there is a lake existing, water or land road will be built to the surrounding cities.


8.Expected outcome


Bottom-line: Generate random city positions within a given domain. Connect the cities with straight lines to represent passageways. To ensure that the whole system is designed wisely, we’ll need to make sure that efficiency of each road is sufficient, meaning that we build as few roads to transport as many people as possible. We will design a function to calculate efficiency in advance.


Expected: Consider differed size of different cities, giving the pedestrian flow of that city, and make more roads go through bigger cities. we may achieve this through expanding our initial program by considering big cities as the amounts of small cities placed on a same position.


Potential: Calculate the efficiency of each road after we take sizes into account.


9.Timetable: (time in the table is the latest time to complete the corresponding step)
|Time step|Project progress|
|:-:|:-:|
|7.4|set our map and create some cities(or revise our project if it failed)|
|7.11|create lakes,waterways,land routes,work on our progress report|
|7.18|change the size of cities and build rail networks,finish our progress report|
|7.25|debug and try to calculate the shortest route between cities|
|8.3|debug and finish the project|


10.Extra preparations: We plan to learn to analysis some practical cases of road designing in real life as well as in the virtual game so as to obtain general patterns of road arrangement. For various layouts of cities, we will further learn to find their approximation to more general examples and then deal with them with reference to general methods.


11.Task assignment:
Siyu Lyu: idea, proposal, coding, report
Linran Yang: proposal, coding, report
Yiming Wang: integrating proposal, coding, report



