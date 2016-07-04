---
layout: post
title: Demystifying Large-Scale Scrum   
date: 2016-07-04
categories: scaling less
comments: true
---

[Large-Scale Scrum](https://less.works/), aka LeSS, falls on the simpler-side of the scaling techniques spectrum. The [basic framework](https://less.works/less/framework/index.html) consists of 9 events, 3 roles, 3 artefacts. Minimal elements are added once you go beyond 8 teams. It is this simplicity that makes the approach very effective, and yet also polarising. Let’s go through the framework in more detail.

# Principles


Before getting into the “doing” part, it is vital to learn about LeSS’ principles first. They answer a lot of “why” questions. They stop you from just mechanically doing the framework. They guide you as you start moulding LeSS to your organisational context. For brevity, I will only discuss a subset of the principles that are relevant to the discussion below. There rest can be found [here](https://less.works/less/principles/index.html).

## Principle: Large-Scale Scrum Is Scrum

In a nutshell, **LeSS is just Scrum done by multiple development teams**.* It is therefore a prerequisite for an organisation to understand the [Scrum Framework](http://www.scrumguides.org/) thoroughly before doing LeSS. It is very important to note that you are not scaling the Scrum Team (which the development team is part of). You retain a single Product Backlog. You have one Product Owner. You can have two to as many as sensible development teams pulling work from the same list guided by that one role. LeSS then adds additional events to facilitate further inter-team coordination. Like Scrum, the Scrum Master role stays the same. You can have one or more Scrum Masters, each coaching one or more development teams, the PO, and the organisation as a whole if needed.

## Principle: Empirical Process Control

LeSS, like Scrum, is “designed to be a framework within which you can employ various processes and techniques into it” (quoting the Scrum Guide). It strikes a balance between prescribing just enough rules for an organisation to start inspecting and adapting; and yet **have a lot of room for the organisation to add their own rules and processes to fit their situation and apply their learnings.** That is, the LeSS Framework is just a starting point. Just because a thing is not part of the framework doesn’t mean it cannot exist. If you end up having a lot of processes that resemble other more prescriptive frameworks, then great! You got to that point because of inspection and adaptation, not through prescription.

# LeSS Framework

As mentioned earlier, LeSS is just Scrum with additional events added on to it to facilitate inter-team coordination. 

LeSS Sprint is 1-4 weeks long. All development teams are all part of the same Sprint. 

Before the first Sprint starts, the development teams and the PO should’ve agreed on a baseline *Definition of Done* (exactly as defined by Scrum). Each development team has the option of adding more on this list, making them have a more robust definition than others (but not less). 

Each Sprint starts with a *Sprint Planning One* where all development teams (or their representatives) meet with the Product Owner. In this meeting, development teams and the PO agrees on what work is pulled from the Product Backlog and which development team will work on them in the Sprint.

![LeSS Framework](/assets/images/posts/less-101/less-framework.png)

*Sprint Planning Two* happens right after. At this point, most development teams do the meeting on their own. From the items pulled during the previous meeting, each development team plans on how they would do the work for the rest of the Sprint. Each development team would have produced their own Sprint Backlog after this meeting. 

*Daily Scrum* is the same. It is performed individually by each development team. It is recommended that they be scheduled in a staggered fashion. This is so other development teams can have the opportunity to send an observer to other development teams’ Daily Scrum should they desire so.

At some point within the Sprint, the development teams shall do a *Product Backlog Refinement* session. The goal is to be able to split and add more details into future work. With the PO and Scrum Master/s, this can be done by representatives of all development teams, a combination of development teams, or single development teams, depending on the situation and the work to be discussed.

It is understood that there will only be one *Potentially Shippable Product Increment (PSPI)* at the end of the Sprint. And so, it is expected that all development teams have integrated all their work. 


Towards the end, the *Sprint Review* happens. Stakeholders are given the chance to review the current PSPI, and provide feedback to the PO and the development teams during this meeting.

Finally, two types of retrospective sessions close the Sprint. The first one is the *Retrospective*. This consists of the development team and their respective Scrum Master doing the event as Scrum defines it. After which, an *Overall Retrospective* happens which is attended by representatives of all development teams, the PO, and the Scrum Master/s, with the goal of sharing learnings, and cross-team and organisational improvements.

# Adoption

For rules so simple, following them though will be quite difficult for a lot of organisations. This will entail them having teams that are cross-functional and cut across all components that the product has (i.e., having [feature teams](https://less.works/less/structure/feature_teams.html)). Various component-based backlogs should eventually be merged into an end-user-centric Product Backlog. The Product Owner will have a more intense role which will no doubt need a lot of help beyond the prescribed roles. 

LeSS understands these, and [prescribes ways](https://less.works/less/adoption/index.html) on how to adopt the framework. It would be great to go into detail through all of them. But for brevity’s sake, I will zero-in on one which, through personal experience, is the most helpful.

## Adoption Principle: Deep and Narrow over Broad and Shallow

It is [prescribed](https://less.works/less/adoption/three-principles.html) that it is better to apply LeSS in one product really well over applying LeSS in many groups poorly. While jumping all in might have merits, the changes that LeSS will introduce might prove to be too disruptive and too risky for some organisations. Doing Scrum well should first be the focus. Then scale it. 

# More with LeSS

This is by no means a thorough description of LeSS. But just enough to give you a grasp on what it is about. I invite you to explore the [official website](https://less.works/) further and get to know it more.


---

<small><b>*</b> LeSS uses the term “Team” while the latest Scrum Guide uses “Development Team.” For consistency and clarity, I am using the Scrum term throughout the article.</small>