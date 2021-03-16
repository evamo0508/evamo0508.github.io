---
title: "AutoValet: Autonomous Parking in Parking Garages"
collection: projects
type: "Capstone Project"
permalink: /projects/autovalet
venue: "MRSD Program, Carnegie Mellon University"
date: 2020-11-24
location: "Pittsburgh, PA"
---

Our team proposes a parking solution that can operate in the absence of this custom infrastructure.
Our system provides an autonomous car the ability to enter a previously unexplored parking garage,
navigate safely through the garage until an empty parking spot is found, and park itself. In the
background, the system will be creating an accurate map of the environment that can be used by
building managers, future cars entering the garage, etc.

Abstract
======
Within the realm of autonomous driving, autonomous parking in indoor environments is an under-
explored topic. Indoor parking creates new challenges, as there is rarely a prior map of the
environment and the configuration of the environment is non-static, with different amounts of parked
cars and people present in the garage at any one time. Moreover, there is no prior information
regarding the location of the free parking spots in the garage, which complicates the planning
problem since there is no clear destination. In this project, we intend to tackle some of these
problems assuming minimal priors about the environment.

We have developed a platform-independent software stack that can scale to enable driver-less
cars to autonomously search a crowded indoor parking garage for a free spot and park itself in
that spot. We developed it to be control-model-independent and easy to interface with the existing
autonomy stack of any planar mobile robotic system. The system does not require any custom
infrastructure or pre-built maps of the environment.

We propose a pipeline comprising of modules to perform lane detection, simultaneous local-
ization and mapping, path planning, and parking in order to execute an end-to-end autonomous
search-and-park maneuver. We validated the performance of our system in simulation (Gazebo)
and hardware (Clearpath Husky) using rigorously derived metrics for each subsystem, and used the
CMU East Campus Garage to perform our tests and showcase our demo. This report comprises
the technical details of our software pipeline and project management practices followed over the
course of the project.

Website
======
My team and I had put up tons of information to this [website](https://mrsdprojects.ri.cmu.edu/2020teami/) under MRSD program.
Not only are the project systems elaborated, but also we had the project management docuements and diagrams included.

Report
======
This project had been going on for 1.5 years (3 semesters in total). 
We had several reports/presentations/individual lab reports uploaded [here](https://mrsdprojects.ri.cmu.edu/2020teami/presentations/),
including some of those here for convenience.
* [Final Report](https://drive.google.com/file/d/1FldlT7pVbCBCbyigWUuv2oP38Tb-k2BL/view)
* [Final Poster](https://docs.google.com/presentation/d/1eosKrK5BLm70Mu2J6YtF2qS3BPplPqU4OsldYLVNqEM/edit#slide=id.p)

Demo Video
======
We put up 3 demo videos [here](https://mrsdprojects.ri.cmu.edu/2020teami/video-gallery/),
including one video for final validation, one for the Spring semester recap, and one for how we assemble our robot platform.
