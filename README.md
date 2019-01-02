Deep Learning Project for IEOR 4720

Implementation of Bootstrapped DQN (https://arxiv.org/pdf/1602.04621.pdf)

To run this code ensure that you have numpy, gym, tensorflow, sklearn, pandas and matplotlib.pyplot installed. 

This repository contains 3 files.

1. Simple_Version_CartPole.ipynb:
This is a simple version of our project that only has 2 fully connected layers. It is only for the purpose of running CartPole which is the simplest possible environment on Atari Gym. 

To run the Bootstrapped DQN in line 2 set model_name = "Bootstrap"
To run the DQN in line 2 set model_name = "DQN"

2. Modified_DQN.ipynb:
This is a version of our project in which we have made an improvement to the Bootstrapped DQN. It is a modification. It is for the purpose of running any game in Atari Gym. You can run the DQN, Modified DQN and Bootstrapped DQN for any Atari Game.You can set the game you want to play in line 4: env = gym.make("Qbert-v0").

To run the Modified DQN in line 2 set model_name = "MDQN"
To run the Bootstrapped DQN in line 2 set model_name = "Bootstrap"
To run the DQN in line 2 set model_name = "DQN"
