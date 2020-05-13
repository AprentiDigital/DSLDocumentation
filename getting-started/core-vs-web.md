---
layout: default
title: Core vs. Web
parent: Getting Started
nav_order: 7
---

## Core vs. Web vs. English

The Possum Labs DSL project is broken up into a number of different packages. This allows you to integrate at the level you prefer without needing to take everything. A big reason for this seperation is that we utilize Selenium and that is a large dependency.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Nu5BkWbZk6Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Core

The core package has the logic for dealing with variables. It has the least dependencies.

### Web

The web package has a dependency on selenium.

### English

The English project has default implementations for simple stesps and has a dependency on Specflow. 

### Wich one should you use?

Use English when getting started. 

If you are worried about dependencies, or there is a conflict you can utilize the lower level packages.

If you work in a langauge other than english the advice is to still do a prototype in english package and then replace that with your desired langauge.

If there is a package in your perferred langauge then by all means use that.