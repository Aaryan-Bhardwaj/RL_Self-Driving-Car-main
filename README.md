![NTU logo](https://1000logos.net/wp-content/uploads/2021/04/ASU-logo.png)

Arizona State University, Arizona

Ira A. Fulton Schools of Engineering
___

### EEE 598: Reinforcement Learning in Robobotics Final Project
# Reinforcement Learning for Self-Driving Cars
___

- This project is a Final Project carried out by **Aaryan Bhardwaj, Apoorv Uplal, Aditya Ravichander, Akshat Sharma** as part of our EEE 598 curriculum.
- Download here: [Final-Report.pdf](https://docs.google.com/document/d/18EjKs-7TDLgtz52AHI6O3cpm7RkFAeCz/edit?usp=share_link&ouid=104476638045106880617&rtpof=true&sd=true)

___

# Abstract

In this project, we implement a supervisor agent that uses deep reinforcement learning to improve driver assistance systems. The agent has to maximize its speed on a multi lane expressway. Collision avoidance function is added to the environment in order to avoid potentially dangerous scenarios. Additionally, the highway driving instance is a stochastic environment with built-in randomness.  In this project, a traffic environment simulation, a neural network model, and a reinforcement learning agent is developed. The suggested model just makes use of the barest amount of environmental sensory data. The ideal policy is effectively learned by the agent and applied. To evaluate the model's statistical performance, three different traffic scenarios were investigated.

This work uses [Songyan Ho's work](https://github.com/songyanho/Reinforcement-Learning-for-Self-Driving-Cars) as its starting point and focuses on observing variations in model behaviour with changes in reward structures.

# Simulator

![screenshot](https://lh4.googleusercontent.com/k4OYr4Xbm19aXYHhfaYEUIwbfI5gB8tgJFYL3ZhrzQemRVZDjoaomnYS3kmwh32xAX4=w2400)

*Simulator running under macOS environment*

## Run
1. Install latest Python version
2. Open Terminal. Navigate to main directory.
3. Install requirements using <br>&nbsp;&nbsp;&nbsp;pip install -r requirements.txt
4. Run using command <br>&nbsp;&nbsp;&nbsp;python gui.py
