---
title: "Day 18: Intro to Webpack"
image: /uploads/webpack.jpg
date: 2020-08-14T18:26:00.000Z
draft: false
showonlyimage: false
weight: 0
description: a gentle intro to webpack
---
Day 18 of [\#100DaysOfCode](https://twitter.com/hashtag/100DaysOfCode?src=hashtag_click) - learned to set up a react app without using create-react-app. Learned about how to configure package.json and webpack.config.js to start and build a project.

![webpack](/uploads/webpack.jpg "webpack")

In webpack.config.js file, I should add the following properties:

* entry - "An **entry point** indicates which module webpack should use to begin building out its internal [dependency graph](https://webpack.js.org/concepts/dependency-graph/)."
* loaders - with test and use properties "**Loaders** allow webpack to process other types of files and convert them into valid [modules](https://webpack.js.org/concepts/modules)"
* output - "The **output** property tells webpack where to emit the *bundles* it creates and how to name these files."
* plugins - "plugins can be leveraged to perform a wider range of tasks like bundle optimization, asset management and injection of environment variables."
* mode - "By setting the `mode` parameter to either `development`, `production` or `none`, you can enable webpack's built-in optimizations that correspond to each environment. The default value is `production`."

> Documentation <https://webpack.js.org/concepts/>
>
> Tutorial <https://t.co/P3PyWyUc2l?amp=1>