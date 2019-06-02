# drl_p1
# Summary
Repository for the 1st project for Deep Reinforcement Learning nanodegree on Udacity.

In this project we train an agent to collect bananas in the Unity based environment.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. The agent has 4 possible actions - move forward, move backward, turn left, and turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

# Contents

Contains the agent code (`dqn_agent.py`), neural net code (`model.py`), training notebook (`Navigation.ipynb`), trained model weights (`checkpoint.pth`), and report (`Report.pdf`).

# Getting Started
Download the environment from one of the links below. You need only select the environment that matches your operating system:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
(For Windows users) Check out this [link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file.

# Instructions

Follow the instructions in `Navigation.ipynb` to train the agent.
