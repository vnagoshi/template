---
layout: essay
type: essay
title: Server Refreshing
date: 2017-10-26
labels:
  - Software Engineering
  - Meteor
---

Meteor is a web application framework that allows programmers to structure their applications intuitively and access a plethora of external packages that bring often advanced web features to the application with minimal effort. Meteor focuses around a more dynamic means of building web applications with pages partitioned into templates and few if any static links. Meteor is pretty simple to pick up, however, due to its size and robustness, Meteor is quite a challenge to actually understand and master.

### Minor Gripes

There is a pretty steep learning curve for Meteor when actually trying to modify anything, a wall even. Meteor has decent documentation, however, due to the wide breadth of all of its packages and applications, there are few learning sources that can adequately explain both everything and every use. There ends up being a lot of trial and error when trying to integrate new features into a Meteor application. Sometimes it runs smoothly on the first go, and sometimes is breaks for no obvious reason.

Meteor is also not the most flexible of frameworks to write in. Every package and feature has a specific way it wants to be invoked in and if something violates that, typically the feature breaks and it may take the app down with it. Considering how flexible JavaScript is and to a lesser extent HTML, the strictness of Meteor when writing a web application is a bit off putting.

### Blind Programming

The largest problem I have with Meteor is its compile times. It can takes a long time for Meteor to compile an application, especially if it’s the first compilation for an application relying on a large number of external packages. During the first compilation, Meteor has to download and extract any non-local packages which takes a while to understate a little. Meteor compiles much quicker after the initial compilation, however it still typically floats around thirty seconds which when compared to the near instantaneous update times of static pages is a pretty long time

My typical workflow when developing projects for the web looks something along the lines of “change a few lines in the source code, save, refresh the page, and repeat”. The problem is with Meteor I have to add in “wait for Meteor to compile” right after “save”. Even when Meteor compiles quickly (sub 30 seconds), this wait time adds up, leading to a substantial amount of time spent not actually working on the code but instead staring at the console. This aspect of Meteor causes the blind programming issue. Essentially since waiting for Meteor to compile ends up being so time consuming in the long run, the rational is to keep modifying the code without waiting for the compile to complete as its just more time efficient. The programmer ends up saving time not constantly having to wait for compilation, however, they are also unable see what their modifications to the code actually do to the page and are thusly coding blind. This is fine if you do not make any mistakes, but if you did make a mistake, you often won’t know about it until you actually due hit a “stopping point” and wait for compilation to complete.

### Overall

All in all, Meteor’s vast array of packages makes up for the framework’s flaws. The ability to quickly do complicated tasks like logins and dynamic links with minimal effort is ultimately more efficient than trying to implement them yourself. While there ends up being a lot of dead time when developing in Meteor, it would have taken much more time to try to write those features yourself. There is a large amount to learn, but once you get used to it, Meteor lets you get a lot of complicated stuff done in a relatively short amount of time.
