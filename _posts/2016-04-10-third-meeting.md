---
layout: post
title:  "Third Meeting"
date:   2016-04-10 20:40:00 -0500
categories: notes meeting integration
---

Our third meeting took place on Thursday, April 7th, 2016.

## Integration

In this meeting, we discussed how we would integrate the three main parts of our project (the *web server*, the *Raspberry Pi and camera*, and *face detection*) into one codebase.	Here's a diagram describing how the parts interface:

![Our face scanning machine!]({{ site.url }}/assets/setup.png)

Here's what each .py file will boil down to:


{% highlight python %}
""" app.py """
import flask
import face
import camera

""" Routes for commands to control the camera """

""" Routes for commands to analyze collected data """

""" Routes which serve up configuration pages """
{% endhighlight %}

{% highlight python %}
""" face.py """

""" A function to detect faces in a given image """

""" A function to run face detection on a directory of images """

""" A function to generate plots, images, and models of our data """
{% endhighlight %}

{% highlight python %}
""" camera.py """

""" A function to take a picture """

""" A function to rotate the camera """

""" A function to run some sequence of commands at a certain time """
{% endhighlight %}
