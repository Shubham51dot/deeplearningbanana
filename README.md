# deeplearningbanana
## Banana project

In this project we use Deep Q-Learning(DQN) to coach an agent to gather bananas within an easy 2d world. The project uses Unity's ML-Agents environment. The goal of the agent is to gather yellow bananas while avoiding blue bananas.

The environment features a state space of 37 dimensions including basic information about the agent and therefore the "ray-based" perception of the objects it can see. Note - For this project, no trainning was undertaken supported pixel values.

The agent receives a gift of +1 for selecting up a yellow banana and a -1 penalty/reward for selecting up a blue banana. The environment is concsiderd solved when the agent receives a mean score of +13 over 100 consecutive episodes.
The agent has four discrete actions to settle on from:
1. 0 - Forward
2. 1 - Backward
3. 2 - Left
4. 3 - Right

### Installation
The Unity ML-Agents environment only supports Python 3.6.

Installation instructions for the Unity ML-Agents are often found at Unity ML-Agents and NumPy. Note - you are doing not require the Unity download for this project.

The following prerequist libraries are often installed as follows:

1. pip install numpy

2. pip install torch

3. pip install unityagents

4. pip install matplotlib




