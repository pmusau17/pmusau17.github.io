---
title: Projects
layout: collection
permalink: /projects/
collection: projects
entries_layout: grid
---

![Patrick](/pages/images/projects2.jpg "Projects Image")
## [DARPA Assured Autonomy](https://www.darpa.mil/news-events/2020-01-29)

**Project Summary:** The Goal of the Assured Autonomy program is to create technology for the continual assurance of Learning-Enabled, Cyber Physical Systems. Utilizing formal methods and other fault tolerance techniques, the project seeks to advance the ways Machine Learning and AI systems can learn and evolve to better manage variations in their environments. Our focus has been on the autonomous vehicle space. However the technology and techniques being investigated will be designed to be transferable to other autonomous systems with minimal modifications.

**Specifics:**
- Trained a reinformcement learning agent to autonomously control an unmanned underwater vehicle to avoid obstacles in a pipe following scenario
- Performed the data collection, sanitization, that was used to identify a mathematical model of the underwater vehicle.
- The model was then used to reason about the safety of the system using [reachable set analysis](https://ieeexplore.ieee.org/abstract/document/8318388) .
- Funded by the Defense Advanced Research Projects Agency (DARPA).
- Framework’s used: Robotic Operating System, Python, MATLAB, [NNV](github.com/verivital/nnv).

## [F1Tenth Autonomous Racing Competition](https://github.com/pmusau17/Platooning-F1Tenth)

**Project Summary:** The [F1/10 Platform](http://f1tenth.org/) is an open source 1/10 scale vehicle testbed that carries a full suite of sensors for the tasks of perception, planning, and control. The platform is equipped with a LIDAR, stereo camera, and inertial sensors. Since 2016, teams have been competing in an international racing competition that has been held in Pittsbrugh, PA, Porto, Portugal, Turin, Italy, Montreal, Canada, New York, NY. The next competition is scheduled to be held at in Berlin, Germany at the International Federation of Automatic Control ([IFAC](https://www.ifac2020.org/)) conference in July, 2020. 

**Specifics:**
- Built a 1/10 scale autonomous vehicle testbed equipped with a LIDAR, stereo camera, and inertial sensors.
- Implemented a gap following algorithm called the [disparity extender](https://www.nathanotterness.com/2019/04/the-disparity-extender-algorithm-and.html) that was able to complete 21 laps in a 5 minute time trial with zero collisions. Demonstration can be found [here](https://youtu.be/Iq2r2OOWbkE?t=4639).
- Competed at CPS-IoT Week in Montreal Canda using a potential field control strategy.
- Implemented multi-vehicle platooning in simulation using the pure pursuit path tracking algprithm in simulation. Demonstration and code can be found [here](https://github.com/pmusau17/Platooning-F1Tenth)
- Implemented end-to-end learning driven control using NVIDIA's DAVE-II architechture and MiniVGGNet. Demonstration and code can be found [here](https://github.com/pmusau17/Platooning-F1Tenth).
- Currently Pursuing strategies involving Simultaneous Localization and Mapping, Path Planning, Reinforcement Learning, and End to End Learning.
- Development timeframe: March 2019-present.
- Languages and Framework’s used: Robotic Operating System, Python, C++.

<iframe src="https://giphy.com/embed/cMDs3hQe0fhcKqwOyu" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/cMDs3hQe0fhcKqwOyu"></a></p>

## [NSF CPS Challenge](https://github.com/verivital/VandyCPS)

**Project Summary:** The goal of the [NSF CPS Challenge (2020)](https://cps-vo.org/group/CPSchallenge) is to use a quadrotor aircraft with downward facing camera, and other sensors, to so search for an ideal experiment site for deployment of a soil probe, and recovery of the probe back to base after a pre-specified dwell time.

**Specifics:**
- Platform used: Tarot 680 pro
- The sampling goal for the competition is to use a probe to measure soil moisture, and soil grain size distribution.
- Implementing Object Detection Techniques using Keras and OpenCV
- Also working on implementing Visual Servo Techniques to control the drones descent to the target location.
- Development timeframe: 2017-Present
- Languages and Framework’s used: Robotic Operating System, Python, OpenCV, C++

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Day 1 of autonomous flight tests for the 2019 CPS Challenge at the TIMPA airfield in Tucson, AZ. <a href="https://twitter.com/cpsvo?ref_src=twsrc%5Etfw">@cpsvo</a> <a href="https://twitter.com/verivital?ref_src=twsrc%5Etfw">@verivital</a> <a href="https://t.co/uaFJAKN6CZ">pic.twitter.com/uaFJAKN6CZ</a></p>&mdash; Patrick Musau (@pmusau13) <a href="https://twitter.com/pmusau13/status/1128475378954035201?ref_src=twsrc%5Etfw">May 15, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### [NNVMT](https://github.com/verivital/nnvmt)

**Project Summary:** The purpose of this tool was to address the lack of neural network model standardization among the various verification research software artifacts. The tool allows for interchange between neural network verification tools and related software, such as ONNX, PyTorch, Keras, Tensorflow.

**Specifics:**
- The tool and installation instructions can be found [here](https://github.com/verivital/nnvmt)
- Implemented Translation Scripts for the following tools [Reluplex](https://github.com/guykatzz/ReluplexCav2017), [Sherlock](https://github.com/souradeep-111/sherlock), [ERAN](https://github.com/eth-sri/eran),  and [NNV](https://github.com/verivital/nnv).
- Implemented Unit Testing using PyTest to ease development and validate translations.
- Development timeframe: 2018-present
- Building the tool with [Diego Manzanas Lopez](https://dieman95.github.io/)
- Written in Python 3


> "If I have seen further than others, it is because I was standing on the shoulders of giants."
> 
> <cite>Isaac Newton</cite>