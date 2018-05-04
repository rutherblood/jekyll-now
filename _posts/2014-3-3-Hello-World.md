---
layout: post
title: Intro.
published: true
---
I am here now. This is my my. I have been thinking of daily writing discipline for long now. Feels good and scary to start. My goals are this: to try not using cryptic language, not speak bullshit or in circles, **WRITE DAILY**, and be as naked as the title promises. I might not always be on a mountaintop though. This might feel like a microblog though it is not.

Here's what is on my mind right now. I've been working on a visual poetry project on and off over the last six months. This idea exists where I manipulate SVGs in various ways embedded with content like text patterned in various ways with animation, shadows and whatnot. A visual demo right [here](https://www.instagram.com/p/BiITms2H-16/). Here are the two problems I am facing.
-Compatibility: Various browsers implement the SVG spec differently. About what I'm interested in, Firefox implements the 'rotate' attribute of the 'text' tag in SVG differently than Chrome. This irritates me. Here's a visual demo: ![Firefox svg rotate demo](/images/howfirefoxdoesit.png)
How Firefox does it ^
![Chrome svg rotate demo](/images/howchromedoesit.png)
How Chrome does it ^
-Performance: Text shadows when coupled with animating the motion of text completely demolishes every modern browser. No browser promises a silky smooth rendering of this behaviour and starts lagging just to make it unusable. 

There are various ways I can fix this. For one, I could not use the features which are the bottleneck or I could create my own chimerical beast: Webkit + nanovg + ?(would only know once i start doing it). Doing anything like this ofcourse introduces a third problem. 
-Distribution: how do I push my improved results to an end user to whom I deliver my poetry over the web? Will think about that later. But this is an interesting problem in itself. 

So all this might occupy me on and off for the better part of the year. 

See you tomorrow,
Avi.
