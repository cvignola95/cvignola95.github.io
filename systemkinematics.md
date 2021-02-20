---
title: System Kinematics
---

## Figure in Vector-Based Drawing

![Annotated Figure](/AnnotatedFigure.svg)
**Figure 1.** _4 Bar Mechanism_

## Paper Device
_Update 02/19/2021_

![Photo](/IMG-20210218-WA0000.jpg)
**Figure 2.** _Physical Model 1_
![Photo](/IMG-20210218-WA0001.jpg)
**Figure 3.** _Physical Model 2_
![Photo](/IMG-20210218-WA0002.jpg)
**Figure 4.** _Physical Model 3_
![Photo](/IMG-20210218-WA0003.jpg)
**Figure 5.** _Physical Model 4_
![Photo](/IMG-20210218-WA0004.jpg)
**Figure 6.** _Physical Model 5_
![Photo](/IMG-20210218-WA0005.jpg)
**Figure 7.** _Physical Model 6_
![Photo](/IMG-20210218-WA0006.jpg)
**Figure 8.** _Physical Model 7_
![Photo](/IMG-20210218-WA0007.jpg)
**Figure 9.** _Physical Model 8_
![Photo](/IMG-20210218-WA0008.jpg)
**Figure 10.** _Physical Model 9_
![Photo](/IMG-20210218-WA0009.jpg)
**Figure 11.** _Physical Model 10_
![Photo](/IMG-20210219-WA0003.jpg)
**Figure 12.** _Physical Model 11_

## [Kinematics Modeling Python Code](https://nbviewer.jupyter.org/github/cvignola95/cvignola95.github.io/blob/main/System%20Kinematics.ipynb)

## Discussion

_1. How many degrees of freedom does your device have? How many motors? If the answer is not the same, what determines the state of the remaining degrees of freedom? How did you arrive at that number?_

The device has one degree of freedom as of now. So only one motor as of now. But the degrees of freedom will change after we design the end effector for the system. So more motors may be required. Once the end effector is designed, the team's website will be updated with the total degrees of freedom for the system and the total number of motor that will be finally used.

_1. If your mechanism has more than one degree of freedom, please describe how those multiple degrees of freedom will work togehter to create a locomotory gait or useful motion. What is your plan for synchonizing, especially if passive energy storage?_ 

The mechanism currenlty has only one degree of freedom. The descripion about how the system will work together to create a locomotory gait or useful motion will be added to the team's website after the end effector is designed and more degrees of freedom are added to the system later. The plan for synchronizing will also be updated on the team's website after the end effector is designed.

_1. How did you estimate your expected end-effector forces ?_

From our biomechanics studying, what we know is the maximum acceleration during the motion, we assume acceleration profiles are sinusoidal. Therefore, maximum acceleration happens at t = 0, goes to 0 at the midpoint and becomes negative from midpoint to reaching the prey. We also know the mass of the device; therefore, we can compute the force profile required for our device by using F = m*a.

_1. How did you estimate your expected end-effector speeds ?_

From literatures, we found the maximum speed and we know the speed at the initial point and final point is 0. Then, we just assume the speed profile is a sinusoildal function and fit the known parameters into the function.
