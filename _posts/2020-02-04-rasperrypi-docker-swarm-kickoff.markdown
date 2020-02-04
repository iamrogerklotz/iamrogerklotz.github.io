---
layout: post
title:  "RaspberryPi Docker Swarm Project"
date:   2020-02-04 07:58:15 -0600
categories: jekyll update
---

Like many of you, I find myself to be a context-driven learner.  My most effective discovery is always coupled with real (hopefully interesting) use-cases I can explore organically rather than traditional course work, self-study via reading, etc.  Despite spending most of my time in the field helping end-users with their own challenges, it can be difficult at times to find problem statements that provide opportunities to explore particular technologies in which I’m interested.  In the few months to come, I knew I wanted to get a bit deeper with a few technologies: 

1) Containerization via Azure Kubernetes (AKS) and Docker  
2) Github and Azure Devops integration  
3) Basic Python and C# scripting   

I spent a few weeks noodling on what I could work with that was both relevant to these services and generally durable (from both a fun and utility perspective) that might provide some opportunity to "get smart".  Following my recent home network upgrade project including RaspberryPis for PiHole/Unbound DNS sinkholing, I figured I would continue the Pi theme.  

I stumbled on a TON of basic Python-based robotics projects on Amazon that seemed to tick the "fun" box, and decided building a Docker Swarm on a cluster of RaspberryPis might be an effective way to create some resiliency for my local DNS resolvers and provide some local capacity to run a few other containers.  As such, I snatched up this neat Yahboom tank project, a load of RaspberryPi 4s, random components and a fresh cup (or ten) of coffee...let's see where this goes.  

![useful image](/img/pi_swarm.png)