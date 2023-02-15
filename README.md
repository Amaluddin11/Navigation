# Bananas Collector - Udacity Deep Reinforcement Learning Project 1

# Project Details

This project involves training an agent to navigate a virtual world and collect yellow bananas while avoiding blue bananas. The agent interacts with the world using a Unity-based environment provided by [Unity Technologies](https://unity.com). The environment is called Banana Collector and contains 37 state features that the agent can observe, such as the agent's velocity and the ray-based perception of objects in the agent's forward direction. The agent takes actions based on the observed state and receives a reward of +1 for collecting a yellow banana and -1 for collecting a blue banana. The goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

### State Space

The state space has 37 dimensions and includes the agent's velocity and ray-based perception of objects in the agent's forward direction.

### Action Space
The action space consists of four discrete actions:

- `0` - move forward
- `1` - move backward
- `2` - turn left
- `3` - turn right


### Solved Criteria

This project is considered solved when the agent achieves an average score of at least 13 over 100 consecutive episodes. The score for each episode is the sum of rewards obtained during the episode.

# Getting Started

1. Select the environment that matches your operating system:
  - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

(*For Windows users*) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(*For AWS*) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the "headless" version of the environment. You will **not** be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the **Linux** operating system above.)

2. Then, unzip the file from this repository in the working folder.

# Instructions

Execute `navigation.ipynb`

It will first start the environment, and examine the state and action space.

Then, you can train the Agent.

Finally, you can test the trained Agent.

# License

This project is licensed under the MIT License - see the [**LICENSE**](https://opensource.org/license/mit-license-php/) file for details.

# Acknowledgments
This project was completed as part of the [**Udacity Deep Reinforcement Learning**](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) Nanodegree program.
