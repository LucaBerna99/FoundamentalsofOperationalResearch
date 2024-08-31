# FoundamentalsofOperationalResearch

Imagine a bus system with multiple stops. This code helps figure out the best way to schedule buses using data about:

Bus stops and travel times: This includes information on where buses start and end, and how long it takes to travel between stops.
Number of passengers: The code considers how many extra passengers are waiting at each stop.
The code does 4 main things:

## Cleans Up Data: 
It removes unnecessary information and makes sure everything is formatted correctly.
## Creates a Map:
It builds a network map where each stop is a point and travel times are connections between points.
## Calculates Best Bus Routes:
It figures out the minimum number of buses needed and the best routes for them to take, considering travel times and extra passengers. It does this by trying different scenarios with more buses and seeing if the overall cost (extra passengers waiting) improves.
## Shows Results:
It creates a graph to visualize how the number of buses affects the total number of extra passengers waiting at stops.
In simpler terms, the code helps a bus company plan efficient routes for their buses to minimize passengers waiting at stops.
