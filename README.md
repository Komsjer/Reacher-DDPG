# REACHER DDPG 
This project is an assignment from the Udacity Deep Reinforcement Learning course. [p2_continuous-control] found here. The objective is to train the Unity reacher agent to keep its arm in a rotating target.


## Enviroment

##### Observation

Type: Box(33)

The statespace represents the current state of the arm and the targer.

##### Actions
Type: Continues(4)

The 4 actions controll the movement of the agents arm

##### Reward

A reward of ~+0.04 is provided for each step the agent is in the target sphere.

## Installation and setup

##### 1.
For the dependancies to this project please follow the instructions from the assignment github [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)

##### 2.
To install the unity enviroment you'll need to download the right version for your pc drag it into the project folder and unzip it, not that you'll need to edit the path in the notebook.

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

##### 3.
Launch Jupyter notebook in the project folder

## How to use
When running either of the notebooks make sure you have edited the PATH variable to your version of the unity Banana enviroment

To train a model run the Training notebook

To Evaluate an agents performance run the Evaluation notebook
