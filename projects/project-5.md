---
layout: project
type: project
image: images/rgbstudios.png
title: Manoa Marketplace
permalink: projects/manoa-marketplace
date: 2017
labels:
  - Web Development
  - Meteor
summary: A web based used wares trading space for UH Manoa students
---

<img class="ui image" src="{{ site.baseurl }}/images/manoa-marketplace-home.png">

# Program Overview

Manoa Marketplace is a Meteor based web application designed to allow students at UH Manoa the ability to buy and sell used goods through a campus service. Students must login into the marketplace using their UH login for verification purposes. They can then post listings to the marketplace, specifying the sale item as well as the price they will sell at. In addition students can browse through all of the listings on the marketplace, either by browsing full categories or by searching for key terms in a listing's name. Students inquire about any item they would like to purchase through Manoa Marketplace's messaging service. From there sellers contact the buyer via his or her email. All transactions on Manoa Marketplace must occur on campus.

# Team Contribution

Manoa Marketplace was developed collaboratively with <a href="https://mhsakuda.github.io/" target="_blank">Mitchell Sakuda</a> and <a href="https://jessieflores.github.io/" target="_blank">Jessie Flores</a>. My role in development took on primarilly the back-end functionality of the program. I hooked up the default Meteor Mongo database to the pages and forms that required them, figured out proper page routing, built the admin and messaging systems, and generally sorted out any complications the team ran into stemming from Meteor's behavior. I also built some pieces of the front-end including the header and overall page themimg and a lot of bug testing and fixing.

Developing Manoa Marketplace in a collaborative environment forced me into learning how to read into the thought process behind code. Sometimes the commit descriptions or inline documentation was simply lacking when reading through collaborator's code (I myself was part of this problem to an extent) so it became useful to be able to read code, understand what the code did, as well as understand what the code was supposed to do quickly in order to determine if it needed a fix. As I worked mostly on back-end functionality, I gained a strong knowledge of how Mongo collections oporate as well as how to manipulate and publish them. I also gained a stronger knowledge of HTML page events as well as how to capture and differentiate said events within Meteor's templating.

<hr>
Project Home: <a href="https://manoa-marketplace.github.io/">manoa-marketplace.github.io</a>