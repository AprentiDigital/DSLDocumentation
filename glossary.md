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

### Attribute

### Behavior-Driven Development (BDD)

### Bounded context

### Container

### Context Map

### Cucumber

### Docker

Docker is a tool that makes it possible to run multiple, isolated copies of applications at the same time. It has less overhead than running individual virtual machines for each application, because all the containers running the applications share a single operating system kernel. Automated tests for websites will run faster if you can run them in multiple instances of browsers at the same. Docker makes that possible. When running browsers in Docker for the purpose of testing, the browsers are often run in a headless state.

### Domain

### Domain-Driven Design (DDD)

### Domain-Specific Language (DSL)

A domain-specific language is a limited-use language made up of words that have meaning within a certain context. That context, or domain, is often a product, business, or workflow. The words in a domain-specific language can be combined and used to accomplish specific tasks. Alexa, Cortana, and Siri are examples of domain-specific languages: you can interact with them in simple, scripted ways to accomplish tasks.

### Dot notation

### Enterprise service bus (ESB)

### Entity/Entities

### Feature

### Gherkin

### Git

Git is a free, open source tool for source control management. It is primarily used in software development for tracking changes to source code, and it can be used and managed via the command line or any number of third-party applications that provide graphical user interfaces.

### Headless

Running software headless (e.g. running a browser headless) means running it without its graphical user interface. When running browsers in containers for automated testing, the graphical user interface isn't usually necessary, because there isn't a person watching every single test play out. Despite running headless, it's still possible to record screenshots of the tests that can be reviewed after the test is over.

### Keywords

### Model

### Model-Driven Design (MDD)

### Mono

[Mono](https://www.mono-project.com/) is an open source implementation of Microsoft's .NET Framework that makes it possible to develop cross-platform applications. Supported platforms include Windows, MacOS, Linux, and [others](https://www.mono-project.com/docs/about-mono/supported-platforms/).

### .NET, .NET Standard, and .NET Core

.NET is a framework that is used to create Windows applications. .NET Standard is a set of APIs that all .NET implementations must use. .NET Core is an open source, cross-platform implementation of .NET Standard. While .NET is only used to develop Windows applications, .NET Core can be used to develop applications for all major operating systems, including Windows, MacOS, and Linux. The PossumLabs.DSL example project is compatible with .NET Core.

### Open Source

### Property

### Quality Assurance (QA)

Quality Assurance is the implementation of structured methods of testing products to ensure that they maintain certain standards of quality. In the software industry, QA, testing, and QA testing are sometimes (though not always) used interchangeably.

### Selenium

### Selenium grid

### Source Control

Source control, also known as version control, is change management for sets of information like source code and documents. Source control tools like Git allow individuals or groups of people to make and keep track of changes to data and resources, merge and resolve conflicting changes, and reverse or revert changes if needed.

Distributed version control is a kind of source control where everyone working on a project has a complete copy of it mirrored on their own computer as well as a complete history of its changes.

### SpecFlow

[SpecFlow](https://specflow.org/) is a testing framework that supports a domain-specific language called Gherkin. SpecFlow integrates with Visual Studio and provides testing solutions for .NET platforms, including the .NET Desktop Framework, .NET Core, and Mono. It is an open source port of Cucumber.

### Test-Driven Development

### Ubiquitous language

### Variable

### Visual Studio

[Visual Studio](https://visualstudio.microsoft.com/) is a full-featured integrated development environment (IDE) from Microsoft. It can be used to develop and debug software, apps, and websites. The [Visual Studio Community edition](https://visualstudio.microsoft.com/free-developer-offers/) is free, while the Professional and Enterprise editions are subscription-based. Visual Studio is primarily available for Windows. There is also a version available for MacOS, but it can only be used with .NET Core.

### Visual Studio Code (VSCode)

[Visual Studio Code](https://code.visualstudio.com/) (VSCode for short) is a free, cross-platform text editor for managing source code. It includes developer tools and optional extensions that help with language support, testing, and debugging, and that make it a viable alternative to Visual Studio for many projects. It is available for Windows, MacOS, and some Linux distributions.

### Web driver

### XPath (XML Path Language)

XPath is a query language for XML documents. You can use XPath queries to select XML nodes and compute values. In the PossumLabs.Specflow.Selenium project, XPaths work behind the scenes to find and select HTML elements on a webpage. The [XPath standards](https://www.w3.org/TR/xpath/all/) are maintained by the World Wide Web Consortium.
