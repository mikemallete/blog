---
layout: post
title: Definition of Done&#58; Misunderstood Organisational Agility Gauge 
date: 2019-06-23 11:00:00
categories: scrum definition-of-done maturity 
comments: true
---

"Is it done done? Un-done? Not done?" The topic of "Done" can get absurd really quickly, unfortunately. While I love Scrum, admittedly, sometimes it is hard to carry a conversation with a straight face: being served by a master, a team within a team, everyone is a "developer," oh and don't get me started on "grooming" :-) And then there's the "[Definition of Done](https://scrumguides.org/scrum-guide.html#artifact-transparency-done)." While Scrum is an effective framework, being nomenclature-challenged at times does not help in making important points obvious. Worse, misunderstood.

Behind all the "done done-ing" is a powerful concept that exposes organisational state of agility. It exposes the system as it is in an almost painfully transparent way.

## Weak and Robust

Let's first start with defining all the activities needed to be performed for a feature to be shipped to the end customers (or taken away, or modified) with the highest possible quality. This would include analysis, coding, dozens of testing practices, training and documentation, hours of reviews, deployments to various environments, etc. 

A perfect agile organisation has teams that do all these activities in a single sprint, every sprint. That is, they can add/remove/change features to what end customers already have in hand within a span of two weeks or less, endlessly. Imagine how fast this organisation can pivot, inspect, and adapt?

However, perfect organisations are hard to come by. Realistically, a lot of teams may only be able to do a subset of all these activities within two weeks. 

Two main considerations: capability and capacity. First, what are activities that the team can perform? Next, what activities makes sense to do now given it takes away time from potentially doing more features? That, in exchange for lowering risk and having something readily shippable (see: [Undone Work](https://less.works/less/framework/definition-of-done.html)). 

The Scrum Team ultimately agrees what these activities are. The more activities in the list means a more robust Definition of Done. Conversely, a weaker Definition of Done is one where more activities are not performed within the sprint.

## Misuse 

There was an organisation I worked with that started off with teams doing their best to have strong Definitions of Done. However, they were being assessed on how many features they were able to produce per sprint (ehem through velocity). They eventually dropped some activities (i.e., regression testing, deployment configuration, and code reviews) which gave them more time to work on more features per sprint. The weaker definition of done made them look faster. But only introduced more risk and uncertainty. They couldn't ship until introducing weeks of "hardening sprints" before release time.

With another organisation, the development and QA managers demanded that all scrum teams adhere to their very robust Definition of Done. The teams were very frustrated because they lack the skills and capability to do a lot of them. A lot of training and mentoring were needed - not to mention patience and understanding. 

Then there was this organisation that just couldn't expand their Definition of Done. There were too many "external" teams doing specialised work (e.g., security testing team, UX and design team, DevOps team, regression team etc.) and their respective managers wouldn't let go of their respective territories. The infrastructure was also not flexible enough to be managed by multiple teams simultaneously. The waiting and rushing dynamic between the Scrum Teams and the specialised teams was not fun at all. And it was very obvious that their development and production environments needed some upgrading.

![Getting to "Done" is an Organisation-wide Responsibility](/assets/images/posts/definition-of-done/done.jpg)

## System-wide Changes

Being able to have a more robust Definition of Done is an *organisation-wide responsibility*. It is not just on the individual Scrum teams. Pursuing this may entail organisational restructures, architectural and environmental changes, capability uplifts, etc. System-wide changes. It also depends a lot on the political climate within the organisation, and how much the organisation is willing to invest in becoming agile. You can't just treat "done done" with nonchalance.
