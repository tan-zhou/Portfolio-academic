---
title: "Accessibility Design: Food Journaling through Conversational Agent"
date: 2021-03-07T06:32:08.689Z
summary: In situations when people need to document foods they eat daily via a
  voice assistant, how can we design the dialogic flow to facilitate users’
  reflections on their eating habits?
draft: false
featured: false
external_link: '""'
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
## Overview



My Role: UX Researcher and Designer



Project Overview: When people document foods they eat daily (food journaling) via a voice assistant, how can we design the dialogic flow to facilitate users’ reflections on their eating habits? 



Methods: Literature review, Interviews, Competitive Analysis, Google Assistant, Amazon Alexa 

Data Sources: Interview transcripts, Literature  

Skills: Interviewing, descriptive statistical analysis, thematic analysis, usability testings, survey

Deliverables: 1) Research report, 2) Persona, 3) Design Patterns

Tools: Google Docs, Google Slides, Google Forms



Background/Context: Studies following diabetic patients and weight watchers showed food journaling as an effective way of managing diets. Although automating the journaling process using smart devices could increase adherence by lower manual labors and the mental burden, it could also lead to a decrease in users reflecting on collected data. After searching the field, there isn’t a well-design voice-based interface valuable that supports food tracking. 

## Objective

* Understand users needs and pain points in food journaling 
* Design the flow of the conversation and its underlying logic to facilitate voice-based food journaling
* Adapt Nielsen’s heuristics to evaluate voice-based interface  



## Opportunity and Process

### Opportunity

We delved into persuasive design literature to create design patterns that enhance the 



 

### Process

In order to define the users’ requirements, I conducted a competitive analysis of existing tools that support voice-based food journaling. I also interviewed two participants, who have precious used their mobile phones for food journaling, to understand the needs, behaviors, and motivations of the user during the journaling process. 

Using the information collected from the field review and interview, I write a series of sample dialogs to capture the “sound-and-feel” of the interaction understand different scenarios. They convey the flow that the user will experience and allow me to experiment with different design strategies, such as how to promote the discoverability of new features or how to confirm a user’s request.



At the usability test stage, a friend who is unfamiliar with the project was asked to role-play the simple dialogs with me. This helped me curate the conversation, defining the flow and its underlying logic that represents the complete food journaling experience. I also conducted system evaluations with a set of adapted heuristics to expose usability issues.



## Strategy

Exploratory Interviews

My initial goal was to understand users’ needs in the journaling process through exploratory interviews. Two interviews were conducted with informants who have experience in food journaling. 



Heuristic Evaluation

Awareness of system status

The Nielsen heuristics emphasize the visibility of system status. Although visibility does not apply to voice-based interfaces, feedback is still important. The system needs to inform users about what it is doing in a timely and appropriate fashion. 



Error prevention 

As with any system, it is better to prevent errors from occurring or handle them in a way that is less intrusive to user experience. This becomes even more important in a system with no visual interface since people cannot “unsay” what they have previously said. This system addresses this issue by providing users their options for the next step explicitly in the conversation. 



Flexibility and efficiency



Novice users become experts after they are familiar with the system and experts need efficiency. As a result, some instructions, which would be helpful to novice users, may become redundant to an expert. The logic flow suggests that it supports setting up customized shortcuts for frequently used terms to speed up the process. 



Accessibility 

 Voice based interaction is great for people who are unable to use a graphic interface. It doesn’t require input from hands which offers more accessibility since lots of real-world tasks require both hands. Users could interact with the system while carrying groceries, cook a meal, or drive a car. 



Ambiguity



people aren’t machines. They don’t speak in syntax but use synonyms and homonyms. They sometimes forget what things are called and pause, or use a metaphor to describe them instead. People could comprehend this freestyle, so should voice technology or any least to a certain extend. When the user pause, the system just repeats the previous response with a much more detailed instruction of what users can do until they make a selection.



Discoverability  



How is the system going to enable people to discover possible actions? The invisibility of a voice-based interface makes it difficult for users to browse and explore new ways of interaction they could have with the system. In this logic flow, new actions will be introduced in the form of quick tips at the end of each conversation (except customized shortcuts). And during the reflection stage when a user views their journals on a display, users are suggested new interactions that are more efficient or accurate for their food journaling.



Multimodal Reflection



In this five-stage personal informatics model proposed by Li et al. \[], the reflection stage may involve looking at lists of collected personal information or exploring or interacting with information visualizations. For a voice-based system, it is inherently difficult for exploration and impossible for visualization. To address this issue, the system expands to another modal for long-term reflection. The design flow falls back to a visual interface after collecting information. Users can access their journaling data through smartphone and on the website where auxiliary graphical interfaces would help visualizing personal information. However, this part is not accomplished during this project. In addition, the logic flow also addressed short-term reflection by repeating the list of input for confirmation during every conversation. 



## Outcomes  

* Dialogic flow for food journaling via voice assistant
* Sample dialogs for voice-based interactions



![](https://lh6.googleusercontent.com/mLcCIMme-TSHIrtRCe9GqDrf1WXf4blBtlHC48aIGfIXr9nuJWP5ySFhhZNG4coAAamdGdNDaYW2PNyKTMjw0WVEFZQp80S7A2B__33IVdZsVfUi2dm1uma7jo9DnKXOKIDnQdUz)



The logic flow of conversation shows four stages of the voice-based foo journaling system. In the beginning, users start to engage with the voice assistant by saying specific trigger words just like other voice-triggered voice assistants. In the collection phase, different approaches are taken for novices and experts. The reflection stage suggests a multimodal approach – short-term reflection is embedded in the conversation while long-term reflection relies on reports and visualizations after the food records are synced to another display. At the final stage, users could take actions after they reflect on their food journal to correct something that incorrectly recorded via speech, set a shortcut for more efficient interaction, or explore new actions they just find out.



Sample Conversations



A novice user adding Food. 

\- Hi My Food Journal,  

\- Hi! Welcome to My Food Journal. I can help you add new food to the journal or check previous journals. Which would you like? 

\- Add new food.  

\- Okay, go ahead and say the names. 

\- Ummm….

\- You can add food by saying its name and serving size. Go ahead. 

\- One in-n-out double-double, French Fries, and Chocolate shake.

\- Got it. Would you like to add more?

\- No, that’s it.

\- Sure. I got one in-n-out double-double, a medium French Fries, and a medium chocolate shake. Is that correct? 

\- Yup.

\- Alright. Quick tip: You can always add more food by saying “Hi My Food Journal, quick add.”



In the sample conversation, we can see that the system always provides an affirmation when it gets any information from the users. In the end, new actions were introduced in the form of quick tips at the end of each conversation to increase discoverability. 



Quick add and customized shortcuts

\- My Food Journal, quick add.

\- (A response tone playing indicating the system is listening)

\- “McDonald Lunch Combo”

\- (A confirmative tone playing indicating the system have received your information)



In this example, a user has set up a shortcut named “McDonald Lunch Combo” which includes a list of food they usually get from McDonald. This way the user could skip the instructive steps and complete the journaling in a much more efficient fashion.



## Conclusion/Reflection

The focus of the project is on the bottom-up process of conversation design. After gathering insights from competitive analysis, interviews, acting, and adapted heuristic evaluations, I delivered a dialogic flow for food journaling via voice assistant and sample conversations. The next would be expand the dialogs based on the flow and implement the system on a real-world voice assistant platform. An implemented system could be used in further evaluation for people's interaction with food journaling via voice assistant in the real world.