---
layout: creative
title: PARI interactive museum kiosk
summary: Interactive touch-screen kiosk application presenting live data feeds from onsite meteorological and astronomical instruments, along with interactive activities highlighting PARI's research and education projects.
image: /creative/pari-museum-install.jpg
---

I designed and developed an interactive kiosk desktop application for visitors to the North Carolina Museum of Natural Sciences (in Raleigh, NC) to explore and learn about the resources and programs of the public not-for-profit Pisgah Astronomical Research Institute.

{% include project-image.html file="creative/pari-museum-install.jpg" description="TODO" %}

## Background

My advisor in the New Media department arranged a meeting between the PARI staff and myself when they approached her to find a student who could design and implement an interactive kiosk application with a quick turn-around.

The <a href="http://naturalsciences.org/" target="_blank">North Carolina Museum of Natural Sciences</a> in Raleigh, NC was about to open their cutting-edge Nature Research Center wing, and PARI would be represented in an exhibit featuring posters and other displays, meteorites from their collection and a touch-screen monitor. They had first planned to create a simple Powerpoint presentation to install on the touch-screen kiosk, but later decided a more interactive experience would be needed to engage museum visitors, who would be pulled in all directions by the sights and sounds of the new wing. The PARI staff wanted to give the visitors "a window to PARI" to simulate an actual visit to PARI's campus in Rosman.

{% include project-image.html file="creative/pari-mockups.png" description="Some of my initial exploratory mockups for the UI." %}

## Version 1

The first version simply needed to highlight PARI's most important assets and resources through pre-established content, including:

* high-definition video clips
* astronomical plate images
* interactive modules located on PARI's website

My task was to design and develop the information hierarchy and interface for this content, then package it into an installer file to send to the museum.

I used Adobe Flash (CS5) to develop the application primarily because of my familiarity with using Flash for interactive development and its built-in methods for desktop deployment packaging.

{% include project-image.html file="creative/pari-main.jpg" description="The application is installed on touch-screen monitors at both the PARI campus and the museum in Raleigh. PARI's target audience includes people of all ages and backgrounds, with a focus on engaging young people in astronomy and science in general. For these reasons, the navigation had to be simple, intuitive and accessible." %}

{% include project-image.html file="creative/pari-whatispari.jpg" description="The PARI staff had two short video documentaries they wanted embedded within the application. The high-resolution videos had to be reduced and converted into a compatible format. The videos are integrated into the interface such that the user can still navigate through other content while the video is playing." %}

## Version 2

After completing the first version and having it successfully launched in time for the museum opening, I was offered the Digital Resources & Science Education Intership position at PARI, made possible by a National Science Foundation grant, to refine and enhance the application. Major changes included:

* Integration of real-time data from the onsite scientific equipment, including solar and sky cameras, telescopes and seismometers
* Development of custom modules to simulate the features on PARI's website, which were previously accessed by browser pop-up windows (to improve usability and ensure a consistent user experience)
* Refining the navigation and information hierarchy
* Application of game elements to existing content, such as obscuring content until certain interactions occur and asking leading questions to prompt user engagement

### Real-time and recent aggregated meteorological/astronomical data feeds

Visitors at the museum in Raleigh can currently access:

* live images of PARI's telescopes
* a time-lapse recording of the past 24 hours of sky activity captured by the PARI Sky camera
* live images captured by the sunspot and solar flare telescopes
* current satellite weather tracking images
* current data for seismic activity like earthquakes
* the last five minutes of solar flare activity recording by PARI's low-frequency antenna

{% include project-image.html file="creative/pari-instruments.png" description="TODO" %}
{% include project-image.html file="creative/pari-26m.jpg" description="Various instruments and cameras at PARI generate streaming video and data. Version 2 accessed several of these feeds and integrated the real-time streams into the desktop application." %}
{% include project-image.html file="creative/pari-weather.jpg" description="A 'recent lightning detector' was just one of the meteorological and astronomical instruments that conveyed real-time or recent aggregated data to the kiosk application." %}

### A glimpse of 110 years of astronomical images

One of PARI's most impressive resources is the Astronomical Photographic Data Archive (APDA), which houses over 110 years of astronomical images from photographic plates.  

The "Sky Time Machine" includes highlights from this collection. The user selects an image from the thumbnails at right and is presented with a plate image and a leading question. The answer is revealed when the user touches the left box. Some images have other interactive components like time-lapse animation and magnification upon touch.

{% include project-image.html file="creative/pari-skytime.jpg" description="TODO" %}

### Citizen science and classifying stars

PARI also encourages "citizen science," (sometimes called "crowd-sourced science") which engages the public in tasks of data collection and other research. The SCOPE project hosted on PARI's website asks visitors to help classify hundreds of thousands of unclassified stars by categorizing spectra images.

Originally, the application linked directly to the SCOPE website through a pop-up browser window, but usability suffered. Version two includes a 5-step "lesson" about categorizing stars, followed by a module simulating the spectra classification process.

{% include project-image.html file="creative/pari-scopeclassify.jpg" description="TODO" %}

## Reflections

Through the experience of creating a user-friendly platform for exploring a slice of the resources, programs and massive amounts of data generated at PARI, I began to fully understand and appreciate the responsibilities of an interaction designer/developer to parse and interpret inaccessible information, then find ways to effectively communicate it to wider audiences.

This was an incredibly gratifying experience and I would absolutely welcome similar opportunities to work with educational institutions, science-oriented research facilities or museums to develop engaging interactive platforms.

{% include project-image.html file="creative/pari-rebekah.jpg" description="TODO" %}







