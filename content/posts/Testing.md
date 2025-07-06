---
date: '2025-07-05T21:32:57-07:00'
draft: false
tags: ['hugo', 'github', 'static-site']
title: '"HelloWorld"; or, "An Interesting Thing Happened On The Way To The Static Site"'
---


## Origins:
In 2012 I looked into running a VPS for some web hosting.  Intended to just host a personal blog and some other projects.  I chose [Linode](https://www.linode.com/) as AWS free trials only went so far, and I didn't want to worry about variable costs.  Linode was great for a flat rate; offered public IPv4 addressing, load balancing, etc.  Setting up a simple LAMP stack and Fail2Ban, which was OK for me. Beyond just an initial page; I didn't do much more than shell in occasionally to do system maintenance, or run some connectivity tests from Linode's network to my home network.  

I'm still paying a monthly fee for this.  I'll probably re-evaluate that soon


## The Present:
Recently, I've been doing a lot of [go](https://go.dev/).  
On a whim looked up go based static site generators and found [Hugo](https://gohugo.io/).  

After building a static site locally, I was curious about the options on how to host it.  I had heard something about Github pages, but didn't dive too deep on that initially.  I looked into options at Linode; but there's not really a good fit there for a simple static site.  I could spin up another VPS, but that seemed a bit overkill and costly.  I went all the way through setting up a Docker Image repository and Application within Google's Cloud Run.  Which is really cool stuff and the cost would potentially be much lower than what I'm paying Linode today.

I was at the point where I was going to setup some test CI to Cloud Run, but ran into some docs about how this type of thing is done natively in Github.  Almost instantly I found this to be:

- A lot simpler
- Familiar, since I use Github Actions in my professional work
- Free for public repositories
- It's also a lot 'closer' to the code, if that makes any sense.

## Beyond:
I'm digging Hugo so far, and setting this up in Github Actions is the next step.  Wish me luck ,👋 bye!
