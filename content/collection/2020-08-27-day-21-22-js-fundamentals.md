---
title: "Day 22-23: JS Fundamentals"
image: /uploads/screen-shot-2020-08-26-at-9.24.21-pm.png
date: 2020-08-27T04:22:58.332Z
draft: false
showonlyimage: false
weight: 0
description: Covered JS fundamentals section and Object Section
---
It was great covering the fundamentals section. It explained a lot of coding practices I have seen but did not fully understand. Like logical operators, *OR* and *AND* operators' interesting short-circuit evaluation in JS: false || alert("it is done") => it shows an alert before *OR* operator returns the first truthy operand, in this case, it is alert('It is done'). 

In the fundamentals section, I learned about the new Nullish Coalescing Operator - *?? -* basically an operator to give a null or undefined variable a default value. I think the OR operator can be used to achieve the same outcome. 

![Nullish coalescing operator](/uploads/screen-shot-2020-08-26-at-9.36.31-pm.png "Nullish coalescing operator")

Also, I did not know you can give a loop a label in combination with *break/continue. It is pretty good.* 

I wanted to go over the basics of Object after the fundamentals. Make sure I learn and review about Objects, It is so important! I did not know about the *in* operator. Once I learned about that, it's easier to remember to use for... in loop for Objects :))) One of the most important things is about cloning an object, especially deep cloning. In this section, it talked about using Object.assign(dest, \[source1, source2 ...]) for cloning and merging. And the lodash library's [cloneDeep](https://lodash.com/docs/4.17.15#cloneDeep) function for deep cloning. I want to implement an algorithm for it myself! Lastly about Objects is *this* keyword and Reachability - it involves how JS engine doing garbage collection. It is something that is new to me too!

![this keyword](/uploads/screen-shot-2020-08-26-at-5.52.08-pm.png "this keyword")