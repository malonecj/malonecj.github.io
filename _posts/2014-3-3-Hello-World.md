---
layout: post
title: Backbone Marionette Sample Application
published: true
---

First post. Hello!! This is a small sample appliction I wrote about a year ago while learning about Backbone Marionette and trying to find out the best way to go about building an application with it. Much of the application structure is based upon the ideas I read about in the Marionette books written by [David Sulc](https://leanpub.com/marionette-gentle-introduction)  

![_config.yml]({{ site.baseurl }}/images/playlist_app.png)

The application itself is a simple playlist app, using the [Spotify Web API](https://developer.spotify.com/web-api/) to search for songs and artists and play. After searching for tracks, you can then play a 30 second clip of it. We use the html5 audio element for this, and pass it a Url that we get back from the Spotify API.

You can view and download the code for the application [here](https://github.com/malonecj/backbone_sample_playlist_app). To run it yourself, 
clone the repository and run
 
 npm install
 grunt serve
 
 which will fire up a local server and the application.