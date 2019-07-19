---
layout: post
title:      "Singing with Sinatra, although slightly out of tune..."
date:       2019-07-19 12:31:18 +0000
permalink:  singing_with_sinatra_although_slightly_out_of_tune
---


I just finished up the second major project for Flatiron’s engineering program and I can flatly admit that I’m both content and discontent, with a stress on the latter. 

I’m content in that it’s finished.

I’m discontent in that it seems as though the project could never actually be finished as there are seemingly endless additions, new features, and possibilities for refactoring. I suppose that’s the point, though, and perhaps a larger metaphor for what I, and the other students at Flatiron, are undertaking: a lifelong pursuit of not just mastering a specific language (or languages) but rather a boundless journey of learning itself.

As I step briefly away from the app in order to document the experience, I do appreciate the many things that I learned along the way to building this simple app from scratch.

First, though, I’ll briefly explain the background for the development of this particular app.

Over a year ago prior to beginning this journey to being a developer, a friend introduced me to an app called Be My Eyes. This app is specifically and only designed to aid those without the sense of sight to better navigate their world. It enables volunteers to be contacted via the app and the end user to ask that volunteer basic questions to help them in certain tasks that those with sight may take for granted.

Its simplicity of purpose and conscience beneath its surface is both beautiful and inspiring. This, in my mind, is what tech can do best: improve the lives of others while we’re sharing this moment in history together.

For my own app, it’s nothing as noble, but the intent was to develop for a specific niche that is underserved. My brother, as unbelievable as this may read, hunts invasive pythons in the Florida Everglades. This sort of tech and app development is alien to that world and although he uses a smartphone, most things are done with duck tape and muscle. For this app, I created a simple database for those like him to enter their captures and document them in a central space for later viewing. 

At the moment, the app is basic with the ability to hold the entry’s basic data, but the possibilities for expansion are nearly endless and I’m excited about the challenge of implementing them in the near future.

During the process of development, there were many things that I learned which are now committed to long-term memory. Some are simple, and some are more complex. 

On the simple side, when using string interpolation, remember to use double quotes! I went over code for an hour and what appeared correct in viewing but was returning an error, was simply due to using single quotes when I was using string interpolation.

On the more complex, the difference between render and redirect in your controller method is important. Although they both appear to be similar and show pages in your browser, redirect creates a completely new request for your browser an entirely different URL while render shows the user a specific view while preserving any variables instantiated in the controller action. This distinction is important! If you don’t want to lose access to information stored in a variable, choose to use render as redirect, with its new request, will erase anything that was contained within any variables. 

In sum, this was an exciting journey and I’m happy that I’m captaining this trip. On to the next project!
