---
layout: post
comments: true
title: New website based on Jekyll
---

I have decided to abandon my existing website and start over. First of all, I needed to update the design. 
It really needed a refresh. Elements needed to be removed, texts needed updating and I needed to rethink 
what I needed it for. 

<!--more-->

I reconsidered the Umbraco platform. Did I really need it? Not really actually, I rarely used the backend
for anything special. I hardly added any new content, even though I really want to get my blog going. If
I should continue to use it, I needed to upgrade to the latest version of Umbraco (v7.4) just for good
measure. Additionally, I have it hosted on Azure. For a site of my size, the Azure brackets makes it more
expensive than another standard webhotels. The reason I choose Azure to begin with was to learn the Azure
stack better. However, I needed to reconsider everything. I already have a Github account, and their 
project websites are free so why not change?

Github projects does not support any server scripting languages and having everything in static HTML was
indeed an option, but not really viable longer term solution.

However, Github supports [Jekyll](https://jekyllrb.com/). A ruby framework for converting static files into
even more static files. A few variable tricks and includes. Everything occures at compile time, which 
happens at every push to the Git repository. It is not really supported on Windows, so I had to jump
some hoops to get it to work. However, I like it for now. It is dead simple and easy to maintain.

 