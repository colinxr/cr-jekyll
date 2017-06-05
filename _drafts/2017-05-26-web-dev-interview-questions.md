---
layout: post
title: "Web Dev Interview Questions"
description: "Interview Prep"
date: 2017-05-117
share: true
---

prep for web dev interview


##General interview questions

###CSS


2. Reset vs. normalize

Reset just unstyles browser user-agent styles, while normalize preserves useful defaults. Normalize is more modular and its easy to remove the bits you don't need.


3. Floats

Floats will take the element out of the normal float of the docoument and push the element to the side of the page.


4. Z-Index

Sets visual depth. can be positive or negative, values are all relative. 

can be annoying to rewrite HTML to make elements naturally stack upon eachother the right way, so z-index lets you manually set the visual depth.


5. Clearing

using the clear property... clear: both. 

inserting a div with class of .clearfix at the end of element. 

put a pseudo element on the last element which clears

6. Sprites are sets of images gathered into one file. set of icons that run the same height, creates one http request instead of TK. Choose the background image you want to show and the background position. 


7. Image Replacement Techniques

Don't come across this alot to be honest. Overflow: Hidden and huge negative margin-left/


8. feature constrained browser

Always felt modernizr is a pretty powerful tool to progressively enhance. There' a baseline of like ie9, ie10, and then you build up from there. 

CanIUse is really great. 


9. Grid System

Bootstrap mostly, have used foundation in the past as well. 

css grid is something i've been meaning to learn about. 


10. Media Queries


11. styling SVGs


12. Optimize for print

N/A


13. Writting Efficient CSS

sort properties by alphabetically, it's anal but makes for scanning really easy. 
Shared selectors get on one line each

separating components into individual partials in sass. 

don't use #IDs. 

Normalize, Variables, typography, reusable components: buttons, cards, forms, layout scaffolding, page specific styles. 


14. Preprocessors

I use SASS, with .scss, love the power of variables, math, partials, nested selectors. It feels right. It feels like a natural way to organize.


15. 






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


*callbacks & higher-order functions*
honestly, i'm just not that great at JS. 
http://callbackhell.com/

*async functions*
	- webscraping, super simple but is firing after my bookmark save method.
	https://blog.risingstack.com/node-hero-async-programming-in-node-js/





