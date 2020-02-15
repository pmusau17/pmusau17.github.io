---
title: Projects
layout: collection
permalink: /projects/
collection: projects
entries_layout: grid
---

![Patrick](/pages/images/projects2.jpg "Projects Image")
## [DARPA Assured Autonomy](https://www.darpa.mil/news-events/2020-01-29)

**Project Summary*:* The Goal of the Assured Autonomy program is to create technology for the continual assurance of Learning-Enabled, Cyber Physical Systems. Utilizing formal methods and other fault tolerance techniques, the project seeks to advance the ways Machine Learning and AI systems can learn and evolve to better manage variations in their environments. Our focus has been on the autonomous vehicle space. However the technology and techniques being investigated will be designed to be transferable to other autonomous systems with minimal modifications.

**Specifics:**
- Trained a reinformcement learning agent to autonomously control and unmanned underwater vehicle to avoid obstacles in a pipe following scenario
- Performed the data collection, sanitization, that was used to identify a mathematical model of the underwater vehicle 
- This model was then used to reason about the safety the system using [reachable set analysis](https://ieeexplore.ieee.org/abstract/document/8318388) 
- Funded by the Defense Advanced Research Projects Agency (DARPA)
- Framework’s used: Robotic Operating System, Python, MATLAB, [NNV](github.com/verivital/nnv)

## [F1Tenth Autonomous Racing Competition](https://github.com/pmusau17/Platooning-F1Tenth)

- Built a 1/10 scale autonomous vehicle testbed equipped with a LIDAR, stereo camera, and inertial sensors
- The testbed’s sensors mimic full scale solutions and allow us to pursue research in perception, planning, control, and networking
- Competed at CPS-IoT Week in Montreal Canda using a potential field control strategy
- Pursuing strategies involving Simultaneous Localization and Mapping, Path Planning, Reinforcement Learning, and End to End Learning
- Development timeframe: March 2019-present
- Languages and Framework’s used: Robotic Operating System, Python, C++

## [NSF CPS Challenge](https://github.com/verivital/VandyCPS)

- Goal of this challenge is to use a quadrotor aircraft with downward facing camera, and other sensors, to scan an area for a lost aircraft, and recover it safely back to base
- Platform used: the Intel® Aero Ready to Fly Drone
- Achieved a 3rd place ranking after one week of development in 2017
- Development timeframe: 2017-Present
- Languages and Framework’s used: Robotic Operating System, Python, OpenCV, C++

### [NNVMT](https://github.com/verivital/nnvmt)

- Purpose of this tool was to address the lack of neural network model standardization among the various verification research software artifacts
- Tool allows for interchange between neural network verification tools and related software, such as ONNX, PyTorch, Keras, Tensorflow
- Development timeframe: 2018-present
- Written in Python 3
