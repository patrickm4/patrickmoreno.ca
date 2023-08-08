---
layout: ../../layouts/project.astro
title: Due
client: Self
publishDate: 2023-08-07 00:00:00
img: /assets/due-today.png
description: |
  To due app to simplify scheduling simple or complex tasks/goals
tags:
  - Vue2
  - PWA
  - vue-scroll-snap
repoLink: https://github.com/patrickm4/due
repoName: github.com/patrickm4/due
---

<img src="/assets/due-today.png" alt="Today Page" style="height: 680px; width:380px;"/>
<img src="/assets/due-tmr.png" alt="Tmr Page" style="height: 680px; width:380px;"/>
<img src="/assets/due-some.png" alt="Someday Page" style="height: 680px; width:380px;"/>

There are lots of apps that help you do the thing you told yourself you would do yesterday. One app in particular I've used from way back when windows phones were a thing. This is a direct comparison to it. Due it was called, perfect for saying "this looks like tomorrow's problem."

This is an app I've been wanting to use, couldn't find anything similar so I made one. I've built an <a href="https://patrickmoreno.ca/due/" target="_blank">alpha version</a> and now use it daily.

<h2>How it works</h2>

Swipe left or right to go to Today's task list, or Tomorrow's or Someday's.

On each page you can create a new task/goal that is due for that day.

Tasks in the Tomorrow list will move into the Today list when tomorrow arrives.

Tasks in the Someday list will move into the Tomorrow list when its due date is set to tomorrow, then move into the Today list when tomorrow arrives.

Tasks can also be moved around the 3 different days, so if you couldn't get something done today you can move it to Tomorrow.

In the Someday list tasks generated or moved her are given a random due date of 1 to 3 weeks.

<h2>Future goals</h2>

I am going to style the tasks action buttons and rearrage them in a better format for mobile.

There's also some UX work like showing the next or previous day slightly over to the current page the user is on to show them they have something due that day. 

Yeah these look like a project in the "Someday" column.


View the live project <a href="https://patrickmoreno.ca/due/" target="_blank">here.</a>
