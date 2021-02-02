---
title: "Traffic Signal"
date: 2021-02-02 12:00:00
description: The first in a series of small projects, built for simplicity.
featured_image: "images/3762648-green-traffic-signal-light-against-blue-sky.jpg"
---

# Traffic Signal

## Philosophical Digression

David L. Marquette describes in his book the <i>Language of Leadership</i> two kinds of work: <b>red</b> and <b>blue</b>. Neither hold a political affiliate, but instead map to dmirror coginitive states. In red work, the task is reflexive. When we do red work, little thought is required. Mop the floor, commute to work, pick up the kids from soccer practice. The route from soccer pitch to home is well-trod, so to speak, and our brain cna navigate the traffic, pavement, and weather from the bottom up. While to shout the kids down, and wipe mud off of the backseat can take effort, the number of thought units spent will be fairly minimal.

Blue work, on the other hand, requires consideration, and can take a long time. To extend the family scene, you may want to raise children who can care for you in old age. In order to successfully raise such a child, you will need to provide it nutrition, society, and exercise. Ferrying the offspring to and from soccer practice counts as red work, but in the bigger picture is a fraction of blue work's design. The effort to plan how to raise children took more work than a single trip in the minivan.

In terms of software development, we might do red work in obtaining authentication credentials for an API that will add some feature to our app. Filling in forms has been largely automated to a series of mouse clicks that saves time.

## A Simple Program

It is in the spirit of red work that I present today's program, "Traffic Signal", a Python class and script that simulates a traffic signal. The user plays the role of urban planner, and calls class methods to pass timing objects in as the state of an instance. The script then powers on the signal, and logs updates to the console. Default timings include a standard 3 second yield interval between green and red.

![](/images/ts_screencap.png)
