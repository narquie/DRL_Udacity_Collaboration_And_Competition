# DRL_Udacity_Collaboration_And_Competition
The environment is a 2D space with two AI's that attempt to receive and return balls over a tennis net. The AI's can move forwards, backwards, and jump. Each time the ball touches the ground on a side of the net, the respective AI receives a reward of -.01. If the AI manages to hit the ball over the net, it receives a reward of +.1.

The state space is of length 8 and the action space is of length 2. The state space details the velocity and position of each respective racket and the position and velocity of the ball. The actions are a vector of length 2 which is moving along the x axis (+-) and jumping (a movement along the y axis).

Scoring a max score of .5 between agents averaged over the 100 latest epsiodes is the condition to solving the environment!

To run the project in windows, pytorch and unityagents packages must be installed. Pytorch's instructions for downloading are here: https://pytorch.org/ and unityagents instructions for downloading are here: in command line (after installing python 3), use "pip install unityagents". You will also need to unzip the folder for the Research.exe as the folder is named at the moment.

The project will be ready to run after all dependencies are met! Training an AI can and probably will use a lot of processing power, so do not be surprised if your computer suddenly is performing more than usual.

This project was heavily based on the source code from the Udacity program. I have made updates to how the agent is updated and the architecture of the neural networks.
