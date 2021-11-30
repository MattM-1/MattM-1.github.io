---
author: Matthew Midtvedt
title: Testing Formatting
date: 2021-11-27T13:20:12-06:00
math: true
categories: ["Testing"]
draft: false 
---

The code below seems to work nicely; however, I think I am going to have a problem with the math.
```
PriorityQueue<String> stringQueue = new PriorityQueue<>();
stringQueue.add("blueberry");
stringQueue.add("apple");
stringQueue.add("cherry");
```
Now, it's time to figure out if we can get KaTeX working properly.

Block Math:
$$
\Alpha \implies \Beta
$$
