---
layout: default
title: Glossary
nav_order: 8
---

# Glossary
{: .no_toc }

## Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

### Anti-corruption layer

An anti-corruption layer is a form of insulation that protects tests from needing to change when changes are made to the application that is being tested. Most applications change, evolve, and are refactored over time. When the application changes, an anti-corruption layer means that the tests will need few (if any) changes.

With DSL testing, tests are written in a human-readable format that is resolved to code behind the scenes. The underlying test framework and the core application being tested can both change without needing to rewrite the tests themselves (in most cases).

### Application programming interface (API)

An API is a piece of software that handles communication coming from other programs. REST and GraphQL are technologies that are used to implement APIs.

### Attribute

Attributes are a C# concept similar to "tags" in Gherkin. They are non-functional documentation elements that other systems may interpret. 

Think of them as hashtags in tweets, but for code.

### Behavior-Driven Development (BDD)

BDD is a development methodology that was introduced around 2008 to help developers know exactly what they need to build. It helps with the practice of creating a specification before implementation. These specifications are in a form that are both machine-parsable and human-readable, which means the specifications act as the acceptance tests for the development work.

### Bounded context

Words have meanings within a context. For instance, when you are talking about cars, "gas" refers to gasoline, whereas in a physics class, "gas" means a state like solid or liquid. A bounded context defines a set of related things. Within Domain-Driven Design (DDD), a bounded context is a pattern that helps deal with large models by breaking up them up into parts.

This also applies in large organizations, where as the UI team has a clear idea of what and "account" is, but the CFO has a different meaning for "account".

When creating a Domain-Specific Language, it's important to be clear what is in or out of context to minimize confusion. This may mean that in large organizations you will need multiple bounded contexts and multiple Domain-Specific Languages.

### Container

For our purposes a container is a virtual machines inside of Docker. 

### Context Map

A Context Map is produced by using Context mappting, which is a tool that allows you to identify the relationship between bounded contexts and the relationship between the teams that are responsible for them.

### Cucumber

A interperter implementation of Gherkin. Specflow is also an interperter of Gherkin. This is the part that reads the feature files are triggers the code for scenario execution.  

### Docker

Docker is a tool that makes it possible to run multiple, isolated copies of applications at the same time. It has less overhead than running individual virtual machines for each application, because all the containers running the applications share a single operating system kernel. Automated tests for websites will run faster if you can run them in multiple instances of browsers at the same. Docker makes that possible. When running browsers in Docker for the purpose of testing, the browsers are often run in a headless state.

### Domain

An organizational construct to group concepts; much like a king has a domain that contains subjects and assets. In our context it refers to ideas, processes, and concepts.

### Domain-Driven Design (DDD)

A set of practices that focus on placing the problem that the business solves at the center of the software. By utilizing the language and concepts of the business in the implementation you reduce the risk of mistakes.

This is in contrast to implementations that focus on the technology, and may colapse multiple business concepts into single entity for efficiency. 

### Domain-Specific Language (DSL)

A domain-specific language is a limited-use language made up of words that have meaning within a certain context. That context, or domain, is often a product, business, or workflow. The words in a domain-specific language can be combined and used to accomplish specific tasks. Alexa, Cortana, and Siri are examples of domain-specific languages: you can interact with them in simple, scripted ways to accomplish tasks.

### Dot notation

This is a common way of accessing variables in programming languages. Lets say we have a dog called "Loebas", and we want to get the color of his coat; this would read as Loabas.Coat.Color in dot notation.  

### Enterprise service bus (ESB)

A system that uses messages that are broadcast, and subscribed to by software components. This is in contrast to sending infomration to specific locations via API calls.

It is the software equivalent of the bloodstream, lots of hormones are places into the bloodstream by some organs and then acted upon by others. This is in contrast to the nervous system where the information is send to specific locations.

### Entity/Entities

The mouns that are the most meaningful in your oganization, these can be things like Customer, Order, Shipment, Wiget, etc.

### Feature

An organizational unit for scenarios that wish to share a background. It is also the unit at wich sceanrios are presisted on disk. So your feature files will contain your scnearios. 

### Gherkin

A set of simple grammar that in english consistes of the Given, When, Then syntax. This syntax is what is interperted by Cucumber and Gherkin.

### Git

Git is a free, open source tool for source control management. It is primarily used in software development for tracking changes to source code, and it can be used and managed via the command line or any number of third-party applications that provide graphical user interfaces.

### Headless

Running software headless (e.g. running a browser headless) means running it without its graphical user interface. When running browsers in containers for automated testing, the graphical user interface isn't usually necessary, because there isn't a person watching every single test play out. Despite running headless, it's still possible to record screenshots of the tests that can be reviewed after the test is over.

### Keywords

These are reserved words in programming langauges that have specific meaning. For instance in Gherkin Give, When and Then are keywords. When these words are used in specific contexts they will be interperted to trigger functionality. 

### Model

An abstraction of data and processes that is useful for communicating with people or software. 

### Model-Driven Design (MDD)

An analythical process where you will describe the software using many models. It focuses less on the business comapred to Domain Driven Design, but there is overlap.  

### Mono

[Mono](https://www.mono-project.com/) is an open source implementation of Microsoft's .NET Framework that makes it possible to develop cross-platform applications. Supported platforms include Windows, MacOS, Linux, and [others](https://www.mono-project.com/docs/about-mono/supported-platforms/).

### .NET, .NET Standard, and .NET Core

.NET is a framework that is used to create Windows applications. .NET Standard is a set of APIs that all .NET implementations must use. .NET Core is an open source, cross-platform implementation of .NET Standard. While .NET is only used to develop Windows applications, .NET Core can be used to develop applications for all major operating systems, including Windows, MacOS, and Linux. The PossumLabs.DSL example project is compatible with .NET Core.

### Open Source

This refers to software where the source code is available for inspection and compilation. This allows developers to dive in and understand exacty how the code works even if they work for a different organization. It also allows people to contribute to these projects.

It is a bit like Wikipedia except that there is an approval process for changes that is amnaged by the owners of each individual project.

### Property

A data attribute of an object. For instance a drivers license object would have an expiration data attribute as well as many other ones. These don't have to be simple data types and can be complex objects that have their own properties.  

### Quality Assurance (QA)

Quality Assurance is the implementation of structured methods of testing products to ensure that they maintain certain standards of quality. In the software industry, QA, testing, and QA testing are sometimes (though not always) used interchangeably.

### Selenium

An open source suite of software that provides a standardized api to itneract with the different types of browsers. Very popular in the testing of websites and many other tools have been build on top of Selenium.

### Selenium grid

A configuration of a Selenium controller and Selenium Nodes that provide a collection of browsers that tests can utilize. The controller provides the best matching browser for tests depening on what it has avaialble. 

Altough setting this up can be complex, it can also be as simple as a singe docker compose file.

### Source Control

Source control, also known as version control, is change management for sets of information like source code and documents. Source control tools like Git allow individuals or groups of people to make and keep track of changes to data and resources, merge and resolve conflicting changes, and reverse or revert changes if needed.

Distributed version control is a kind of source control where everyone working on a project has a complete copy of it mirrored on their own computer as well as a complete history of its changes.

### SpecFlow

[SpecFlow](https://specflow.org/) is a testing framework that supports a domain-specific language called Gherkin. SpecFlow integrates with Visual Studio and provides testing solutions for .NET platforms, including the .NET Desktop Framework, .NET Core, and Mono. It is an open source port of Cucumber.

### Test-Driven Development

Introduced around 2000, this practice aimed to prevent developers from building incorrect code. The idea is that the developer writes tests before they write code in an effort to ensure that the code works according the the expectations that the developer has. 

This is different from BDD as the tests are written by the developer not in collaboration with the team.

### Ubiquitous language

A subset of English (or any language) where all the works have a clear meaning understood by the people that work on the domain. This will be a tiny set of words relative to English, without synonims and few adjectives. 

The goal is to ensure that there is clarity in what is being communicated in this language, without any ambiguity. Examples where you would find ubiquitous langauge in real life are rules & regulations and work orders.

### Variable

In our context this is a named piece of data. Lets say there are two cats, Whiskers and Purrcival. If we want to communicate about these cats we don't want to keep saying first and second cat, so instead we refer to them by their name. This will allow us to refer to Whiskers.Coat.Color for the collor of the coat of whiskers whitout any ambiguity.   

### Visual Studio

[Visual Studio](https://visualstudio.microsoft.com/) is a full-featured integrated development environment (IDE) from Microsoft. It can be used to develop and debug software, apps, and websites. The [Visual Studio Community edition](https://visualstudio.microsoft.com/free-developer-offers/) is free, while the Professional and Enterprise editions are subscription-based. Visual Studio is primarily available for Windows. There is also a version available for MacOS, but it can only be used with .NET Core.

### Visual Studio Code (VSCode)

[Visual Studio Code](https://code.visualstudio.com/) (VSCode for short) is a free, cross-platform text editor for managing source code. It includes developer tools and optional extensions that help with language support, testing, and debugging, and that make it a viable alternative to Visual Studio for many projects. It is available for Windows, MacOS, and some Linux distributions.

### Web driver

A piece of middle ware used in Selenium to interact with a specific web browser like Ghrome, Edge, etc.

### XPath (XML Path Language)

XPath is a query language for XML documents. You can use XPath queries to select XML nodes and compute values. In the PossumLabs.Specflow.Selenium project, XPaths work behind the scenes to find and select HTML elements on a webpage. The [XPath standards](https://www.w3.org/TR/xpath/all/) are maintained by the World Wide Web Consortium.
