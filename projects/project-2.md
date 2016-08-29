---
layout: project
type: project
image: images/scel.png
title: SCEL Instrumentation Device
permalink: projects/vacay
date: 2016
labels:
  - Python
  - Arduino
  - Qt
summary: Worked in a small team to develop an Instrumentation device for the Smart Campus Energy Lab (SCEL) focusing on current and voltage logging.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/Instrumentation1.png">
  <img class="ui image" src="../images/Instrumentation2.png">
  <img class="ui image" src="../images/scel.png">
  <img class="ui image" src="../images/Instrumentation3.png">
</div>

The [Smart Campus Energy Lab (SCEL)](http://scel-hawaii.org/) at the University of Hawaii at Manoa focuses on the design and development of low-cost, accurate, and reliable environmental sensor modules that can easily be reproduced for mass deployment on rooftops across the University of Hawaii at Manoa campus. To aid in their development, our team was tasked with developing an in-house data logger to assist SCEL students in conducting their analysis of their components and boards.

I lead the firmware development of the project, where my main focus was handling the communication between the board and the computer. I used serial communications to transmit the data being received on the board to the computer where it could then be processed and handled to be displayed to the user.

This project provided a great opportunity to gain more experience with Python and embedded systems development.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).
