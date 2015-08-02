---
layout: post
title: Making Distributed Teams Suck Less
date: 2015-03-05
categories: distributed-teams
comments: true
---

Three years ago in a [conference in Hong Kong](http://at2012.agiletour.org/en/hong-kong.html), myself and my buddy, Emerson Mills, were invited as speakers. His talk was entitled “How to Suck Less with Distributed Team,” which I obviously stole as title for this piece. What stuck was his observation of how the Open Source Software (OSS) movement can be a source of inspiration on how, well, to make distributed teams suck less. He was able to articulate something I can’t put my finger on for a long time. I’ve since had further discussions with clients on the topic in subsequent years. And what made me decide to finally write this post was when I had a meeting with the former owner of the company (let’s call him Mr. J) I’ve worked for. It was successful despite the difficulty of working with distributed teams. He wanted to figure out how to rebuild that magical experience we had and apply that to his new company, which is also set up in the same distributed fashion.

## My Background

I would say 95% of my career, I’ve worked in, with, and been somehow involved with distributed teams. As a developer, executive, and/or coach. It’s a mixed bag of experience, some that really sucked, others so-so, while at least a couple were successful. I will detail both companies later.

On the other hand, I’ve started my relationship with the OSS movement since I started falling in love with GNU/Linux in the late 90’s. Eventually contributing to OSS apps right until now.

## Distributed Teams and OSS

The merging of the professional and the OSS world for me started when I worked for a company that was heavily involved in building commercial open source software. Let’s call this Company A. I would say the experience was like doing typical OSS work, which meant dealing with people in different timezones, a surprise contribution from some unknown fellow every now and then, some engagement on community lists, etc. But this time, with a bit more predictability of what gets in a release and focus on where we are taking the product, mainly driven by commercial reasons. The company fully embraced the OSS culture it got exposed to, and used the same principles and practices in working with non-OSS clients as well. Everyone was on IRC, including clients. We operated more as a community rather than in strict hierarchies. Everyone collectively owns the source code. For the few years I was there, I experienced two commercial in-house OSS products get acquired by the dominant players in their respective industries, while a client also getting acquired by another bigger company.

I was inclined to think that that experience was a special case. Until I joined Mr. J’s company, Company B. For at least five years, I was exposed to working on multiple products, sharing one platform, customized and forked countless times, used by clients in 5 continents, and being developed in at least three countries simultaneously. And it was crazy. And it was fun. We disrupted the market enough that we got noticed by the big player in the field, and just had to acquire the company. I could think of many things that could have gone wrong, but didn’t.

In hindsight, I realized that the approaches these two companies took were very similar. And the OSS culture is pretty much the inspiration, whether deliberately or not.

## Commonalities

The following are things I’ve extracted from these experiences and what is observable in OSS work.

### 0. Avoid Distribution

I am cheating here. I just have to let this out first. If you have the chance, do not distribute your teams! OSS benefited a lot when companies supported it with its own workforce, most of whom are working in their respective offices. These patches of development effort from co-located groups accelerated the work further than when everyone was contributing independently from wherever they are. Imagine if you have all of them in one room?

### 1. Infrastructure to Support Real-time Communication

Like in OSS communities, most of us in Company A were on IRC. There were different channels depending on target audience: developers, clients, communities, etc. Until now, most major OSS communities still use this old but reliable technology. We have something similar in Company B. In this case, it was group chats in Skype. I understand if this was to happen now, we will be using better ones like Slack or Hipchat.

Although the overlap in timezones were not large in both situations, whenever we do catch each other online, it was great. Way better than email. And it somehow builds the bond between the group.

### 2. Meritocracy

Most of the time, OSS is being driven by a community. No one person controls the decision-making (unless you are Linus Torvalds). There weren’t any hierarchies. No software architect group to get approvals from. Just contribute whatever idea you have. And if they are with merit, they get merged into the mainline. This was pretty much how Company A operated. We did have team leaders. But the distinction in their role was more for administrative purposes. When we started developing, everyone was equal.

It was same with Company B. We did have a software architect person. But never did he act like a gateway of sorts. All ideas were just flowing from anyone from anywhere in the world. He was just like any one of us. He broadcasts his ideas like everybody else, prone to criticism and review by the whole group. I’ve seen ideas from the most junior people override those coming from more senior guys. And it was very motivating for everyone.

### 3. Automation

Most, if not all OSS I’ve worked with have, at the very least, an automated build system in place. Anytime someone breaks the build, everyone knows about it through IRC and email. And no one is allowed to work on anything other than fixing the build. Patches being submitted had to have automated tests attached, otherwise they won’t be accepted. Since Company A was pretty much an OSS company, we had that in place by default.

This is also true in Company B where there was heavy investment on automation. And they weren’t that expensive at all. We were using commodity hardware and open source tools.

### 4. Nothing Personal

Some code bashing gets a little intense in OSS. The fact that you have your code exposed to so many people, there will always be someone criticizing. And that’s a good thing. The downside is, if you are someone who gets very attached to your contributions, prepare for an uncomfortable emotional ride. In OSS, whatever you contribute is collectively owned by the group. Whatever is being said about the specific contribution is about the code, not the person. And this is something I learned early on in Company A. Nothing is personal when it comes to code.

While pair programming with the development manager of Company B, I noticed he kept on deleting names of people if they appear in the source code. I asked why he was doing that? He told me, we don’t want to promote this behavior of people getting attached to their code. It belongs to everyone and it is everyone’s responsibility to make sure they are in shape. It sure hell won’t get them promoted if their names appear on more classes and methods. There were people who left the company because they did feel offended by this and the constant criticism they felt they were getting. But the pride should not be taken from the lines of code you contributed, but the product you are building as a whole with the different people working with you.


### 5. Socialized Practices

OSS has standards. Whether it be coding standards, testing process, patch submission, etc. All these practices are often published publicly on community wikis. Whatever is written there is reflective of whatever the community agrees to do to work together better. It is not driven by any standards body, management, or client. The practices emerge from the collective experience of the group as they work, and evolves naturally over time. Like source code, these are prone to review and criticism by the community. Again by default, Company A abides by this.

Company B also documents their way of working through a wiki. All pages pertaining to practices and standards can be edited by anyone. No group has any control over it, even senior management. As with the other previous points above, everything is according to merit, not according to who wrote them.


On both, one thing was prevalent. The desire for a high degree of software craftsmanship. Most of the agreements being made revolves around test driven development, relevant design patterns, removal of code smells, etc. I bet regardless of situation, if you do reach this level, you can make anything work!

## Summing It Up

Most of the commonalities I’ve noticed revolved around full empowerment of the individual contributor and development community as a whole. Less restrictions means easier asynchronous movements. Rather than having an elite committee from which decisions flow from, the organic nature of this approach makes no one a bottleneck. Extra care must be made though in making sure all information and supporting infrastructure are fully available to the community. Source codes, servers, working agreements, conversations, etc. Unlike in co-located set up, a missing piece here is way riskier. This is because communication is more difficult given there can only be very little face-to-face conversations and there are differences in timezones.
