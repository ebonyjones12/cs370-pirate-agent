# CS 370 Pirate Intelligent Agent

## Project Summary

For this project I was given starter code that included the TreasureMaze.py and GameExperience.py classes along with a partially built Jupyter Notebook. The maze environment and the game experience replay system were already set up for me. What I created myself was the deep Q-learning algorithm inside the qtrain() function. This included the epsilon-greedy exploration and exploitation logic, the experience replay loop, the neural network training steps, and the target network update system. The model trained for 440 epochs before reaching a 100% win rate and passing the completion check from every starting position in the maze.

## What Do Computer Scientists Do and Why Does It Matter

Computer scientists solve real problems by building systems that can think, learn, and make decisions. This project is a good example of that because the pirate agent is not just following hardcoded rules. It is actually learning from experience over time. That matters because it shows how AI can be applied to things like navigation, robotics, and decision making in situations where you can not predict every possible outcome ahead of time.

## How I Approach a Problem as a Computer Scientist

I break the problem down into smaller pieces and try to understand what each part needs to do before I start writing code. For this project I had to understand how the environment worked, how rewards were being assigned, and what the neural network was supposed to learn before I could write the training loop. I also tested and adjusted things like the epsilon decay rate and the target network update frequency to get the model to perform well.

## Ethical Responsibilities to the End User and the Organization

As a computer scientist I have a responsibility to make sure the systems I build are honest about what they can and cannot do. For an AI agent like this one the ethical concern is making sure the system is actually reliable before it is used in a real setting. A model that looks like it is working but has not been properly tested could cause real harm depending on where it is applied. It is also important to be transparent about how the model makes decisions so that users can trust and verify the results.
