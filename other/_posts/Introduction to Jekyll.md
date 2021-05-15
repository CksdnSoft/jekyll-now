--- 
layout:  post
title: Introduction to Jekyll
---
It is 2020, and I want to keep a record of all the study notes that I will create as I study development or other CS topics.

I can't be bothered to create another website with databases. In addition, I don't want to pay any more money for running a server. I am already spending enough for other projects. So the option that I chose was to go with Jekyll, and host the website for free on Github Pages.

Using Jekyll with stackedit is awesome.

## First step
In the right sidebar menu, go to `Workspaces > Add a GitHub workspace`. Then, add my github repo for my static website.
After that, stackedit will automatically fetch all of the .md files and list them nicely on the left sidebar.

## Second step
Edit or create files. Make sure to not put the .md extension after the filename. I have tried it: the file is commited to github as `filename.md.md`. Sidenote: this is technically okay for Jekyll as Jekyll simply reads this file as `<filename.md>.md`.
StackEdit will automatically synchronize with github for me. If I want to manually synchronize, I can click on the synchronize button on the top bar.

## Third step
Final step is to make sure my static Jekyll website displays everything just like Stackedit's preview window.

### Single Line feed
By default Jekyll ignores Single Line feeds. Therefore I refered to [this site](https://stackoverflow.com/questions/52762454/jekyll-markdown-with-line-feed-is-not-rendered-in-html)  to fix it.

### Design
I also fixed:
* Background color
* 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI0OTQ4Mjc4MV19
-->