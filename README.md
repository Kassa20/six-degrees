# six-degrees
This algorithm uses Breadth First Search to find the minimum distance between two actors. 


## Background 
According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.

In this problem, we’re interested in finding the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.”

We can frame this as a search problem: our states are people. Our actions are movies, which take us from one actor to another (it’s true that a movie could take us to multiple different actors, but that’s okay for this problem). Our initial state and goal state are defined by the two people we’re trying to connect. By using breadth-first search, we can find the shortest path from one actor to another.

## Task
Complete the implementation of the shortest_path function such that it returns the shortest path from the person with id source to the person with the id target.

## Sample Output

<img width="422" alt="image" src="https://github.com/user-attachments/assets/1776310d-b2d8-49c1-97f6-2a550883059f" />






