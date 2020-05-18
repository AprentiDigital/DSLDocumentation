---
layout: default
title: Core vs. Web
parent: Getting Started
nav_order: 7
---

## Core vs. Web vs. English

The Possum Labs DSL project is broken up into several different packages. This separation allows you to integrate at the level you prefer without needing to take everything. A big reason for this separation is that we utilize Selenium, and that is a large dependency.

### Core

The core package has the logic for dealing with variables. It has the least dependencies.

### Web

The web package has a dependency on Selenium.

### English

The English project has default implementations for simple steps and has a dependency on Specflow. 

### Which one should you use?

Use English when getting started. 

If you are worried about dependencies or there is a conflict, you can utilize the lower-level packages.

If you work in a language other than English, the advice is to do a prototype with the English package and then replace that with your desired language.

If there is a package in your preferred language, then, by all means, use that.