---
layout: post
title: 2019-07-22-design-pattern-eventstore
---

building on top of [https://github.com/mkcoder/lifebook/wiki/Blog#event-sourcing-design-discussion](lifebook event sourcing introduction post)

in this post we will look at a couple of design patterns that might help us decouple our application; compare and contract 
those patterns, look at different architectures and how it might help us get a better idea of what works and doesn't 

throughout the application design we need to keep in mind that this is a core feature so we have to keep 
a lot of things internal and only expose methods through interfaces and we have been thinking about a new lifebook.core.domain project that will bind and expose interfaces only so let's refactor to that design

let's look at a very confusing diagram and let me explain how it should work 

![https://github.com/mkcoder/mkcoder.github.io/blob/master/images/lifebook%20architecture-lifebook.core.es.png](confusing diagram)
