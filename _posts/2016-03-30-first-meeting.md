---
layout: post
title:  "First Meeting"
date:   2016-03-30 14:25:13 -0500
categories: notes meeting mvp
---
Hello! My name is Tom Fischer and I am one of the project mentors of this group. The group held its first meeting on Thursday, March 17th, 2016. Here's what went down:

## Objective

Our objective was (1) to discuss what is to be gained by the end of this course, and (2) to specify our [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product).

#### What is to be gained from this course?

At the beginning of this meeting, we talked through some things that we'd like to learn about throughout this course. We came up with a sizeable list:

* Fundamental Software Development Best Practices
  * Fundamental source control usage
    * We will use [Git](https://en.wikipedia.org/wiki/Git_(software)) and [GitHub](http://github.com/). You can view our GitHub Organization [here](http://github.com/uiuc-facescanner).
  * Unit testing and continous integration
    * We will use [Travis-CI](http://travis-ci.org/) for continuous integration.
  * Weekly code reviews
  * The use of external libraries, APIs, and packages
    * E.g., [numpy](http://numpy.org), [scipy](http://scipy.org), [OpenCV](http://opencv.org), [Flask](http://flask.pocoo.org)
  * Working in a team environment
  * [Agile software development](https://en.wikipedia.org/wiki/Agile_software_development)
* Exposure to Technologies and Hardware
  * There are many ways to reach our goal. We all plan to have a fundamental understanding of the following technologies by the end of this course:
    * [Python](http://python.org)
	* [Go](http://golang.org) (maybe)
	* [Raspberry Pi](http://raspberrypi.org)s

#### Our MVP

The second main objective of our first meeting was to specify our [minimum viable product](https://en.wikipedia.org/wiki/Minimum_viable_product). Here are some parts of the specification:

* A computer
  * E.g., Raspberry Pi, Arduino
  * ssh access
  * runs a webserver that allows remote execution of routines via HTTP requests
* A camera
  * E.g., Kinect, Picamera
  * captures images of a group of people at a given rate
    * the group of people will be in a classroom or lecture hall

The camera will capture a set of images of a group of people. The computer will analyze these images using external libraries, APIs, and packages, to provide a report about various attributes the group.

#### Attributes

Our MVP should be able to provide information about one of the following four attributes:

* Attendance (which people compose the group)
* Attention as a function of
  * time (how does average attention change over the time during which a set of images were taken)
  * content (how does average attention vary between sets of images based on the content of lectures)
  * number of devices (how does average attention vary based on the number of laptops, tablets, in the group)

#### Stretch Goals

After our reaching our MVP, we'd like to be able to provide information about as many of attributes as possible. We'd also like to make our information as accurate as possible.