# Deep-Reinforcement-Learning-My-First-DQN-Agent
This is an implementation of Deep Reinforcement Learning for a navigation task. Specifically, DQN algorithm with experience replay method is used to solve the task.
## Details of the environment 
THe environment is a [Unity Environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector) which consists of a square surface with Yellow and Blue Bananas scattered around. 
## Task of the agent
The agent needs to collect as many yellow bananas as possible while avoiding the blue bananas.
## Actions possible for agent 
- move forward
- move backward
- turn left
- turn right
## Reward for the agent 
- Yellow banana `+1` reward
- Blue banana `-1` reward
## When is environment said to be solved ?
The banana collection is an episodic game. Idea is to maximise the total score in an episode. The environment is said to be solved if the agent learns to secure an average score of at least `+13` points over `100` consecutive episodes.
## How to get started ?
- Gain a basic understanding of [Unity Environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector)
- Set up a Python 3.6 Environment to install [Dependencies](https://github.com/udacity/deep-reinforcement-learning#dependencies) involving PyTorch, the ML-Agent toolkit and a few more Python packages.
- Download a Unity Environment for [Windows(64-bit)](https://classroom.udacity.com/nanodegrees/nd893/parts/6b0c03a7-6667-4fcf-a9ed-dd41a2f76485/modules/e7499d4f-24f9-42ec-9864-23adcfa4e241/lessons/69bd42c6-b70e-4866-9764-9bfa8c03cdea/concepts/319dc918-bd2c-4d3b-80a5-063bb5f1905a)/[Windows(32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)/[Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)/[LINUX](https://classroom.udacity.com/nanodegrees/nd893/parts/6b0c03a7-6667-4fcf-a9ed-dd41a2f76485/modules/e7499d4f-24f9-42ec-9864-23adcfa4e241/lessons/69bd42c6-b70e-4866-9764-9bfa8c03cdea/concepts/319dc918-bd2c-4d3b-80a5-063bb5f1905a)
## My Solution
![image](https://github.com/SHIVOH/Deep-Reinforcement-Learning-My-First-DQN-Agent/blob/main/resultDRL.png)
- Run [Navigation.ipynb](/Navigation.ipynb)
- See a glimpse of my [agent during training](https://www.youtube.com/watch?v=GsU6uDynaw8) and my [trained agent](https://www.youtube.com/watch?v=aMmo9q_zODk) collecting bananas on YouTube.
- Do checkout my [Report](/report.pdf) for more theoretical explanation of the project implementation.
