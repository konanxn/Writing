# Programming - the pragmatic approach

[<img src="https://images.unsplash.com/reserve/NnDHkyxLTFe7d5UZv9Bk_louvre.jpg?dpr=2&auto=format&fit=crop&w=1080&h=730&q=80&cs=tinysrgb&crop=">](
https://unsplash.com/photos/-aDl1z8_nGY)
Photo by Stacy Wyss on Unsplash - https://unsplash.com/photos/-aDl1z8_nGY


I like to give myself the illusion that I handle many things in a "pragmatic" way. I like the concept. Therefore I dive into pragmatic concepts in programming.

This is a summary of the conclusions from ["The Pragmatic Programmer", by Andrew Hunt and David Thomas](https://www.amazon.de/Pragmatic-Programmer-Journeyman-Master/dp/020161622X/ref=sr_1_1?ie=UTF8&qid=1505644110&sr=8-1&keywords=pragmatic+programmer) added with some of my thoughts.


## 📄 Table of contents

- [Intro](#intro)
- [Content](#content)
- [Pragmatic Philosophy](#pragmatic-philosophy)
- [Pragmatic Approach (when programming)](#pragmatic-approach-when-programming)
- [Basic tools](#basic-tools)
- [Pragmatic Paranoia](#pragmatic-paranoia)
- [Bend or Break](#bend-or-break)
- [While Coding](#while-coding)
- [Before the project](#before-the-project)
- [Pragmatic projects](#pragmatic-projects)
- [Useful links & credits](#useful-links--credits)

---
>“Whenever a theory appears to you as the only possible one, take this as a sign that you have neither understood the theory nor the problem which it was intended to solve.” 
― Karl R. Popper
---

## Intro

There are already many summaries of this book. But the concepts are important and worth repeating. At the end you will find a list with other summaries, in case you want to read other opinions as well.

## Content

The book divides itself into the following:

1. the pragmatic philosophy
1. the pragmatic approach
1. the basic tools
1. pragmatic paranoia
1. bend or break
1. while you are coding
1. before a project
1. pragmatic projects

## Pragmatic Philosophy

Before going into it's concepts I would like to revisit it's [definition and quote Wikipedia](https://en.wikipedia.org/wiki/Pragmatism):

> Pragmatism considers thought an instrument or tool for prediction, problem solving and action, and rejects the idea that the function of thought is to describe, represent, or mirror reality. Pragmatists contend that most philosophical topics—such as the nature of knowledge, language, concepts, meaning, belief, and science—are all best viewed in terms of their practical uses and successes.

In the first chapter of the book general concepts and approaches are described, like

- enjoy what you do
- find solutions instead of excuses
- fix problems where they occur and work on the source and not the result
- zoom out to the big picture and welcome changes
- set up a quality standard. Follow it.
- knowledge is power. Learn everyday as much as you can. Diversify.
- communicate efficiently. Know your stuff and know your audience.

## Pragmatic Approach (when programming)

Always stay as DRY as possible (don't repeat yourself). Avoid duplicating code, information or documentation. Every piece of knowledge should be a single, unambiguous, authoritative representation within a system.

Follow the principle of [orthogonality](https://en.wikipedia.org/wiki/Orthogonality_(programming)). Set a small set of primitive constructs, which can be combined in a small number of ways. It allows to:
- reduce the numbers of errors
- divide functions within an application easier
- divide teams more logical
- test faster

Use tracer bullets and prototyping to evaluate an environment and adapt it's tools accordingly. Whereas tracer bullets (can be algorithms, techniques, languages, or libraries) should penetrate a bigger area, prototyping provides great feedback when exploring a more focused area of the project (can be new features in an existing system, contents of external data/tools, user interface design). 

> Shoot tracer bullets to explore, prototype to learn!


## Basic tools

Regarding tools stick to powerful basics. 
Use GUIs wisely. They might be easier to start with but are limited. Plain text is always on top in terms of speed and opportunity.
Choose one editor that covers the basics (configurable, extensible, syntax highlighting, etc.) and always use source/version control.

For debugging:
- focus on solving, rather than blaming
- dive to the root of the problem and don't use quick fixes
- find the root by elimination
- try to reproduce the bug (identify the core problem)
- use rubber ducking (explain the bug to someone)

Aim to write code, that writes code (for example uses JSX).

## Pragmatic Paranoia

Don't overestimate yourself. Nobody alone writes perfect code. 
Create assertions where they are absolutely necessary. Exceptions should only be used for exceptional problems.

## Bend or Break

- the law of Demeter: Minimize coupling, since each combination can lead to unexpected results.
- dynamic configuration: Put abstractions in Code and details into metadata. Program for the general case and de-module specifics.
- design for concurrency: maximize parallelism wherever possible.
- separate the codebase into a MVC structure: Divide functions and use subscribe mechanisms to act only when needed. 
- use blackboard implementations: store active objects and retrieve data when necessary.

## While Coding

Program deliberately instead by coincidence. 
- always be aware of what you are doing
- only rely on reliable things
- document your assumptions
- not only test your code but also your assumptions
- refactor often and early. Do not add functionality. Have good tests before refactoring. 
- don't use wizard code
- test units and test against the contract. Set up a test environment to automate.


## Before the project 

> The key to solving puzzles is both to recognize the constraints placed on you and to recognize the degrees of freedom you do have, for in those you'll find your solution.

Never sacrifice the bigger picture for specialization. Remind yourself of the big picture whenever possible.

## Pragmatic projects

- organize a team by functionality rather than "job functions" and let them organize themselves within
- ubiquitous automation: building the project, tests, statistics, etc.
- always test: early, often, automatically
- always document: in the code and outside. Use the same principles as when writing code
- expect greatness: Exceed the users' expectations

___


Thanks for reading my article! Feel free to leave any feedback! 

___

## Useful links & credits
- [📄 Summary of The-Pragmatic-Programmer by HugoMatilla](https://github.com/HugoMatilla/The-Pragmatic-Programmer)
- [📄 Summary of The-Pragmatic-Programmer by Nearsoft](http://academy.nearsoft.com/project-updates/summaryofthebookthepragmaticprogrammerfromjourneymantomaster)


<!-- Written by Daniel Deutsch (deudan1010@gmail.com) -->
