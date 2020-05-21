---
layout: default
title: Contribution Guide
nav_order: 7
---

# Contribution Guide

Welcome to the contribution guide. There are several different ways you can help make this project better—first, report bugs. 

## Bugs
There are bugs in this code, I mean we don't know where they are, but there is too much code for there not to be bugs. So when you see something that looks like a bug, let us know.  The artifacts we would love to have are stack traces, expected behavior, and reproduction projects if you have the time. 

If you have a flaky or non-reproducible bug, please still let us know. We might not be able to fix it with the information we get from you, but it can combine with data from other users to help us track the issues down.

## Feature requests
This project has the solutions to the shared testing problems between a few systems. This sample size means that many other common issues are a good fit for the PossumLabs.DSL project. We can't promise that we will be able to implement them all, but we'd love to hear about any ideas. 

Feature requests do not have to be limited to functionality and can include requests for tutorials or documentation.

We will prioritize features based upon ease, fun, perceived value, and how well they fit the DSL testing idea. 

## Code Reviews
A large part of the PossumLabs.DSL project was written by one person without collaboration. This lack of feedback is a known weakness of the project, and there are areas where the solutions to the problem are not optimal. So if you are willing to take the time to review part of the code and provide feedback, it would be greatly appreciated. 

It is always easier to understand feedback with context, so if you could share examples of where a particular pattern caused issues, it would be appreciated. 

## Contributing Code
First off, take a look at the code and see if you want to work on this codebase. There are video introductions below for the separate projects to help you get started. The second thing you need is something you want to implement. Feel free to reach out to bas@possumlabs.com to set up some time to discuss the plan if you'd like. 

From a code perspective, we care about a few things. First of DRY, Don't Repeat, Yourself. If you find yourself copy-pasting code assume that it violates DRY. The second is the Single Responsibility Principle; if you can't describe what a class or method does without using "and" you probably violate it. Last name things well; this should be easier once the Single Responsibility Principle has been honored. There are many other great practices and use the ones you like. 

The goal is to keep the code pretty and fun to work on while keeping tests written using PossumLabs.DSL passing. 

## Code of conduct
We'll add one when we have to; hopefully, this is never. 

### Videos

#### PossumLabs DSL Contribution Guide: Intro

<iframe width="560" height="315" src="https://www.youtube.com/embed/f1b5pm4rBLU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### PossumLabs DSL Contribution Guide: PossumLabs DSL Core

<iframe width="560" height="315" src="https://www.youtube.com/embed/WS-ze5fXJAA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<feeback>
