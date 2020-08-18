---
title: "Day 19: Hugo & Netlify"
image: /uploads/hugocms.jpg
date: 2020-08-17T14:23:11.120Z
draft: false
showonlyimage: false
weight: 2
description: My experience of setting up this site, using hugo and netlify cms
  for a project - the JAM stack
---
Day 19 of [\#100DaysOfCode](https://twitter.com/hashtag/100DaysOfCode?src=hashtag_click) - I wanted to have a dedicated place for tracking my daily learning. I used Jekyll before for hosting a blog but found it hard to use for frequent updates. After looking into this, I deployed this site using [hugo](https://gohugo.io/getting-started/quick-start/) and [Netlify cms](https://www.netlifycms.org/docs/hugo/#introduction). The documentation is so good on both of their websites. 

In addition to following the doc, I had to figure out some settings:

* Hugo - I had to add the publish directory for the generated static files. It is import to have this for hosting on github pages and Netlify

![config.toml](/uploads/config_toml.jpg "config for hugo publish directory")

* Netlify setting - I also had an issue with Identity settings. You can get a new API token if it's not connecting. Also enable third party OAuth also helps with log into CMS

  ![git gateway](/uploads/netlifysetting.jpg "API token")

  I found including Netlify CMS into the project was pretty easy. It only needs two files: index.html and config.yml. The config file is where I spent the most time because I had to define the needed cms widgets for the required post fields. 

  Here is the CMS UI once it's deployed and logged in:

  ![cms interface](/uploads/screen-shot-2020-08-18-at-3.46.35-am.png "cms interface")

  ![text editor interface](/uploads/screen-shot-2020-08-18-at-4.11.50-am.png "text editor interface")