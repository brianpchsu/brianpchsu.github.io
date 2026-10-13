---
layout: post
title: "Blameless Postmortems: Reviewing Incidents Without Pointing Fingers"
date: 2021-10-07
description: "When a massive outage takes down services worldwide, Silicon Valley culture does not turn it into a witch hunt. This post describes my company's SEV system and blameless reviews: instead of blaming the person who made the mistake, you find the system problems that let one error reach production."
lang: en
permalink: /blog/blameless-postmortems/
topics: [career]
featured: true
translation_ref: blameless-postmortems
---

* Contents
{:toc}

This Monday, my company had a major incident. Many users could not reach our services, but oddly, employees could not get on the internal network either. We could only communicate by email. For the details of what happened, see the engineering blog post (More details about the October 4 outage).

I have seen people share the incident and speculate that with a global outage and losses this huge, whoever caused it is surely going to be fired. That kind of guess mostly comes from not knowing Silicon Valley culture (though I am not sure most Silicon Valley companies are really like this, haha).

## SEVs and Blameless Reviews

At my company, a serious incident is called a SEV (Site EVent), graded by severity, and this global incident was the highest severity level. While an incident is ongoing, the oncall engineers of the relevant teams, and any engineer who can help, join in to handle it. After the incident is fixed, we hold a review meeting, a SEV Review. The meeting is not about settling scores. It is about what we learned from the incident, and how to strengthen our systems and processes so the same thing does not happen again, or so we can recover faster when something similar happens. If one engineering mistake can break the system, was our review process not enough? Did the integration tests or simulation tests fail to catch the problem? Did we roll out too fast, letting an error hit many users directly? Were there factors the system had never considered? Or does the whole process make it too easy for a human error to reach production? If one engineer's single mistake can take down the entire site, could a hacker attack cause the same damage? In the meeting, nobody blames the engineer who wrote the code or script that caused the incident, because that helps nothing. A failure is usually the result of a series of problems, and a blame culture after an incident also discourages everyone from trying new things in the future.

Former VP Vijaye also wrote about his experience with blameless SEV reviews, along with an interesting personal story. If you are interested, check out his post, [Blameless SEV review](https://www.linkedin.com/posts/vijaye_blameless-sev-review-at-facebook-whenever-activity-6851577359695527936-F4U0/).

What are postmortems like at your company? Feel free to share.

#IHaveCausedASEVMyself

---

*This post was originally published on my former blog, 「半路出家軟體工程師在矽谷」, on October 7, 2021. The blog is now offline, and the text is preserved via the Wayback Machine. It has been lightly edited for this site.*
