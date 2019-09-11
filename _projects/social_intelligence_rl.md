---
title: "Robots Gain Social Intelligence Through Reinforcement Learning"
collection: projects
type: "Undergraduate research"
permalink: /projects/social_intelligence_rl
venue: "Intelligent Robot Lab, National Taiwan University"
date: 2018-07-06
location: "Taipei, Taiwan"
---

Trained the humanoid robot Pepper to learn basic social skills through Proximal Policy Optimization in deep reinforcement learning, 
including understanding in what situation it should greet, say bye-bye, shake hands, or simply do nothing.

Abstract
======
The project goal is to make Pepper learn some basic social skills through deep reinforcement learning. 
The states for Pepper to determine his action were defined to be eight consecutively taken photos of his built-in camera, 
so that it mimics a person’s viewing of the surroundings. 
As for deep reinforcement learning, the quality and the amount of training data are the most important. 
Unfortunately, there wasn’t any open source data relating to our environment setup, so we had to collect all data by ourselves. 
A deep reinforcement learning model was trained and implemented to Pepper. 
Although the accuracy is not high enough due to the difficulties of collecting sufficient data, 
Pepper did learn something such as moving forwards to the person before shaking hands. 
More techniques with getting data are indispensable and would promise a better model through retraining with those data.

Report
======
I worked on this project for two semesters. As a result, there are two reports according to each semester.
* 1st semester: [report](http://evamo0508.github.io/files/2017Fall-IntelligentRobotLab-RL.pdf)
* 2nd semester: [report](http://evamo0508.github.io/files/2018Spring-IntelligentRobotLab-RL.pdf)

Demo Video
======
* An example with successful interaction: [video](https://goo.gl/rVepYb)
* Another example with successful interaction: [video](https://goo.gl/Vkz6hL)
* An unsuccessful interaction: [video](https://goo.gl/h6Rnv4)
