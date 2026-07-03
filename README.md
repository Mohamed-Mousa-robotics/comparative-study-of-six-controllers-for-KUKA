# Comparative-6-controllers-KUKA-Industrial-Robot
Trajectory Tracking Control of a KUKA Industrial  Robot: A Comparative Evaluation of Six Controllers
# Overview
his study explains comparison between 6 control methods for trajectory tracking control of KUKA KR6 R900 SIXX industrial robot under effect of 4 disturbance levels (0,1,1.5,2)*sinewave.  
# control strategies
Proportional–Integral–Derivative (PID), Computed Torque Control (CTC), Sliding Mode Control (SMC), Model Predictive Control (MPC), Adaptive Neural Network (ANN), and Actor–Critic Reinforcement Learning (AC RL). 
# Objective
study the performance for each controller by studying some characteristics, such as system behavior under varying disturbance levels, Integral of Time-Absolute Error (ITAE), Integral of Time Squared Error (ITSE), tuning effort, execution time, and real-time applicability. the tracking performance for the 6 cntrollers was studied the tracking circular trajectory. 
# MATLAB Simulink Implementation
the follwing figures presents some selected parts of the implementaion of some controolers using simulink environments.
![SMC](SMC.png)
![CTC](CTC.png)
![ADAPTIVENN](ADAPTIVENN.png)
# Results
the following figures demonstrate the comparative results of the 6 controllers.
![ctcresult](ctcresult.png)
![smcresult](smcresult.png)
![results](results.png)
![results2](results2.png)
