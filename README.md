# Current-Emerging-Trends-in-CS

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

In order to implement deep Q-learning I was tasked with completing the Q-training algorithm code block. To do this we first had to declare and initialize the variables that will be used be the learning algorithm to train our system. After that we had to make a for loop that runs for each epoch, or times that the learning algorithm will work through the training dataset. Inside this loop we need to reset the epoch-specific variables and tell the agent where to start. Next, we need to make a while loop to continue moving the agent until the game is over by either winning or losing. Winning the game is reaching the treasure and losing the game is if there are no more actions that can be taken. You then need to tell the agent what to do. The epsilon is set to choose a random action 10% of the time, as the epsilon is initially set to 0.1, and set to choose the move with the highest reward for the other 90% of the time.  After each move the system takes the new information it learned and updates the Q-table with new values. This continues for each move until the agent wins or has no more valid actions. As the agent discovers the path to the treasure, the values along that path are set to the highest reward and the epsilon is lowered to make the agent choose the higher reward more. If the agent wins, the win history is appended by one so that we can track the success of the system and the system is set to run until either the win rate passes the completion check or the system runs through the number of set epochs. 

What do computer scientists do and why does it matter?

Computer scientists are tasked with solving problems using programming and algorithms to improve computer systems and create and develop  applicaations to aid in making life easier for humans.

How do I approach a problem as a computer scientist?

 I approach problems as a computer scientits by first finding and reviewing the ideas and requirement that the problem provides. From there I put the ideas together in a document to define everything that the problem entails. After that, it is important to create diagrams and requirements before building the system that solves the problem.
 
 What are my ethical responsibilities to the end user and the organization?
 
 It is important to make sure that computer scientists have a strong code of ethics. They must be sure that they think about the end user and their privacy while developing. 
 
 
