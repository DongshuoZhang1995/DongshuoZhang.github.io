---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Electrical & Computer Engineering, The Ohio State University, January 2020 - December 2023
  * Dissertation title: Geopositioning Multiple Autonomous Platforms using Deep Learning and Photogrammetry
  * Advisor: Professor [Alper Yilmaz](https://ceg.osu.edu/people/yilmaz.15)
* M.S. in Electrical & Computer Engineering, The Ohio State University, August 2017 - May 2019
  * Advisor: Professor Wladimiro Villarroel
* B.E. (Bachelor of Engineering) in Electronic Information Engineering, University of Electronic Science and Technology of China, September 2014 - June 2017

Research Projects
======
* Vision-based Unmanned Aerial System (UAS) Geotracking [[`paper`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9967102)] [[`link`](https://github.com/JianliWei1995/Vision-based-UAS-Geotraking-2022)]
  * Reduced UAS reliance on Global Positioning System, which can be jammed and suffer from multipath problems
  * Proposed a real-time pipeline alternative to the GPS functionality using UAS embedded vision system
  * Constructed the pipeline consisting of an off-line fast geospatial Quadtree data retrieval, a selection of feature detection and matching schemes, and attitude-control mechanism guaranteeing the scalability of flight region
  * Achieved realtime UAS geotracking accuracy by 3.39 meters in average and 5.38 meters in maximum

* UAS Navigation in Real World using Reinforcement Learning (RL) [[`paper`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9967103)] [[`link`](https://github.com/JianliWei1995/Vision-based-UAS-Geotraking-2022)]
  * Inspired by human’s instinct: environment understanding and landmark recognition, the team enabled the UAS self-navigation via recognizing its surrounding environment using its embedded vision sensor
  * Trained the agent in reinforcement learning framework to interactively learn the navigation policy and familiarize itself using images from vision sensor in an designed UASNAV environmen
  * Let the UAS fly in the real world to recognize the landmarks and take action according to the learned policy
  * Proposed a novel end-to-end UAS navigation framework for long-range vision based navigation in the real world. Experiments demonstrated that the UAS can navigate itself to the destination hundreds meters away from a random selected starting point with following the shortest path

* Object Detection and Height Estimation using Deep Learning [[`paper`](https://isprs-archives.copernicus.org/articles/XLIII-B2-2021/557/2021/isprs-archives-XLIII-B2-2021-557-2021.html)] [[`link`](https://github.com/JianliWei1995/Vision-based-UAS-Geotraking-2022)]
  * Developed object height estimation algorithm using vehicle-mounted monocular vision system and deep learning
  * Proposed an end-to-end pipeline consisting of the choice from a selection of advanced object detectors and photogrammetry module doing depth estimation, 2D to 3D backprojection and object height decomposition
  * Proposed MOHE-Net detecting and estimating object (over 80 classes) height. Estimated a 183 centimeters tall person within an average error of 5.09 centimeters, around 2.8%

* Artificial Intelligence Technique for Trajectory Estimation of Maritime Vessel [[`paper`](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9639595)] [[`link`](https://github.com/JianliWei1995/Vision-based-UAS-Geotraking-2022)]
  * Generated georeferenced tracks of maritime vessel traffic based on the data recorded from a single electro-optical camera imaging the traffic from a moving platform
  * Localized target vessel among several similar vessels in image coordinates with tracking by detection strategy
  * Defined the geometric relation between GPS-based spherical coordinates of latitude and longitude in the world frame, the local camera centered coordinates and the local image coordinates
  * Geotracked target vessel in video and retrieved its geoposition in the accuracy by 15.26 meters in average


Skills & Qualifications
======
* Python, Matlab, C++, R
* PyTorch, TensorFlow, OpenCV, Pandas, SciPy, scikit-learn


Patent
======
* System and Method for Hypersonic Aerial Platform Geopositioning (in review)


Publications
======
{% include papers.md %}

