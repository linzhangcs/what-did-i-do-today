---
title: "Day 26: UI.dev React Course - part one"
image: /uploads/screen-shot-2020-09-10-at-9.33.46-pm.png
date: 2020-09-11T06:34:08.239Z
draft: false
showonlyimage: false
weight: 0
description: Review passing data, rendering lists, managing state, functional
  components, validating props with PropTypes, and the component lifecycle
  functions
---
I have done three different intro courses on React already, but I still like to try more courses with new topics that are I have not learned. Currently,  I am following Tyler Mcginnis' React courses. It has sections on Higher-Order Components. I am looking forward to that next!

Today was mostly reviewing what I already know, so I covered 42% of the course. 

What I found meaningful during this review were five ways of binding *this* keyword and the component lifecycle functions.

The five ways of binding this keyword:

* Implicit Binding - most used, refers to the object that is on the left of the dot when the function is invoked
* Explicit Binding - use call, apply, and bind
* new keyword Binding - creates a new this object under the hood
* Lexical Binding - use the arrow function to solve this explicit binding in handlers
* window Binding - default to the window object, but 'use strict' to prevent this behavior

Also, the overview on the component lifecycle functions is great. 

![lifecycle three stages](/uploads/screen-shot-2020-09-10-at-11.57.48-pm.png "lifecycle three stages")

![ functions needed during mounting](/uploads/screen-shot-2020-09-10-at-9.30.37-pm.png " functions needed during mounting")

![functions during updating](/uploads/screen-shot-2020-09-10-at-9.35.34-pm.png "functions during updating")

![componentDidUpdate for re-fetching data](/uploads/screen-shot-2020-09-10-at-9.36.51-pm.png "componentDidUpdate for re-fetching data")

![functions during unmounting](/uploads/screen-shot-2020-09-10-at-9.39.54-pm.png "functions during unmounting")

componentDidUpdate and componentWillUnmount are functions I need to practice! 

Overall, I spent 5.5 hours on the course.