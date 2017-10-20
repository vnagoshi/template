---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

<img class="ui small centered image" src="{{ site.baseurl }}/images/meteorLogo.jpg">

The Meteor web application building platform lets you efficiently create web applications by giving you access to a wide range of practical packages and tools. These tools come premade to easily build complex web features using only a few intuitive lines of code. Meteor also comes with a live update feature which makes viewing changes you have made to your web app automatic, lessening the chance of human error during development. While Meteor is a great platform for building a web application, its breadth and scope give it a few learning pains.

Meteor sets up an intuitive file structure and organization for your application, however you have to import files between one another, and tracing your imports is a royal pain. If you forget to import a file in just one place in your application, your entire application will likely not render or function as intended. This issue is made worse the larger your application becomes and the more files become reliant on other files throughout the app. The most effective solution for this problem is to trace your imports from the lowest level source up to its highest level importer, and checking all dependencies of said source for the import, however this is not an overly efficient process, though it is effective. Doing this process does have the benefit of making you very well learned in the internal architecture of your application.

Another problem is apparently caused by OS, namely Windows, where extracting meteor takes an exorbitant amount of time. Installing meteor involves running the setup exe then checking back in a half hour to an hour to see if it successfully managed to extract the library. This problem also occurs when installing a large number of packages; Meteor will spend maybe three or four minutes downloading the missing packages, then spend hours extracting them during the initial startup of some applications. Unfortunately I have yet to find a Windows native solution for this issue.
