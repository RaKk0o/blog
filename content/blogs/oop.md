---
title: "OOP"
date: 2020-12-04T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

A new company selling electronic components online is looking to develop its information system. Thus, we will have to create an application that will allow the company to manage its business processes.

## Problem

How to realize a solution allowing a company to manage its business processes?

## Achievements

First of all, we were able to read and understand the specifications that were given to us. Thanks to the different information available in the project specifications, we were able to create a data dictionary. This dictionary allows us to group together, and therefore to visualize more clearly, the different information that we will need in our database. Then, we realized several diagrams which aim to represent data as well as their links in an easily comprehensible way. Thanks to the information in the data dictionary, we were able to design different tables that group the information, and different links between the tables.

![MLD](/img/projects/oop/MLD.png)

Next, we made some other diagrams explaining how our application works. First of all, the user will click on a button on the system to either create, modify or delete a staff member (or any other management tool). As soon as he presses the button, it will send a request to the system so that it displays the list of personnel. Moreover, with this information the user will fill in the corresponding data of the form received to add or modify the staff member. For the city, the user will enter the address where the staff member lives and it will search the cities and the postal code that the user will choose. In addition, the user will validate the data he has filled in previously with the added city and zip code and this will send the confirmation request to the database. In addition, the database will record the information added or modified and will return the list of personnel to see if the addition or modification was successful. Then, the program will close itself by updating the received data.

To facilitate the use of the application to the user, we have integrated a graphical interface. For this we used "Winforms" and C++/CLR. We were then able to create several buttons that allow the user to make choices and navigate in the application, but also several "textbox" that allow the user to enter or modify data contained in the database. modify data contained in the database. In order to be able to see the data in our data in our graphical interfaces, we have set up "DataGridView".

![UI1](/img/projects/oop/menu.png)

![UI2](/img/projects/oop/gestion.png)

## Acquired skills

During this project, I learned a lot about linking a database to a program, but also about making a graphical interface, and especially about programming.