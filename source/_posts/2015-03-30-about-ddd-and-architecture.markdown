---
layout: post
title: "About ddd and architecture"
date: 2015-03-30 11:27:50 -0300
comments: true
categories: 
---

http://www.infoq.com/news/2013/07/architecture_intent_frameworks 

Robert refers to an architecture model described in the book Growing Object-Oriented Software Guided by Tests, (similar to the Hexagonal architecture), which describes an architecture with three zones with dependencies going only one way, from the volatile parts towards the more stable parts:

A Domain Model with the core business rules, the most stable and important part for the business, not depending on anything else.
Application Services for the use cases of the system which uses, and depends on, the domain model.
External Details, database, user interface, network, etc., that are less relevant for the business model. The most volatile part and depending on the other two.

https://www.youtube.com/watch?v=WpkDN78P884

