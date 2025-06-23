# Cheaper Airline Conection
This is a python coding exercise that checks if we can get a cheaper flight by flying long distance.

## Problem
COMPANY X employees are trying to find the cheapest flights to upcoming conferences.


When people fly long distances, a direct city-to-city flight is often more expensive than taking two flights with a stop in a hub city. Travelers might save even more money by breaking the trip into three flights with two stops. But for the purposes of this challenge, let's assume that no one is willing to stop three times. The table contains the following columns:

•   id - the unique ID of the flight;

•   origin - the origin city of the current flight;

•   destination - the destination city of the current flight;

•    cost - the cost of current flight.

Dataframe: da_flights

Your task is to produce a trips table listing the cheapest possible trips between all origin-destination pairs present in the dataset, considering routes with up to two stops.


This table should have the columns origin, destination, and min_price (cheapest one). Sort the output table by origin, then by destination.


The cities are all represented by three-letter uppercase abbreviations.


Note: A flight from SFO to JFK is considered different from a flight from JFK to SFO.

## Solution
Solution to the above problem is in the notebook attached to this branch. Each steps is well documented in the notebook.
