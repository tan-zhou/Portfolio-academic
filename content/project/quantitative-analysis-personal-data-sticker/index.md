---
title: "Quantitative Analysis: Personal Data Sticker"
summary: I explore design principles for incorporating self-tracked step counts in data-driven stickers as a first step towards integrating these data into Snapchat posts or Instagram Stories.
tags:
- User Research  
- Survey
- Quantitative Analysis
- Personal Informatis
- Ubiquitous Computing
date: 2020-10-02T05:26:35.054Z
draft: false
featured: false

external_link: ""

image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: 'Image Credit: [**Sanpchat, Inc. on Screen Rant**](https://screenrant.com/snapchat-stickers-premade-custom-snaps-explained/)'
---

## Overview

**My Role:** User Researcher working under a leading researcher 

**Project Overview:**  I explore design principles for incorporating self-tracked step counts in data-driven stickers as a first step towards integrating these data into Snapchat posts or Instagram Stories.

**Methods:** Literature review, Survey, R, Original logistic regression, Statisitcal Modeling 

**Data Sources:** Survey, Literature  

**Deliverables:** Research Report

**Tools:** R Studio, JSON, Google Docs, Photoshop, Windows Powershell 

**Background/Context:** When people set health and behavior goals such as training for half-marathon, going to bed earlier, or losing weight, they often use social media to share their progress with friends and family ([Munson, 2012](https://ieeexplore.ieee.org/abstract/document/6240359)). [Epstein et al. (2015)](https://dl.acm.org/doi/abs/10.1145/2675133.2675135) identified that many people share personal informatics data to receive advisory information, emotional support, motivation, or accountability from their audience. However, prior research has shown that sharing data on social media is often met with ambivalence or no response at all ([Epstein, 2019](https://par.nsf.gov/biblio/10158861)). 
</br>
</br>
{{< toc >}} 

## Objective

When users send or receive Snapchat stickers that contain personal data about step counts,

* What factors influence user perceptions of those stickers?   
* How do these factors influence user perceptions? 
</br>
</br>

## Opportunity and Process

### Opportunity

In Snapchat or Instagram stories, people use stickers to customize their posts for informative, aesthetic, or entertaining purposes. These stickers are presented in a variety of categories depending on the containing information, presentations, styles, etc. Currently, these story features include methods for sharing some types of data, but the data is typically about the environment rather than the person who is sharing. (Habib et al., 2019). This gives me an opportunity to design a series of stickers to support more types of user-generated content that are focusing on sharers’ goals

In this project, I specifically explored and evaluated the design of stickers in one of the most commonly-tracked and often-shared domain -- step counts. 

### Process

we design a series of stickers for Snapchat that contains personal data about step counts and conducted an online survey on how design factors in the stickers influence people’s perceptions.  

Through literature review, I identified a series of predictors that potentially have an influence on Snapchat users and evaluation metrics to measure user perceptions. 
{{< figure src="stickers.png" caption="Samples of data-driven stickers incorperating step counts">}}
</br>

## Strategy

### User Perception measurements

I draw from literature in **online advertising and multimedia study** and measure user perceptions from the following five dimensions: {{<hl>}}**Entertaining, Privacy disclosure, Intention to use, Positivity, and Informative.**{{</hl>}}

Survey questions to measure entertaining:
>- I would find this Snap fun to send.
>- I would find this Snap fun to receive 

### Survey Sampling 

For this study, I’m interested in the opinions of adult Snapchat users. I choose to used convenience sampling for which I sent out recruiting emails to a list of a student research group. I also handed out copies of the flyer with links to the survey in university classrooms and meetings.

### Participants Screening 

I used two criteria to decide whether a person should be allowed to participate in the online survey: 

- Participants need to be at least 18 years old.
- Participants, on average, send or view at least one post on Snapchat per week.

### Regression Aanalysis

</br>
</br>

## Outcomes 

The analysis showed that: 
- we can see that recipients’ perceptions show more significant correlations with our independent variables, compared with sharers’ perceptions. 

- And that influence that factors have on the two sides – Sharer and Recipient – are not received equally. 

- When the relevance of stickers’ presentations changes from irrelevant to relevant, the ratings increase in both sharers and recipients’ intention to use, recipients’ level of entertaining, as well as informative. 

- Context is significant to ratings of Attitude and Entertaining from recipients.

- Stickers design with “Analogy” is perceived to be more exciting to receive than “Plaintext”. 
</br>
</br>

## Conclusion/Reflection

In the project, I explore design principles for incorporating self-tracked step counts in data-driven stickers as a first step towards integrating these data into Snapchat posts or Instagram Stories. I examine the effect of a sticker’s presentation style, domain-relevance, and background through surveys. We uncover the importance of domain-relevant backgrounds and stickers, identify the situational value of stickers styled as analogies, embellished, and badges, and demonstrate that data-driven stickers can make content more informative and entertaining. 

Some limitations of the study: I only received valid answers from 19 participants. This means that our regression analysis results are highly troubled by sampling error. Thus, it is unlikely to draw statistically valid conclusion from such a small sample size. Another flaw in the analysis is that no interaction terms were included in the model, due to that our data sample were simply not powerful enough to discern any differences. 

However, considering the pilot nature of the project, the process I took to reach these conclusions provided meaningful learning experience. Indeed, {{<hl>}}the learnings generated from this pilot directly influence the framing of research questions and analysis approach when the pilot was later developed into a larger, more comprehensive study with 506 total participants.{{</hl>}} The findings of the large-scaled study were published in  [Proceedings of the ACM on Human-Computer Interaction](https://dl.acm.org/doi/abs/10.1145/3415166) in October 2020.