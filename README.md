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
