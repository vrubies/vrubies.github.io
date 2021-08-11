---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Electrical Engineering, Boston University, 2014
* B.S. in Biomedical Engineering, Boston University, 2014
* Ph.D in Electrical Engineering and Computer Sciences, University of California at Berkeley, 2020
  * Research Area: Assured Autonomy for Safety-Critical and Learning-Enabled Systems.
  * Advisor: [Claire J. Tomlin](https://www2.eecs.berkeley.edu/Faculty/Homepages/tomlin.html)

Research Experience
======
My research can be divided into two main areas: planning and control for high-dimensional safety-critical systems and verification algorithms for neural networks. The overarching goal of my work has been to advance the deployment of safe autonomous systems which also incorporate learning components, such as feed-forward and convolutional neural networks. Potential application domains include autonomous vehicles, robotic manipulation, robust and verifiable machine learning, and safe reinforcement learning. Below I present a selection of different research topics I have explored:
* **Control and Reachability.** Computation of safety controllers and reachable sets in constraint and goal satisfaction problems for high-dimensional dynamical systems. In this line of work, neural networks are trained via approximate dynamic programming to emulate the optimal control policy and value function of the underlying Hamilton-Jacobi optimal control problem.
* **ML Verification and Robustness.** Computation of safety controllers and reachable sets in constraint and goal satisfaction problems for high-dimensional dynamical systems. In this line of work, neural networks are trained via approximate dynamic programming to emulate the optimal control policy and value function of the underlying Hamilton-Jacobi optimal control problem.
* **(Multi-agent) Planning.** Computation of safety controllers and reachable sets in constraint and goal satisfaction problems for high-dimensional dynamical systems. In this line of work, neural networks are trained via approximate dynamic programming to emulate the optimal control policy and value function of the underlying Hamilton-Jacobi optimal control problem.

Employment Record
======
* 2020-pres.: **Postdoctoral Scholar**, *UC Berkeley*
* 2018 (Summer): **Special Projects Group Intern**, *Apple*, Sunnyvale, CA
  * Planning for autonomous systems using expert demonstrations.
* 2014-2020: **Graduate Student Researcher**, *UC Berkeley*
* 2013 (Summer): **ICFO Summer Fellow**, *The Intitute of Photonic Sciences*, Barcelona, Spain
  * Worked in the development of a low cost, lens free flow cytometer based on wave field retrieval algorithms of fluorescent signals.
* 2012 (Summer): **Intern at CNM**, *National Center for Microelectronics*, Barcelona, Spain
  * Participated in the development of a low cost paper based microfluidic device for pregnancy detection.

Relevant Skills
======
* **Control theory:** Linear, Nonlinear, and Hybrid Systems, Stochastic Control, Optimal Control, Reachability Analysis, Differential Games etc.
* **AI and Machine Learning:** Dynamic Programming, Reinforcement Learning, Verification, Robustness, Convex and Nonconvex Optimization, Artificial Neural Networks, Decision Trees, Nearest Neighbors, Maximum Likelihood Estimation etc.
* **Programming:** Python, C++, Java, Matlab, ROS
* **Languages:** Spanish (native), Catalan (native), French (fluent) and English (fluent)

Publications
======
  <ul>{% for post in site.papers reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
