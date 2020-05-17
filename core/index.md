---
layout: default
title: Core Tutorials
nav_order: 3
has_children: true
---

## DSL.Core Tutorials

The tutorials fall into up into three sections, Core for the parts dealing with variables, Web for interacting with webpages, and Advanced that talks about replacing components of the framework. This section is the Core section, and you'll learn how the PossumLabs.DSL framework can help you define data for your scenarios concisely and powerfully. 

We will start by introducing entities; then, we will explore the different types of aspects that can describe the entities. All of this will result in the final tutorial, where we will put it all together and create a complex data scenario that leverages all of these concepts. 

A driving force of the PossumLabs.DSL project is to allow for the creation of a concise data definition for scenarios. This conciseness is important because of two reasons. First, the tooling for Gherkin is not fantastic when it comes to refactoring. So less code means that you have a better time in the long term maintenance of the Gherkin in your scenarios. The second reason is that complicated and irrelevant data setup detracts from the clarity of the actual tests. 

All tutorials in this section will have a version that is based on the PossumLabs.DSL.Core package and on the PossumLabs.DSL.English package. The English version is always simpler as we are leveraging more of the common infrastructure. The Core version allows you to avoid the dependency on the Selenium packages that PossumLabs.DSL.English depends upon. 
