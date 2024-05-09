# Parking Lot Simulator

For this project, we trained an agent to find an optimal spot in a parking lot. First, we created a sample parking lot and then we had to randomly distribute cars. Because parking lots in real life fill up closer to an optimal spot, we distributed more cars closer to the optimal parking spot. For our training, we used Q-learning. Our agent trained iteratively with a heavy negative reward for parking into an occupied spot and an increasing positive reward for a spot closer to the optimal one. We used Manhattan distance to calculate the optimal spot and used a green gradient to visualize the value of each spot. Our agent had some basic constraints similar to a real-life car. The agent can only move forward and turn left or right. The agent had to drive into the lane before parking and could not pull through parking spots to change lanes.

The Final_Project.ipynb file is our final code for our Q-Learing Project
Final_Paper.pdf is our final report describing our findings and results
Final_Presentation_Slides.pdf are the slides we used for our poster board in class
Proposal.pdf is from an earlier assignment for documentation purposes
