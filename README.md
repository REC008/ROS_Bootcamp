# ROS_Bootcamp
Repository that talks about all basic features of ROS as a part of ROS


​   1 . *What is ROS, its merits and limitations for Roboticists?* 

ans .  ROS is an open-source, meta-operating system for your robot. It provides the services you would expect from an operating system, including hardware abstraction, low-level device control, implementation of commonly-used functionality, message-passing between processes, and package management

**Merits** 
1. Peer-to-peer communication
2. Free and open-source
3. Thin
4. Multi-language 

**Limitation**
1. does not support multiple robots with the same master node
2. does not support real-time operation and thus not preferred for time-critical applications
3. Multi-robot/fleet management and interaction is not possible
4.  needs high-compute resources and network connectivity on-board for the best performance


​    2 . *Explain in your own words the basic ROS terminology:*

 i)   **Workspace**
 
ans . A workspace is a folder where you modify, build, and install packages

ii) **ROS package**

ans . Packages are the main unit for organizing software in ROS

iii)  **Nodes**

ans . Nodes are processes that perform computation. robot control system usually comprises many nodes

iv) **Topics**

ans . Messages are routed via a transport system with publish / subscribe semantics

v) **Messages**

ans .  Nodes communicate with each other by passing [messages](http://wiki.ros.org/Messages). A message is simply a data structure, comprising typed fields

vi) **Services**

ans . Request / reply is done via [services](http://wiki.ros.org/Services), which are defined by a pair of message structures: one for the request and one for the reply






19th 2020

   a. *What is a subscriber?*

ans. A node that wants to receive that information



   b. *What is a publisher?*

ans. A node that wants to share information



   c. *What is the function of :*

   i. **Roscore**

ans. collection of nodes and programs that are pre-requisites of a ROS-based system. A roscore running in order for ROS nodes to communicate

   ii. **Rosrun**

ans. rosrun allows you to use the package name to directly run a node within a package 

  iii. **Rostopic list**

ans. rostopic contains the rostopic command-line tool for displaying debug information about ROS topics, including publishers, subscribers, publishing rate and ROS messages.

  iv. **Rostopic echo**

ans. rostopic echo shows the data published on a topic

   v. **Rosmsg show**

ans. rosmsg is a command-line tool for displaying information about ROS Message types



20th 2020

   a. *What is the ROS navigation stack?*

ans. A 2D navigation stack that takes in information from odometry, sensor streams, and a goal pose and outputs safe velocity commands that are sent to a mobile base



b. *What is localization? What sensors are used for localization?*

ans. Robot localization is the process of determining where a mobile robot is located with respect to its environment.  data received from IMUs, wheel encoders, GPS, laser, radar, ultrasonic and vision software algorithms to implement SLAM techniques



 c. *What is the meaning of mapping?*

 ans. can create a 2-D occupancy grid map from laser and pose data collected by a mobile robot. 



   d. *What is tf in ROS and why is it needed?*

ans. tf is a package that lets the user keep track of multiple coordinate frames over time. 



   e. *What is the SLAM problem?*

ans. SLAM is the computational problem of constructing or updating a map of an unknown environment while simultaneously keeping track of an agent's location within it.











