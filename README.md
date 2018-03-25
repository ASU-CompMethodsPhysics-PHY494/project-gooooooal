# Soccer Physics for the WIN! (Project 2 for the 2018 class)

## Background: scoring from set pieces

In soccer (or "football" for the world outside the US) a goal is scored when the entire ball fully crosses the goal line between the goal posts and under the goal cross bar. There are a number of set-piece situations that can directly lead to goals. Here we look at two such opportunities that start from a ball at rest:

1. **direct free kick**: A direct kick can be shot directly into the opponent’s goal without touching another player. The opposing team my place a "wall" of players between the ball and the goal but it has to be at a distance of at least 9.15 m (10 yards).
2. **corner kick**: The ball is placed in the corner area and kicked into play. A goal can be scored directly from a corner kick.



## Objectives 

Your objectives are
1. To write Python code to  _simulate realistic shots_ (corner, free kick with wall).
2. To write Python code to _find kick parameters that could lead to scoring a goal_ and to use your code to find such parameters.
3. You will write a _short report_ to communicate, discuss and summarize your reasoning and your results.

The work is carried out in teams of two or three students.


## Given parameters

Soccer rules follow FIFA's [Laws of the Game (PDF)](http://www.fifa.com/mm/document/footballdevelopment/refereeing/02/36/01/11/lawsofthegameweben%5fneutral.pdf).


### Field dimensions

The field is rectangular. The parameters were chosen in the middle of the allowed range for international matches:

- goal line (width of field): 70 m
- touch line (length of field): 105 m


### Goal 

The goal's dimensions are 

- height: 2.44 m (8 ft)
- width: 7.32 m (8 yards)


### Ball

The ball is spherical (parameters were chosen to be in the middle of the allowed ranges):

- circumference: 69 cm
- mass: 430 g


