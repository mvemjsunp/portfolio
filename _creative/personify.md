---
layout: creative
title: PERSONify
# summary: TODO
summary: Interactive data visualization and interface to explore real user search data publicly released by AOL in 2006.
image: /creative/personify-school.jpg
# header-image: /creative/TODO.png
---

I designed and developed an interactive visualization and interface to explore real user search data [publicly released by AOL](https://techcrunch.com/2006/08/06/aol-proudly-releases-massive-amounts-of-user-search-data/) in 2006.

{% include project-image.html file="creative/personify-school.jpg" description="TODO" %}

## Background

In late 2006, the AOL Research team publicly released a compressed text file containing over twenty million search queries collected from around 650,000 users over the course of three months. The team included a readme file with the search data that stated its potential uses “for personalization, query reformulation or other times of search research”. The data set includes the following information for each search query:

* an anonymous user ID (associated with particular user accounts)
* the text of the query
* the date and time when the query was submitted
* the search engine ranking of an item that the user clicked on when results for her query were shown
* the URL of the clicked result

AOL was promptly rebuked for releasing information that could potentially identify individuals based on their queries, and they pulled the file three days later. A class action lawsuit was eventually filed, and reactions around the Internet ranged from horror to fascination.

{% include project-image.html file="creative/personify-landing.jpg" description="TODO" %}


## Concept

PERSONify aims to address the implications of the AOL search data release in a way that both enables access to the data, as well as raises questions about the ethical consequences and voyeuristic nature of viewing it. Through a visually engaging interface that focuses on the content of the queries and the images they form of the users who submitted them, the application allows for an interactive exploration of the data itself.

The latest version of PERSONify features more sophisticated visualization techniques, the ability for the user to search the database for specific words and queries, an improved landing page. Future versions should include the ability to save one's "favorite" users and queries for later review and comparison, adding a sinister layer of gamification.

{% include project-image.html file="creative/personify-firstload.jpg" description="TODO" %}

## Technical

I completed the first version of PERSONify in Fall 2012.  It featured limited access to less than 10% of the entire database. The latest version includes all 20 million+ queries. Each user in the search query database is represented by a colored circle (the size and color of the circle are correlated with the relative number of queries made by that user).

Initially, the application used Processing.js, jQuery and PHP to access and visualize the data, which is stored in a MySQL database. In the latest version I eliminated Processing.js entirely, replacing it with the open-source Javascript library d3.js (which is specifically intended for interactive web data visualization). This improved processing and load time and enabled new and improved opportunities for interactivity and animation.

{% include project-image.html file="creative/personify-clickquery.jpg" description="TODO" %}


## Experimental goals

Although various artists have used the AOL search data in their art, from a documentary to an interpretive performance to a searchable database allowing site visitors to comment on each anonymous user in the database, this approach attempts to be a bit more playful and interactive, encouraging the user to explore and think about the enormous amount of data they're viewing, and about the implications of viewing the data—the same kind of data that (unless we take steps to use anonymous browsers or other precautionary measures) is being collected by some entity, somewhere, every time each of us uses the Internet.

{% include project-image.html file="creative/personify-similarqueries.jpg" description="TODO" %}

