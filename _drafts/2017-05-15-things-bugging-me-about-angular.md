---
layout: post
title: "Building Bookmark, a simple MEAN Stack bookmarking app"
description: "Got an appetite for destruction."
date: 2017-05-117
share: true
---

Here is bookmarkr.

#### Problems I Had

*Understanding MVC *

*the connection between front-end and back-end* 
express routes tie into angular controllers.

I honestly spent two days trying to figure out with my front end api calls weren't working with mongodb, only to realize i had left this line commented out 
mongoose.connect(db.url);

from the scotch.io MEAN Starter app, which was a super helpful tutorial. Scotch.io rules.


*No opinions = wtf*
http://stackoverflow.com/a/11077013
http://stackoverflow.com/a/12957755/444255

Using restify over express. examples using spring framework. just calling server.js index.js. Super annoying. The code all does the same things. 

*Things have just changed*
Any angular resources from, say, 2015 and before, are basically not helpful. the framework has changed so much. the biggest change is the switch from .sucess * .error to .then & .catch – that is, using promises.


*async functions*
	- webscraping, super simple but is firing after my bookmark save method.



