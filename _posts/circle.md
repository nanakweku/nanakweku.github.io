---
title: lesson 4
date: 2022-12-04 12:00:00 -500
categories: [circleci, Git, Github,Marist]
tags: [lessons,git,github,circleci]
--- 


# Introduction to CircleCI 



* CircleCI is a continuous integration and continuous delivery platform that can be used to implement DevOps practices. 

* CircleCI runs each job in a separate container or virtual machine. CircleCI then sends an email notification of success or failure after the tests complete. CircleCI also includes integrated Slack and IRC notifications.

# Primary process that is used in CircleCI to build the code

* executor: adjusting the VM to the preferences and requirements it can be machine, docker or and many more related to the OS
* checkout: git repo checking out and cloning feature
* dependencies: setting up your project’s language-specific dependencies
* code: preparing the code for your tests
* test: running your tests
* deployment: deploying your code to your web servers
