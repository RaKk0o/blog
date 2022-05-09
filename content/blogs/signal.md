---
title: "Signal"
date: 2020-05-27T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

Agent K17 has infiltrated the secret base of major web hackers and managed to steal information from them but unfortunately is stuck in a conference room. He must transmit the information and send the emergency code "ESCAPE K17" without being detected. 

## Problem

How to pass a message that must be undetectable through a microphone used by a a third party?

## Achievements

We started by studying the sound in a general way, and deduced that all the frequencies were not audible by the Man, and that these frequencies leave a trace called spectrum which can be obtained from a sound signal. Thus, even a frequency inaudible by humans will leave a trace in the sound signal.

However, the frequency response varies from one microphone to another. Indeed, it determines the frequencies that the microphones can detect.

We therefore started by proposing several solutions, in particular that a way for the K17 agent to transmit a message would be to record the information and the emergency code that he must transmit beforehand, then to program a simple software that would allow to increase the frequency of the sound of his recording. He would then only have to play this modified sound during a conference. Indeed, by increasing the frequency sufficiently, the human ear will no longer be able to hear the message, however, the microphone will still be able to pick it up if the frequency is not too high and then retranscribe it into a sound signal.
This is the option we have chosen.

First of all, the K17 agent sends information through the microphone in the form of a wave. Moreover, thanks to a software, it will modulate the wave, as well as carry out sampling (with quantization and encoding in Manchester). In addition, the agent will then emit the wave (thanks to the computer) received by the microphone during the conference. In addition, the wave will be sent in the network to be received by another agent, via his computer. Moreover, in order to be able to read the message or the files received, he will filter the wave (thanks to a band-pass), to then decode and demodulate it, in order to be able to read demodulate it, to be able to finally read the information.

To finish, we realized the program in python.

## Acquired skills

During this project I learned a lot about sound, but especially about programming thanks to the use of Python.