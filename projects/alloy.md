---
layout: project
type: project
image: images/alloy-icon.png
title: Alloy Web Application
permalink: projects/alloy
date: 2016
labels:
  - Web Application
  - Meteor
  - Javascript
  - Semantic UI
  - MongoDB
summary: Bringing dream teams together at UH! Alloy is an application for matching the right people to the right projects.
---

<img class="ui medium right floated rounded image" src="../images/alloy-wordmark.png">

Alloy is a web application designed for a Software Engineering course at the University of Hawaii. It serves as a tool to help members of the University of Hawaii community make their project ideas become a reality. Alloy provides its users with a method of connecting people to projects by allowing people to post their projects which can be seen by the entire Alloy userbase. Within the web application users can also invite people to their projects, and search for interesting projects they would like to become a part of. To put it simply, Alloy bridges the gap between people who have great project ideas and people who want to work on great projects.

There were five contributors working on the development of Alloy in the Fall 2016 semester. My main contributions to the application centered around implementing project creation and incorporating user memberships of the projects. With project creation, I was tasked with developing a page within our app allowing a user to provide information about their project so that it can be posted. This required using a few Semantic UI elements such as forms and dropdowns to provide a user friendly experience to creating their project. I also worked on the membership management aspect of the projects. I elected to provide administrators of projects the ability to manage the members within a project. They are able to remove members, escalate other members to administrative level, allow other users to join the project, and invite users to join the project. With this I needed to incorporate a system of requests/notifications. I implemented a system where users are able to request to join an existing project and the project admins can review these requests and either accept or reject people into their project. I also added the feature of project admins inviting users to join their project. These invitations would go to the user where they can be either accepted or rejected. These were the main components I focused on developing.

<img class="ui large right floated rounded image" src="../images/profject-profile-final.png">

[Check out the project here!](https://alloyteams.github.io/)
