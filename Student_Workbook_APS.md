##### Name:  Akarsh Pallassana Sivaprasad

###### Date:    09/16/2018


# Introduction to ROS -- Self Study

---

- Use this document to help you study.
- For each item, make a list of questions that you have.  Identify all of the things that don't make sense to you.  Clearly denote these as questions.
- Also, make notes when you have answered a question.  Clearly denote these as things that you now understand.
- In the end, you should have no unanswered questions.

- This document is written in *markdown*.  It's a great language for documentation.  Here's a cheatsheet for you:  https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

- You will be asked to turn in paper copies of your compiled document.  Please make sure it's neatly formatted.  I suggest using the 
`remarkable` software package that is already installed on your virtual machine.

---

## Textbook Chapters (Book PDF Available)

### Chapter 1 -- Introduction (READ)

Just read this chapter...**DO NOT INSTALL ANYTHING**. Your virtual machine already has the software loaded and configured for you.  


- Unanswered Questions 
  - How ROS can work as a Peer to Peer system?
  - Does ROS allow Multilingual programming?

- Answered Questions and/or General Notes
  - What is ROS
  - Early Development
  - How to Install
  - Installation Scripts
  - Software Library and Packages collection
  - ROS is a Lite System

---

### Chapter 2 -- Preliminaries (READ)

Just read this chapter...**DO NOT INSTALL ANYTHING**. Your virtual machine already has the software loaded and configured for you.  

- Unanswered Questions
  - 1. How the various subsystems of ROS like CV and Navigation work?
  - What does CATKIN stand for?
- Answered Questions and/or General Notes
  - ROS Network
  - ROS Run
  - Names and Remapping
  - Namespaces (/ to Delimit Spaces)
  - ROS Launch (Automatically Launch a Collection of ROS Nodes)
  - TAB Key to Auto Complete Commands
  - ROS Core (Nodal and Peer to Peer Systems)
  - CATKIN (root)

---

### Chapter 3 -- Topics

- Unanswered Questions
  - Can you explain how a Bi-directional Callback works between nodes?
- Answered Questions and/or General notes
  - Publish and Subscribe 
  - Topics must be of the same data type
  - Publishing Interval
  - Built-in Message Types
  - Defining Custom Message Types

---

### Chapter 4 -- Services	

- Unanswered Questions
  - What is a Service and its components (Calls, Inputs and Outputs)
  - Ho to Implement a service
  - How a service can be called with proxy
- Answered Questions and/or General notes
  - It is a way to pass data in the ROS Network
  - Other ways to return values from a service

---

### Chapter 5 -- Actions

- Unanswered Questions
  - Defining an Action
  - How to use an Action
- Answered Questions and/or General notes
  - Actions are faster than Services (Ideal for Robots)
  - Action Goals / Result / Feedback

---

## ROS Tutorials

### 1)  [Navigating the ROS Filesystem](http://wiki.ros.org/ROS/Tutorials/NavigatingTheFilesystem)

This tutorial introduces ROS filesystem concepts, and covers using the roscd, rosls, and rospack commandline tools.

- Unanswered Questions
  - NONE
- Answered Questions and/or General notes
  - Difference between roscd / rosls / roscpack with the generic terminal commands


### 2)  [Creating a ROS Package](http://wiki.ros.org/ROS/Tutorials/CreatingPackage)

This tutorial covers using catkin to create a new package, and rospack to list package dependencies.

**IN SECTION 4, DO NOT ADD THE WORKSPACE TO YOUR ROS ENVIRONMENT:**

> ~~$ . \~/catkin_ws/devel/setup.bash~~ 

*This has already been done for you in your virtual machine.*


- Unanswered Questions
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified
- Answered Questions and/or General notes
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified


​				
### 3) [Building a ROS Package](http://wiki.ros.org/ROS/Tutorials/BuildingPackages)

**IN SECTION 1, DO NOT DO THIS:**
> ~~# source /opt/ros/\<YOUR_ROS_DISTRO\>/setup.bash~~

> ~~$ source /opt/ros/kinetic/setup.bash             # For Kinetic for instance~~

*This has already been done for you in your virtual machine.*


- Unanswered Questions
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified
- Answered Questions and/or General notes
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified


### 4)  [Understanding ROS Nodes](http://wiki.ros.org/ROS/Tutorials/UnderstandingNodes)

This tutorial introduces ROS graph concepts and discusses the use of roscore, rosnode, and rosrun commandline tools.		

**IN SECTION 1, DO NOT DO THIS:**
> ~~$ sudo apt-get install ros-\<distro\>-ros-tutorials~~

*This has already been done for you in your virtual machine.*


- Unanswered Questions
  - Does rosnode concept follow the master slave protocol?
- Answered Questions and/or General notes
  - Working with roscore and rosrun


### 5) [Understanding ROS Topics](http://wiki.ros.org/ROS/Tutorials/UnderstandingTopics)

This tutorial introduces ROS topics as well as using the rostopic and rqt_plot commandline tools.

**IN SECTION 2.1, DO NOT DO THIS:**
> ~~$ sudo apt-get install ros-\<distro\>-rqt~~

> ~~$ sudo apt-get install ros-\<distro\>-rqt-common-plugins~~

*Your virtual machine already has these things installed.*


- Unanswered Questions
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified
- Answered Questions and/or General notes
  - As we Executed Talk / Listener and Custom Message Packages in class all my questions were clarified


### 6)  [Understanding ROS Services and Parameters](http://wiki.ros.org/ROS/Tutorials/UnderstandingServicesParams)

This tutorial introduces ROS services, and parameters as well as using the rosservice and rosparam commandline tools.

- Unanswered Questions
  - UNEXPLORED
- Answered Questions and/or General notes
  - UNEXPLORED


### 7)  [Creating a ROS msg and srv](http://wiki.ros.org/ROS/Tutorials/CreatingMsgAndSrv)

This tutorial covers how to create and build msg and srv files as well as the rosmsg, rossrv and roscp commandline tools.

- Unanswered Questions
  - What are srv files?
- Answered Questions and/or General notes
  - How to create a custom ROS message


### 8a)  [Writing a Simple Publisher and Subscriber (Python)](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29)

This tutorial covers how to write a publisher and subscriber node in python.

- Unanswered Questions
  - NONE
- Answered Questions and/or General notes
  - I understood this as we executed the Talk-Listen package.


### 8b)  [Examining the Simple Publisher and Subscriber](http://wiki.ros.org/ROS/Tutorials/ExaminingPublisherSubscriber)

This tutorial examines running the simple publisher and subscriber.

- Unanswered Questions
  - NONE
- Answered Questions and/or General notes
  - NONE


### 9a)  [Writing a Simple Service and Client (Python)](http://wiki.ros.org/ROS/Tutorials/WritingServiceClient%28python%29)

This tutorial covers how to write a service and client node in python.

- Unanswered Questions
  - How to define and implement service in ROS?
- Answered Questions and/or General notes
  - NONE


### 9b)  [Examining the Simple Service and Client](http://wiki.ros.org/ROS/Tutorials/ExaminingServiceClient)

This tutorial examines running the simple service and client.

- Unanswered Questions

  - NONE

- Answered Questions and/or General notes

  - NONE

---

## Textbook Github Site

Please take a few moments to familiarize yourself with these resources:

- https://github.com/osrf/rosbook
- https://github.com/osrf/rosbook/issues?utf8=✓&q=
- https://www.oreilly.com/catalog/errata.csp?isbn=0636920024736

These will come in handy throughout the semester.


