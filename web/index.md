---
layout: default
title: Web Tutorials
nav_order: 4
has_children: true
---

## DSL.Web Tutorials

The tutorials fall into up into three sections, Core for the parts dealing with variables, Web for interacting with webpages, and Advanced that talks about replacing components of the framework. This section covers the tutorials for working with websites.

We will be relying on the English package for these tutorials. 

The tutorials will cover what is provided in the PossumLabs.DSL library for interacting with webpages. These are very generic low-level steps for interacting with websites, along the lines of clicking and entering data. It will act similarly to some frameworks that depend on AI, except we leverage xpaths that are evaluated behind the scenes. Chances are you won't need to worry about how it works, and you will be able to refer to elements on the page by the visible test without creating any page objects.

This way of referencing elements is a small time-saving upfront and much larget when pages change, and you have to maintain the page objects. It also may allow you to work with most web pages that were never built for interaction with selenium and automated testing. 

Just because you can reference elements, you should still try and limit doing so in scenarios to keep them concise and readable. A few lines of clicking and entering text is easy to follow, but once you have more than five lines of it, people get lost. In those cases, you can create steps that alias those entering and clicking steps below the hood.   