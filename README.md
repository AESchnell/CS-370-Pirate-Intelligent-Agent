# CS-370 Pirate Intelligent Agent

Project Overview:

In this project, I developed an intelligent pirate agent that uses deep Q-learning to navigate an 8-by-8 maze and locate a treasure. The agent had to learn an effective route while avoiding obstacles, invalid movements, and unnecessary wandering. Successful movement toward the goal was reinforced through rewards, while inefficient or invalid actions resulted in penalties.

The starter code provided the maze environment, experience replay functionality, neural-network model, and helper functions for displaying the maze, playing a game, and checking whether the trained agent could reach the treasure. I created the Q-training algorithm that trained the pirate agent. My code reset the environment, selected actions through an epsilon-greedy strategy, stored experiences, trained the neural network using sampled experiences, updated the target network, tracked wins and losses, and stopped training after the agent achieved a 100% win rate and passed the completion check. In the completed run, the agent satisfied these conditions at epoch 404.

Connection to Computer Science:

Computer scientists use computational methods to analyze problems, design algorithms, develop software, and improve how people and organizations complete tasks. Their work matters because computer systems affect areas such as communication, transportation, healthcare, finance, education, and entertainment. This project demonstrated how computer science can be used to create a system that learns from experience instead of being explicitly programmed with every decision. Although the treasure hunt is a simplified environment, the same reinforcement-learning concepts can be applied to problems such as robotics, navigation, resource management, and automated decision-making.

I approach a problem as a computer scientist by first identifying the goal, requirements, inputs, constraints, and expected results. I then divide the problem into smaller components and examine the available code before deciding what needs to be created or modified. During this project, I reviewed how the maze environment represented states, actions, rewards, and outcomes before implementing the training algorithm. I tested the agent, monitored its win rate and loss, and used the completion check to verify that one successful game was not simply the result of chance. This process reinforced the importance of testing, iteration, documentation, and evidence-based evaluation.

Ethical Responsibilities:

As a computer scientist, I have an ethical responsibility to create systems that are reliable, secure, transparent, and respectful of their users. I should test software carefully, clearly communicate its limitations, protect user information, and avoid presenting uncertain results as guaranteed outcomes. An intelligent system should also be evaluated for unfair behavior or unintended consequences before it is used to make decisions that affect people.

I also have responsibilities to the organization for which I develop software. These include following requirements, protecting organizational data, documenting my work, respecting intellectual property, and reporting defects or risks honestly. In this project, ethical development meant preserving the supplied code where required, documenting the Q-training logic, and validating the agent from multiple starting positions instead of claiming success after a single win. In a real-world artificial intelligence system, these responsibilities would be even more important because errors or biased decisions could directly affect users and the organization.
