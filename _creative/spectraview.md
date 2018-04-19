---
layout: creative
title: SpectraView
# summary: TODO
summary: Web application for interpreting, graphing, and sharing Mössbauer spectroscopy data
image: /creative/spectraview-interface.png
# header-image: /creative/TODO.png
---

I was on a team of three computer science/new media students data-driven web application to interpret, graph and share Mössbauer spectroscopy data for a chemistry research scientist at UNC Asheville who is part of a community of a few thousand scientists working in the field.

{% include project-image.html file="creative/spectraview-interface.png" description="TODO" %}

## Overview

<a href="https://en.wikipedia.org/wiki/M%C3%B6ssbauer_spectroscopy" target="_blank">Mössbauer spectroscopy</a> requires analysis of large multivariate datasets, and the motivation for this project was the need for a more dynamic and interactive and standardized means of handling and interpreting this data, as well as to provide a platform for the scientists to share the data among their colleagues.

Our team designed and developed a prototype web application to accept a variety of raw incoming data formats, interpret and convert them into a standard format and generate interactive graphs. Along with our goal to enable the spectroscopy community to analyze, compare and share the data, we made sure to utilize well-documented, open-source platforms such as the JavaScript graphing library <a href="http://multigraph.github.io/" target="_blank">Multigraph</a> and the collaborative code-sharing platform Github—to encourage future teams of developers and scientists to download our source code and customize it according to their needs.

## Collaboration

Our team of three undergraduate seniors, all with backgrounds in both New Media and Computer Science, were tasked with the responsibility of determining a solution for our client's problem based on our collective skills and accessible tools.

Our individual areas of expertise turned out to be quite complementary, as we had one team member experienced with server management and back-end engineering with Python; one well-versed in front-end design and development; and the other (myself) focused on dynamic integration of the two.

My responsibilities in this project included designing and implementing a suitable database, as well as developing the scripts to dynamically integrate this database with the user interface.  I also worked with our UI designer on the web application interface.

{% include project-image.html file="creative/spectraview-db-tables.png" description="TODO" %}
{% include project-image.html file="creative/spectraview-tech.png" description="TODO" %}


### Code-sharing and version control

The well-known collaborative coding and version control platform Github was essential to our development process. We had all used Github before, but not quite as extensively as this project demanded. As all three of us were writing code on many of the same files, sometimes working simultaneously from different locations, Github allowed us to always have access to the most recent changes by team members, as well as to easily revert back to previous versions of files in case someone contributed faulty code.

This also supported the mutual goal of our team and our client for the project to be scalable and extensible, since Github would host our application prototype persistently as an open-source project for other developers to view, download and adapt to their needs.

{% include project-image.html file="creative/spectraview-github.png" description="TODO" %}
{% include project-image.html file="creative/spectraview-php.png" description="TODO" %}

