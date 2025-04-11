---
title: "Projects"
permalink: /projects/
toc: false
toc_icon: "list"
toc_label: "Contents"
toc_sticky: true
classes: wide
header:
  overlay_image: /assets/Image_water.jpg
  overlay_color: "#000" #overlay_filter: "0.5"
---
I have taken courses in various topics during my academic studies. Here is a list of course projects from my Ph.D. at JHU and my Master’s at UPenn.

## Comparative study of reinforcement learning of heuristic gait learning in quadrupedal robot
Implemented Improved Deep Deterministic Policy Gradient (DDPG) and TD3 on Ant-V2 model using OpenAI gym environment to find stable gait control.

## Wall Tracking using a cockroach Lateral Leg Spring (LLS) Model
Implemented the trajectory tracking and the tracking control of the LLS model moving along a wall in Matlab. Generated an optimized trajectory using differential dynamic programming (DDP) and differential flatness by minimizing energy for a no wall, one wall, two walls, and three walls scenarios. Used feedback linearization as control law to move the model along the desired trajectory.

## Lateral Leg Spring (LLS) Model Analysis and Application on Wall Following
Implemented and simulated a 2- LLS model for a fixed CoP (Center of Pressure) along both vertical and horizontal directions. Implemented the wall following control for the antenna-based LLS model. Added multiple sections on the return map: (1) A section when the leg spring is fully compressed (2) A section when the leg spring is fully contracted. Implemented the wall following control on the return map.

## Place and mark with intention using UR5
Used UR5 interface to get the positions from the robot. Performed control trajectories with UR5 controlled using ROS RVIZ environment that involved inverse kinematics, resolved rate control, gradient control programmed in Matlab to perform the place and mark task. Programmed a code to perform the task of writing "RDKDC" on a piece of paper using the actual robot controlled using ROS RVIZ environment.

## EKF SLAM
Implemented a full SLAM system based on an Extended Kalman Filter in Python.

## A Quaternion Based Unscented Kalman Filter Orientation Tracking
Implemented an Unscented Kalman Filter to track three-dimensional orientation in Python.

## Bayes Filter
Implemented a Bayes Filter to keep track of the Robot’s position in a 2-D grid world in Python.

## Adaptive Filtering
 Designed an adaptive notch filter using LMS algorithm in MATLAB which successfully removed an interference with constant noise frequency and a slowly changing noise frequency. Designed an adaptive notch filter using the NLMS algorithm to remove two different noise frequencies at the same time. Adaptive filtering was used to equalize or invert an unknown channel using training mode equalization and blind equalization. Designed a FIR filter that approximates an IIR filter using the LMS algorithm. Designed a two-channel perfect reconstruction filter bank using MATLAB which successfully reconstructed 1-D signals and 2-D image signals

## Control Methods for time delayed continuous systems
Designed a Smith Predictor to compensate the reduced gain and stability in time delayed continuous systems. Implemented the Smith Predictor in a time delayed PID Controller and LQR Controller

## 8-bit Analog to Digital Converter (ADC) Design
Designed and simulated an 8-bit pipeline ADC using Cadence Virtuoso using a 0.6µm CMOS process. Programmed a code using MATLAB to calculate the INL and DNL of the ADC. The ADC, when tested, provided a DNL of +0.7508/-1 LSB and an INL of +0.582/-1.5512 LSB.

## Wideband Trans-impedance Amplifier Design
Designed and simulated a wideband trans-impedance amplifier using a 0.6µm CMOS process in Cadence Virtuoso. The trans-impedance amplifier had a gain of 206.5kΩ, a bandwidth of 177.8 MHz, and a total input inferred current noise of 19.62nA.
