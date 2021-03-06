# Restaurant App Reviews Project

This Restaurant Reviews project began with a codebase that was "barely usable on a desktop browser, much less a mobile device. It also didn’t include any standard accessibility features, and didn't work offline at all." 

I converted the original, static webpage to a mobile-ready web application. I also took this application that lacked accessibility and modified it for responsiveness on a variety of displays, since another criteria was accessiblility for screen reader use. Key for this project was adding a service worker to begin the process of creating an offline experience for your users.

## Table of Contents

* Installation
* Leaflet.js and Mapbox
* Note about ES6
* Acknowledgments

## Installation

* Clone the project from Github

* In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

* In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

* With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

* Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.

* Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

## Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 

## Acknowledgments

* Udacity community managers
* Project coaches
* Matthew Cranford Blog
* [YouTube](https://www.youtube.com/watch?v=92dtrNU1GQc) - Project 1 MWS Webinar with Doug Brown.
* [YouTube](https://www.youtube.com/watch?v=dMutLUzVbIA&t=0s&list=PLKC17wty6rS1XVZbRlWjYU0WVsIoJyO3s&index=5) - Tutorial Requests: FEND Project 5 & MWS Project Stages 1, 2, 3 (Restaurant Reviews) - Walk Through.
* [YouTube](https://www.youtube.com/watch?v=2PY733qFR3A&feature=youtu.be) - Tutorial Requests: FEND Project 5 - Service Workers.
