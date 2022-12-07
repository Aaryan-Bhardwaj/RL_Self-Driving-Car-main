![NTU logo](https://1000logos.net/wp-content/uploads/2021/04/ASU-logo.png)

Arizona State University, Arizona

Ira A. Fulton Schools of Engineering
___

### EEE 598: Reinforcement Learning in Robobotics Final Project
# Reinforcement Learning for Self-Driving Cars
___

- This project is a Final Project carried out by **Aaryan Bhardwaj, Apoorva Uplap, Aditya Ravichander, Akshat Sharma** as part of our EEE 598 curriculum.
- Download here: [Final-Report.pdf](https://docs.google.com/document/d/18EjKs-7TDLgtz52AHI6O3cpm7RkFAeCz/edit?usp=share_link&ouid=104476638045106880617&rtpof=true&sd=true)

___

# Abstract

In this project, we implement a supervisor agent that uses deep reinforcement learning to improve driver assistance systems. The agent has to maximize its speed on a multi lane expressway. Collision avoidance function is added to the environment in order to avoid potentially dangerous scenarios. Additionally, the highway driving instance is a stochastic environment with built-in randomness.  In this project, a traffic environment simulation, a neural network model, and a reinforcement learning agent is developed. The suggested model just makes use of the barest amount of environmental sensory data. The ideal policy is effectively learned by the agent and applied. To evaluate the model's statistical performance, three different traffic scenarios were investigated.

This work uses [Songyan Ho's work](https://github.com/songyanho/Reinforcement-Learning-for-Self-Driving-Cars) as its starting point and focuses on observing variations in model behaviour with changes in reward structures.

# Simulator

![screenshot](Simulation.gif)

*Simulator running under macOS environment*

## Run
1. Install latest Python version
2. Open Terminal. Navigate to main directory.
3. Install requirements using <br>&nbsp;&nbsp;&nbsp;pip install -r requirements.txt
4. For training the RL agent, Open config.py, comment the lines 21, 22 & 23 and uncomment the lines 16, 17 & 18. Set the penalties and rewards in config.py
5. For setting the reward for overtaking and penalty for being overtaken, open gui_util.py and edit the lines 223 (Overtaking reward) and 227 (being overtaken penalty)
6. Run using command <br>&nbsp;&nbsp;&nbsp;python gui.py 
7. For testing the RL agent, Open config.py, uncomment the lines 21, 22 & 23 and comment the lines 16, 17 & 18.
8. Run using command <br>&nbsp;&nbsp;&nbsp;python gui.py 

## Plot
1. Run the plot.m file in matlab.
2. The file accepts the 3 txt files - avgVel.txt, brakeCount.txt, rewards.txt as inputs and will plot the three corresponding values w.r.t episodes.
