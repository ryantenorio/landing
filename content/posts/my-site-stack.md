---
title: "My Site Stack"
date: 2022-01-04T21:22:33-08:00
summary: "Building something simple, that is a pleasure to use, and with minimized risk"
draft: false
---

TL;DR:

- domain: [Squarespace](https://www.squarespace.com/how-to/buy-a-domain)
- hosting: [Netlify](https://www.netlify.com/)
- website: [Hugo](https://gohugo.io/)
- theme: [Anatole](https://github.com/lxndrblz/anatole)

When I was revisiting my wife and I’s subscriptions at the end of the year, I realized I left my personal domain renewed but effectively dead. Months ago I was playing with some Azure credits from grad school and my domain name pointed to some compute resources in Azure that had long been terminated and swept away. Not entirely satisfied with just correcting the DNS records to the Squarespace defaults and leaving the parking page there, I set about spinning up a quick site to take advantage of the energy of the new year.

For the website itself, Hugo was an easy choice. I coded primarily in Go at the end of my time at Riot Games, and am a big fan of Go Templates so I knew I could install Hugo from source and continue to tinker with the code if I needed to. Alternatives included building my own site using React, my on-again off-again learning hobby, but for my personal landing page presence I wanted something that was **simple, a pleasure to use, and ultimately got the job done with minimal risk.** I will no doubt encounter many other learning exercises with this site, but using it as an outlet to write more React isn’t what I want to focus my energy into right now.

I admittedly never used Netlify before and was curious to try it, and it’s Starter Plan is perfectly sufficient for sites like this. I hooked up my Squarespace-managed domain but can see myself transferring to Netlify DNS in the future to simplify things, especially after experiencing how simple it was to point Netlify to my GitHub repository, press deploy, and be done with it.

For the posts, I plan to draft (like I did this one) in Notion and just export the markdown over. With Netlify's auth features, setting up a CMS would be possible as well in the future, but right now using Notion feels like a good fit because I can consolidate my drafts in the sample place that I am already brain-dumping personal notes.