---
title: "Voice Interaction Design: Food Journaling via Voice Assistant"
date: 2019-03-07T06:32:08.689Z
summary: In situations when people need to track foods they eat daily via a
  voice assistant, how can we design the dialogic flow to facilitate users’
  reflections on their eating habits?
tags: 
- Voice User Interface
- Interaction Design
- User Research
- Ubiquitous Computing
- Competitive Analysis
- Heuristic Evaluation
- Usability Evaluation
draft: false
featured: false
external_link: ""
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  Caption: 'Image Credit: [**Team VOW** on **thevoiceofwoman**](https://www.thevoiceofwoman.com/app-guide-for-food-journaling/)'
---
## Overview

**My Role:** UX Researcher and Designer

**Methods:** Literature review, Interviews, Competitive analysis, Journey mapping, Heuristic evaluation

**Data Sources:** Interview transcripts, Literature  

**Deliverables:** Research report, Dialogic flow, Sample conversations

**Tools:** Google Assistant, Amazon Alexa, Google Sheet 

**Background/Context:** Studies following diabetic patients and weight watchers found food journaling to be an effective means of managing one’s diet. Although automating the journaling process using smart devices could increase adherence by decreasing the effort and mental burden required, it could also lead to a decrease in users reflecting on collected data. After searching the field, I failed to find a well-designed voice-based interface that supports food tracking.
 
**Project Overview:** The overarching goal was to answer the question "When people track foods they eat daily (food journaling) via a voice assistant, how can we design the dialogic flow to facilitate users’ reflections on their eating habits?". 

</br>
</br>
{{< toc >}} 

## Objective

* Understand users needs and pain points in food journaling 
* Design the flow of the conversation and its underlying logic to facilitate voice-based food journaling
* Adapt Nielsen’s heuristics to evaluate voice-based interface  
</br>
</br>

## Opportunity and Process

### Opportunity

The study of automated food journaling show that such automation could lower the burden of tracking and increase adherence ([Beenish et al., 2016](https://dl.acm.org/doi/abs/10.1145/2858036.2858554)), but it could lead to a decrease in users reflection on collected data([Choe et al., 2014](https://dl.acm.org/doi/abs/10.1145/2556288.2557372)). Also, the majority of these studies leverages only graphical interfaces, building on the legacy of hand-and-finger input devices.These approaches are limited by the required input since users might not always be able to log their entries. 

Voice assistants like Amazon Alexa, Apple Siri, and Google assistant are getting more and more ubiquitous. Their support of hands-free interaction makes voice-based food journaling an ideal use case for voice assistants.

{{< figure src="voice_assistant.jpg" caption="Voice Assistants are more accessible than ever.     Photo: Stratablue.com">}}

### Process

In order to define the users’ requirements, I conducted a competitive analysis of existing tools that support voice-based food journaling. I also interviewed two participants who have previously used their mobile phones for food journaling to understand users’ needs, behaviors, and motivations of the user during the journaling process. 

Using the information collected from the field review and interviews, I wrote a series of sample dialogues to capture the “sound-and-feel” of the interaction under different scenarios. These sample dialogues convey the flow that the user will experience and allow me to experiment with different design strategies, such as how to promote the discoverability of new features or how to confirm a user’s request.

At the usability test stage, a friend who is unfamiliar with the project was asked to role-play the simple dialogues with me. This helped me curate the conversation, defining the flow and the underlying logic that represents the complete food journaling experience. I also conducted system evaluations with a set of adapted heuristics to expose usability issues.
</br>
</br>

## Strategy

### Exploratory Interviews

My initial goal of exploratory interviews was to understand users’ needs in the journaling process. Two interviews were conducted with informants who had experience journaling the food they ate. 

### Heuristic Evaluation

**1. Awareness of system status**

The Nielsen heuristics emphasize the visibility of system status. Although visibility does not apply to voice-based interfaces, user awareness and feedback are still important. The system needs to inform users about what it is doing in a timely and appropriate fashion. 

**2. Error prevention** 

As with any system, it is best to prevent errors from occurring or handle them in a way that is less intrusive to user experience. This becomes even more important in a system with no visual interface since people cannot “unsay” what they have previously said. This system addresses this issue by providing users their options for the next step explicitly in the conversation. 

**3. Flexibility and efficiency**

Novice users become experts after they become familiar with a system, and experts benefit from efficiency. As a result, some instructions, which would be helpful to novice users, may become redundant to experts. The logic flow supporting setting up customized shortcuts for frequently used terms to speed up the process. 

**4. Accessibility** 

Voice based interaction is great for people who are unable to use a graphic interface. It doesn’t require input from hands which offers more accessibility since users could interact with the system while carrying groceries, cooking a meal, or driving a car. 

**5. Ambiguity**

People don’t communicate in syntax the way computers do. They sometimes use metaphors or slang. They sometimes forget words or pause when speaking. Voice technology should accommodate the users’ communication style and needs. When the user pauses, the system just repeats the previous response with a much more detailed instruction of what users can do until they make a selection.

**6. Discoverability**  

The invisibility of a voice-based interface makes it difficult for users to explore new ways of interacting with the system. In this logic flow, new actions will be introduced in the form of quick tips at the end of each conversation (except those involving specific customized shortcuts). During the reflection stage when a user views their journals on a display, the system suggests new interactions that are more efficient that would increase the accuracy of the users’ food journaling. 

**7. Multimodal Reflection**

In the five-stage personal informatics model proposed by [Li et al.(2010)](https://dl.acm.org/doi/abs/10.1145/1753326.1753409), the reflection stage may involve looking at lists of collected personal information or exploring or interacting with information visualizations. For a voice-based system, exploration is inherently difficult for exploration and visualization is impossible. To address this, the logic flow allows for short-term reflection by repeating and confirming the list of input items during every conversion. The system also expands to another modality for long-term reflection. The design flow falls back to a visual interface after collecting information. A user can access their journaling data on their smartphone and on the website where auxiliary graphical interfaces would be available. However, this part is not accomplished during this project.
</br>
</br>

## Outcomes  

* Dialogic flow for food journaling via voice assistant
* Sample dialogue for voice-based interactions



![](https://lh6.googleusercontent.com/mLcCIMme-TSHIrtRCe9GqDrf1WXf4blBtlHC48aIGfIXr9nuJWP5ySFhhZNG4coAAamdGdNDaYW2PNyKTMjw0WVEFZQp80S7A2B__33IVdZsVfUi2dm1uma7jo9DnKXOKIDnQdUz)



The logic flow of conversation shows four stages of the voice-based food journaling system. In the beginning, users start with the voice assistant by saying specific trigger words. In the collection phase, novices and experts can take different approaches. The reflection stage suggests a multimodal approach – short-term reflection is embedded in the conversation while long-term reflection involves reports and visualizations viewed on another display. At the final stage, users can take actions after they reflect on their food journal. They can correct something that was incorrectly recorded via speech, set a shortcut for more efficient interaction, or explore new ways to interact with the voice assistant.


### Sample Conversations

A novice user adding Food. (Inputs from the user is highlighted)

>{{<hl>}}\- Hi My Food Journal, {{</hl>}}  

>\- Hi! Welcome to My Food Journal. I can help you add new food to the journal or check previous journals. Which would you like? 

>{{<hl>}}\- Add new food. {{</hl>}} 

>\- Okay, go ahead and say the names. 

>{{<hl>}}\- Ummm… {{</hl>}}

>\- You can add food by saying its name and serving size. Go ahead. 

>{{<hl>}}\- One in-n-out double-double, French Fries, and Chocolate shake.{{</hl>}}

>\- Got it. Would you like to add more?

>{{<hl>}}\- No, that’s it.{{</hl>}}

>\- Sure. I got one in-n-out double-double, a medium French Fries, and a medium chocolate shake. Is that correct? 

>{{<hl>}}\- Yup.{{</hl>}}

>\- Alright. Quick tip: You can always add more food by saying “Hi My Food Journal, quick add.”

In the sample conversation, note that the system always provides an affirmation when it gets any information from the users. At the end of each conversation, new actions are introduced in the form of quick tips to increase discoverability. 

</br>

Quick add and customized shortcuts (Inputs from the user is highlighted)

>\- My Food Journal, quick add.

>{{<hl>}}\- (A response tone playing indicating the system is listening){{</hl>}}

>\- “McDonald Lunch Combo”

>\- {{<hl>}}(A confirmative tone playing indicating the system have received your information){{</hl>}}

In this example, a user has set up a shortcut named “McDonald Lunch Combo” which includes a list of food they usually get from McDonald. This way the user could skip the instructive steps and complete the journaling in a much more efficient fashion.
</br>
</br>

## Conclusion/Reflection

The focus of this project was on the bottom-up process of conversation design. After gathering insights from competitive analysis, interviews, sample conversations, and adapted heuristic evaluations, I delivered a dialogic flow for food journaling via voice assistant and sample conversations. The next step would be to expand the dialogs based on the flow and implement the system using a real-world voice assistant platform.

