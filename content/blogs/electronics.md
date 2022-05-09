---
title: "Electronics"
date: 2019-11-22T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

The MI7 spy agency asked us to work on a new generation safe with increased authentication mechanisms. Thus, there would be several electronic cards with their own number. These cards could then activate the authentication system, which is composed of several authentication levels.

## Problem

How to make a card able to secure authentication?

## Achievements

We started by making a logigram corresponding to the different cards linked to a certain authentication level. Thus, depending on the card recognized, several levels of authentication will be activated according to the cases determined by the card.

![Logigram](/img/projects/electronics/logigram.png)

Then, we realized the prototype of the safe, so we used an Arduino board and an 8 bits dip switch.

![Prototype](/img/projects/electronics/proto.png)

Then we made a program with several parts: 
- A part declaring the variables. 
- A part of initialization and configuration of inputs and outputs.
- A main part that runs in a loop with what the program must execute. 
- A part of initialization and configuration of the functions which are called in the main part

This program was running on a test prototype.

## Acquired skills

During this project, I was able to acquire skills in schema modeling and logigram. But also in programming since we used Arduino.