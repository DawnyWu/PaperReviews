A Unified Neural Network Approach for Estimating Travel Time and Distance for a Taxi Trip


Jindal et al. propose ST-NN, a multi-layer feed-forward neural network for travel time estimation. ST-NN first takes as input the discretized latitudes and longitudes of the origin and destination to predict the travel distance and then combines this prediction with the time information to estimate the trip duration. 


One common limitation of these approaches is that the underlying road network structure and the spatiotemporal properties are largely overlooked. 

comment by Multi-task *****

***

A simple approach for travel time estimation is the segment- based approach, in this approach the travel time is estimated on links (straight subsections of a travel path with no intersections ) first and then add them up to estimate the overall travel time. 
One of the major drawbacks of the segment-based method is that it can not capture the waiting times of a vehicle waiting at the traffic lights, which is a very important factor for esti- mating the accurate travel time. 

In path-based methods, sub-paths (links + waiting time at intersections) are concatenated to predict the most accurate travel time 




