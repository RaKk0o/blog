---
title: "Data Base"
date: 2020-04-03T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

Hephaestus makes legendary weapons and equipment, and with the help of Hermes, his business is flourishing. Hermes wanted to establish himself in Egypt and managed to take over the administration and management of Hephaestus' sales. He then wishes to exploit the data collected by Hephaestus during the last centuries in order to increase the sales.

## Problem

How can Hermès increase sales?

## Achievements

We started by creating an algebraic model. Indeed we had to go from a database realized on Excel, to a clean database with MySQL.
Then we realized a logical data model. This one is used to describe the structure of a database so that it is understandable by the greatest number. It is thus a question of carrying out the logical data model starting from a conceptual data model obtained. The transcription from one to the other is done by following a few simple rules which consist in first transforming any entity into a table, with the identifier as primary key, then observing the values taken by the maximum cardinalities of each association to represent it either by adding a foreign key in an existing table, or by creating a new table.
Once our structure was defined, we were able to create our new database. To fill our database from the Excel files provided, we must first convert it into SQL language. To do this we convert our Excel files to CSV (Comma Separated Values) format. This format can then be transformed directly into SQL language. Then we just have to import the obtained files into the database.
Once our database was filled, we were able to make SQL queries. Thus we were able to get information answering our problem, and to study them.

## Acquired skills

During this project, I was able to learn how to model, to use a database management system and to use the SQL language.