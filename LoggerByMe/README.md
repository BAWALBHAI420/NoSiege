What is it?
-------------
This is Logger v0.4.8 - package that provides powerful, efficient
and pretty logging, monitoring and application management for [Meteor framework](http://meteor.com) application development and 
deployment.
[See it in action and read full usage docs!](http://observatoryjs.com/)

What does it do?
------------------
* Easy logging with different log levels with corresponding methods for message output, optional 
logging to console, pretty output of both Client and Server logs right in the browser, logging of
the currently logged-in user for additional control.

* Augomagical logging, profiling and error handling for DDP, http, Collections, Subscriptions, Template lifecycle methods and any custom code

* Monitoring of your application internals: publish and methods handlers, active sessions, etc

* Full-featured cloud-based monitoring and management of your Meteor applications: closed Alpha!

Installation
-----------------
#### As a Meteor package:

	meteor add superstringsoft:observatory

Usage
---------

	tb = Observatory.getToolbox()
	tb.warn("This is a warning message")

There's *much* more.
[Read full docs](http://observatoryjs.com) and sign up to be notified for the cloud launch!


Feedback
----------
We'd love to hear what you think, whether it's useful and which other features you'd want to see -- so please submit issues here on github or [leave a comment on our blog](http://meteorology.io) 
to share your thoughts and ideas!

