---
layout: page
title: Project
permalink: /project/
---

# Project Overview

The sky is the limit for project ideas. However, I will be helping you limit the initial scope of your projects to ensure that you are able to create something cool in the time allotted.

## Project Requirements

The #1 project requirement:  Make something damn cool!

* Must be something you (or someone you care about) deems genuinely cool/useful
  * Great: An app that combines the APIs for Spotify, a song lyrics service, and a sentiment analysis service to provide sentiment analysis of Spotify playlists or Spotify playlist history
  * Good: A service that emails you daily to ask how your day went, then emails you a weekly summary at the end of the week, perhaps using sentiment analysis and timestamps to glean a little data about how the user is feeling
  * Good: A pictographic cookbook for my little sister that can't read yet
  * Bad: A simple CRUD app to track the movies I've watched
* Must be a web application
  * A web application does not necessarily require a front-end at all-  see the example above about a service that interacts with the user solely via. email
* Must be accessible on the public internet
* Can be written in any combination of web technologies you wish
  * It does NOT need to use Flask or React.  We are using these tools in class to learn concepts, not to prescribe technological solutions

## Project Cadence

We will develop this project in a series of milestones and sprints.  We will start project ideation in Week 0, but we won't start actual coding until midway through the term.  Weeks 8-10 will be lighter on class materials, with labs that are either smaller or entirely optional, so you will have time to focus on developing your project.

* M1: Ideation (week 1)
* M2: Picking Teams (week 2)
* M3: Settling on an idea (week 3)
* M4: Project Plan Pt 1: (week 4)
  * How will users interact with your application?  (Basic wireframes are required, high fidelity mocks are NOT required)
* M5: Project Plan Pt 2:
  * What APIs will you need?
  * How will you structure your application?
  * How will you store and structure your data?
* M6 - M10: Weekly sprints with progress reports
* M11: Live presentations during our finals timeslot<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ^--- I plan to be there live, too


<ul>
    {% for item in site.pages %}
      {% if item.url contains '/project/' and item.url != '/project/' %}
        <li><a href="{{ item.url }}">{{ item.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

