---
title: R2D1 - react.js tiny problems
image: /uploads/screenshot-2024-03-13-at-6.00.47-pm.png
date: 2024-03-14T00:44:05.155Z
draft: false
showonlyimage: false
weight: 0
description: "#100daysofcode R2D1"
---
I﻿ did 3 tiny problems for practicing react useState and useEffect hooks: 

1. [show/hide btn ](https://codesandbox.io/p/sandbox/reactchallenges-usestate2-forked-tslzxt?file=%2Fsrc%2FApp.js)
2. [form submission ](https://codesandbox.io/p/sandbox/hooks-usestate-form-q-forked-76xxkx?file=%2Fsrc%2FApp.js)
3. [start/stop/reset timer](https://codesandbox.io/p/sandbox/hooks-usestate-timer-q-forked-4ddv9y?file=%2Fsrc%2FApp.js)

O﻿ne thing I debugged today was passing the previous timer value to the setTime callback function. I thought setTime(time + 1) would refer to the time variable. There is still something i feel like i am unclear about this :|. it's straightforward should be setTime(time => time + 1). I think I need to read the doc to see why I am still kinda confused.