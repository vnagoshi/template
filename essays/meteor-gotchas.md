---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

//<img class="ui tiny left floated image" src="{{ site.baseurl }}/images/learn-javascript.png">

Meteor sets up an intuitive file structure and organization for your application, however tracing your imports is a royal pain. If you forget to import a file in just one place in your application, your entire application will likely not render or function as intended. This issue is made worse the larger your application becomes and the more files become reliant on other files throughout the app. The most effective solution for this problem is to trace your imports from the lowest level source up to its highest level importer, and checking all dependencies of said source for the import, however this is not an overly efficient process, though it is effective.

Placeholder
