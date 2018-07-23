# Table of Contents
 * [Overview](#overview)
 * [C++ Developer](#c-developer)
 * [Java Developer](#java-developer)
 * [Python Developer](#python-developer)

***

# Overview

We are actively looking for C++, Python and Java developers to help us extend
the [MADARA](http://www.madara.ai) and [GAMS](http://www.gams.ai) middleware
for distributed artificial intelligence in
robotics. These contractors will be able to join daily standups and scrums
with our team members, ask questions and contribute to an active research,
development and engineering team that is tasked with building robotics
systems that must be reliable, mission-critical, and high performance in
outdoor environments.

In general, we are only interested in people who have years of experience in
developing well-documented, scalable and high performance code in C++, Java
and Python and can work well in a team environment. Read on for details about
the simple tests we have created to see if you will be able to quickly
integrate into our team and make impact.

***

# C++ Developer

Our main need is in C++ developers who can dive into well-documented code and
wikis, extract instructions, digest doxygen API information quickly, and get
things done. The following is a task that we would like to see done at a
minimum before we would consider contracting (est 1-4 hours):

 * Install the MADARA middleware with ZMQ enabled
 * Create a simple MADARA application that communicates between 2+ nodes using ZMQ TCP transport protocol
   * Create a github that we can access to look at your code and documentation
   * Use MADARA containers in the madara::knowledge::containers namespace to access and mutate knowledge in the KnowledgeBase
   * Use KnowledgeBase::send_modifieds to send data
   * Be creative and feel free to explore the features
   * Save knowledge to a file as either karl, JSON, or binary
   * BONUS: Create an on-receive filter that reacts to knowledge changes over the network
   * Share the URL to your github and be sure to document your work (especially any installation process we would need to know to run your code). We appreciate this being in a README.md in the root of your github project. Doxygen commenting is especially appreciated.
   * Feel free to share/document any issues you have using MADARA or GAMS and what needs to be improved

Wiki Pages of Interest: [Installation](https://github.com/jredmondson/madara/wiki/Installation) | [Containers](https://github.com/jredmondson/madara/wiki/KnowledgeContainers) | [Knowledge](https://github.com/jredmondson/madara/wiki/InteractingWithTheKnowledgeBase) | [Networking](https://github.com/jredmondson/madara/wiki/InteractingWithTheTransport) | [C++ API Documentation](https://madara.readthedocs.io/en/latest/?badge=latest)

***

# Java Developer

Our main need in Java developers are people who can work with Android and
create tools, interfaces, and extend our JNI port. The following is a task
that we would like to see done at a minimum before we would consider
contracting (est 1-4 hours):

 * Install the MADARA middleware with Java enabled (Android if you want to create an APK)
 * Create a sample Java application or Android application that uses MADARA
   * Create a github that we can access to look at your code and documentation
   * Use MADARA containers in the ai.madara.knowledge.containers package to access and mutate knowledge in the KnowledgeBase
   * Use KnowledgeBase.sendModifieds to send data across the network (Multicast or ZMQ)
   * Be creative and feel free to explore the features
   * Save knowledge to a file as either karl, JSON, or binary
   * BONUS: Create an on-receive filter that reacts to knowledge changes over the network
   * Share the URL to your github and be sure to document your work (especially any installation process we would need to know to run your code). We appreciate this being in a README.md in the root of your github project. Javadocs are always appreciated.
   * Feel free to share/document any issues you have using the Java port and what needs to be improved

Wiki Pages of Interest: [Installation](https://github.com/jredmondson/madara/wiki/Installation) | [Containers](https://github.com/jredmondson/madara/wiki/JavaKnowledgeContainers) | [Knowledge](https://github.com/jredmondson/madara/wiki/JavaInteractingWithTheKnowledgeBase) | [Networking](https://github.com/jredmondson/madara/wiki/JavaInteractingWithTheTransport) | [Java API Documentation](http://javadoc.io/doc/ai.madara/madara)

***

# Python Developer

Our main need in Python developers are people who can work with Boost.Python
or create tools, interfaces, and extend our Python port and create new, useful
features for AI developers and analytics engineers to take advantage of.
The following is a task that we would like to see done at a minimum before
we would consider contracting (est 1-4 hours):

 * Install the MADARA middleware with Python enabled
 * Create a sample Java application or Android application that uses MADARA
   * Create a github that we can access to look at your code and documentation
   * Use MADARA containers in the `madara.knowledge.containers` module to access and mutate knowledge in the KnowledgeBase
   * Use KnowledgeBase.sendModifieds to send data across the network (Multicast or ZMQ)
   * Be creative and feel free to explore the features
   * Save knowledge to a file as either karl, JSON, or binary
   * Share the URL to your github and be sure to document your work (especially any installation process we would need to know to run your code). We appreciate this being in a README.md in the root of your github project.
   * Feel free to share/document any issues you have using the Python port and what needs to be improved

Wiki Pages of Interest: [Installation](https://github.com/jredmondson/madara/wiki/Installation) | [Containers](https://github.com/jredmondson/madara/wiki/PythonKnowledgeContainers) | [Knowledge](https://github.com/jredmondson/madara/wiki/PythonInteractingWithTheKnowledgeBase) | [Networking](https://github.com/jredmondson/madara/wiki/PythonInteractingWithTheTransport) |Python API Documentation (`help ('madara')`)


