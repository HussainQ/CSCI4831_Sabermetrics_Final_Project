# CSCI4831_Sabermetrics_Final_Project
Creating a new statistic to rank Pitchers

# Initial Proposal


My idea is based around one of the questions we have come across in the assignments; how do we determine how good a player truly is? I would like to take a tangent from that and answer the question “How can we measure a pitcher’s efficiency?” This is where my statistic comes in. The point of this statistic is to easily determine the performance or play style of a pitcher using on generalized score. 

I will be using statcast for all my data. Initially I will limit it to two seasons just for a smaller dataset, then adapt it and check if it works with many years of data. It is basically a combination of existing statistics in statcast being merged together as one single score. I would be applying a certain weight to each statistic and calculate my new statistic using that, perhaps as an average or on a percentage scale (which would involve finding the maximum value of this statistic over a few years, and scale accordingly). The variables I think would be useful are bb_type (Type of hit), v(x,y,z)0/a(x,y,z) (The acceleration and velocities of throws in 3 dimensions), effective_speed, release_spin, launch_speed, and launch_speed_angle. I believe the velocity, acceleration, and launch speed angles will have a higher weightage than the other variables, but I am currently unsure of how to balance these. 
  
I do see a few flaws with my approach. The main one would be that this is a completely biased statistic, based on a weighting system that I decide upon. Second, there are other factors that could contribute to a pitcher’s performance, such as playing on home field vs away, the weather, when the pitcher was put into a game, etc. However, the aim is just to create a general-purpose statistic that can generalize the performance of pitchers and give them a ranking. 
	
# Usage

All the required code is in the jupyter notebook.
