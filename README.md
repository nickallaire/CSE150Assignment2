# CSE 150: Introduction to Artificial Intelligence: Search and Reasoning Assignment 2

Project Overview: The goal of this assignment is to design agents for the classic version of Pacman, including ghosts and implement the minimax and expectimax search algorithms. To start off, I modified the reflex agent code to perform better, by having it consider both food locations and ghost locations. Minimax was implemented with an adversarial search agent and then improved by implementing Alpha-Beta Pruning to more efficiently explore the minimax tree. Minimax and alpha-beta both assume you are playing against an adversary who makes optimal decisions. Expectimax was implemented to model probabilistic behavior of agents who may make suboptimal choices. The final step was to write a better evaluation function than the one provided, by evaluating states, rather than actions. My portion of the code can be found in multiAgents.py in spots labeled "*** YOUR CODE HERE ***". The rest of the files and code was provided to complete the assigment.
