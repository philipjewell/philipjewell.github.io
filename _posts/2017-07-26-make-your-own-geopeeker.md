---
id: 350
title: Make your own GeoPeeker
date: 2017-07-26T23:30:59+00:00
author: philipjewell
layout: post
guid: http://philipjewell.com/?p=350
permalink: /blog/make-your-own-geopeeker
image: http://philipjewell.com/wp-content/uploads/2017/07/geohub2.0.jpg
categories:
  - Featured
---
In the past when working in support, I have used GeoPeeker in order to see if someone&#8217;s website had caching issues, geographical specific content, or just to see if anyone else (anywhere else) was experiencing the same issues I have.

The downfall: working in support for a company, others have the same idea and can cause you to meet your daily or hourly limit for your IP address. Being tech savvy and doing things on the cheap when I can, didn&#8217;t quite want to pay for a GeoPeeker plan. They most definitely have their benefits and are a great tool. I just hate to pay for something when I can do it myself.

So that is what I did. Using six different servers, I made proxy script that executes a PHP curl with one central hub that iframes those curl requests. I know&#8230; No one likes iframes these days, but it works!

I decided to be a little more verbose and transparent about the kinds of tools that aren&#8217;t work specific on my Github. If this is something you like the idea of, you can find this project here:  
https://github.com/philipjewell/web-tools#geohub

<div class="github-widget" data-repo="philipjewell/web-tools">
</div>