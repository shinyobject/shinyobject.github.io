---
layout: example
category: portfolio
title: Get Me Home concept design
list_image: 2017-10-24-get-me-home-thm.png
css: article

company: DAT Solutions
role: Lead UX Designer
goal: Implement the "Get Me Home" feature for the mobile freight matching app
excerpt: The concept of "Get Me Home" is straightforward, but the implementation continued to raise interesting quirks. 
---

![Get Me Home]({{site.baseurl}}/assets/images/2017-10-24-get-me-home.png)

A driver typically commits to a one leg of a trip at a time. If a load from Portland is to be delivered to Chicago, the driver won’t look for a return load until they get close to Chicago. The market changes quickly enough that the best loads usually get taken the same day they are posted. It is not uncommon for a driver to take a load going somewhere they haven’t been. In the mobile app we wanted a simple way for a driver to do a search from wherever they currently are to home. Just like the “navigate me home” feature of any GPS app. 

This was a situation where the concept was well understood and we casually talked about it in the early phases of the project. When we got closer to the time to build it, we realized it wasn’t quite as simple. Doing a search from the user’s location using the GPS on their phone was simple enough, but there’s little details that are needed to do a proper search. The most important of which, where is home? After that, we need to know the parameters of the truck: what type is it, how long is it, how much weight can it handle? We could probably deduce these values from previous searches, but what if this is the first search the user does in the app? We knew we would need a screen to collect this information. 

The button for the screen on the left would normally ay “Get Me Home”, but it would start out as “Set up Get Me Home” until the user enters the necessary values. The hamburger menu would contain a link to change these values once they are set. 

The feature contained to be more complicated than we anticipated. There are many ways to prioritize a search: shortest distance, highest profit, and home by a certain date. We didn’t start exploring these options in the initial product release. We did briefly think about a pattern like a regular tap would run the search, sorting the results by the user’s default, but a tap and hold would bring up an option menu to customize the sort. 