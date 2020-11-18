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











