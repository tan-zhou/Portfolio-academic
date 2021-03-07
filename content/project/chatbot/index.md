---
title: "Usability Design: League of Legend Chatbot"
date: "2019-03-07T01:00:00.000Z"
tags:
- Usability Evaluation
- Generative Research 
- Survey 
- Interview

summary: How can the chatbot help facilitate collaborations among a temporarily
  assembled team in League of Legends?
draft: false
featured: false
external_link: ""


image:
  focal_point: Smart
  preview_only: false
  caption: "Image Credit: Riot Games, Inc."
---
{{< toc >}} 

## Overview

**My Role:** Lead UX Researcher in a team of 4 researchers and 2 developers. I contributed to every step of the project 

**Project Overview:** The big overarching question is to understand: How can the chatbot help facilitate collaborations among a temporarily assembled team in League of Legends? 

**Methods:** Interviews, Focus groups, Surveys, Thematics Analysis, Observations 

**Data Sources:** Interview transcripts, field notes, surveys, and in-game chat logs 

**Skills:** Interviewing, descriptive statistical analysis, thematic analysis, usability testings, survey

**Deliverables:** 1. research report and 2. Chatbot Prototype

**Tools**: Google Docs, Google Slides, Google Forms, Excel, OBS Studio, AutoHotKeys, Slack

**Background/Context:** In this project, the client’s request is for the team to study the usefulness of a chatbot in improving group collaboration. We grounded our research in the context of a League of Legends(LoL) game, where team collaboration is the key theme of the gameplay experience. In an LoL game, the temporarily assembled team meet various challenges in communication and coordination, such as not understanding other player’s intention or unresponded request for help. These challenges, if not resolved, could be detrimental to the team’s win in League’s fast-paced gameplay.    

**Client:** [Dakuo Wang, IBM Research](https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Dakuo.Wang) 

## Objective

* Understand what obstacles that impede collaborations among a temporarily assembled team in a League of Legends game
* Understand how might a chatbot help facilitate players collaborate with strangers on their team 
* Evaluate the usability of chatbot’s 

## Opportunity and Process

### Opportunity  

Many League of Legend players expressed that they have a better chance of winning and when they connected to their team. However, the current game doesn’t have any built-in mechanism that proactively encourages players to communicate with their teammates.

This provides a design opportunity for a chatbot that helps to promote team collaboration, whose pre-scripted words can provide additional useful information for the team members and engage them to better communicate with each other. 

### Process

A varsity of UX research approaches was used to design the chatbot. 

1. To understand problems players experience in team collaboration, we conducted interviews and focus groups 
2. To determine the chatbot functions, surveys were conducted  
3. Build a chatbot prototype with learnings from the previous two steps
4. Conducted a Wizard of Oz experiment to verify the usability of the functions

## Strategy 

### Interview and Focus Groups 

We conducted 9 interviews to gather general impressions, barriers, and positive experiences of team collaborations in their most recent gameplay. We encourage participants to describe frustrating situations where their teammate didn’t respond timely to their call for help, where they had difficulties with the built-in chatbot - the main channel of in-game communication, as well as positive moments when they felt connected to the team, and when they successfully operate tactics. Through participants' answers, we are able to understand the current state of in-game collaborations and where points of breakdown are.  

Took the learning from interviews, we follow up with 2 focus groups, where we specifically asked participants to list out the things they asked their teammates to do, the channel via which they asked and the responses they received for their asks. Through back and forth conversations and adding onto other people’s answers, participants were able to give us a quite extensive list of ideas.  

### Survey

After thematic analysis, we were able to synthesize a few themes. We designed a survey to gather quantitive data on the qualitative findings so we can priorities the list of topics by their rankings. 

### Prototype

Combing the quantitive and qualitative findings, we feel confident to develop prototype functions around the areas deemed more important. We developed a list of functions that shows what the chatbot will say in reaction to which scenario.  

### Wizard of Oz Test

Due to the fact that it is difficult to insert chatbot function into this mature and complex game system and the time is limited, we have decided to use a Wizard of Oz study, where a human operator will play as the chatbot in testing sessions. 

A fundamental requirement of a Wizard of Oz study is that the participants (four players in this study design) can not realize that it is a human sitting behind the curtain during the study. They must believe it is a fully automated chatbot that they are interacting with. One challenge for us is how can we ensure that participants won’t find out what’s behind the curtain. We leverage AutoHotKey, a scripting software that allows the test operator to send pre-scripted messages with keyboard shortcuts, to simulate the speed, accuracy, and efficiency of a real-world chatbot system. And the chatbot agent is responsible to determine when to send which message. 

![](https://lh5.googleusercontent.com/gfTNg3A8O8ZXYJl1ris1Xojf1hZQJjKi5HSLfktYS9hO-NjrJ0vAMy5EHRjawZFn-KzUkyBDXxAkcIGxSbrTafWq6uIqoAjGouLFK7PVG86yzJPQtUXzvtHXUY6dKKEcAzgugp3v)![](https://lh3.googleusercontent.com/6HUbA-_na_pWHFQGG8d-iymkfzRdb-kF1kfL_jsRwd8Hliqjg5A9TVYyuvLE9KtgQggVhzvDiDluNiykf_6j1noqbnguUUPU6J7NVbgwqxOuQNEBu0UnwGduyxafbaGw4fL3o5Qz)![](https://lh3.googleusercontent.com/A4EpnAAdyDdC4sfI8MnqT1Ep3tYl1dx1ZPIU9dBQ4Is21buQp0vrpoAKwKI33tS5aK_9e752pv7SuA20gcpV8lHn3WoQB-xY5WBC6KY7P9Tmp3n872jpE0DpHV_pp613jX-nqbYt)

### User Testing

1. We recruited participants via emails with deatils about the study and compensation
2. Participants played two rounds of the game, the first one without chatbot facilitating and the second with our Wizard of Oz chatbot (see picture)
3. After each round of the game, we measured their experience of the previous game through a survey
4. In the end, we measure the performance of the chatbot with extra questions   

(Testing design diagram)

## Outcomes

**Objective 1**

> Understand what obstacles that impede collaborations among a temporarily assembled team in a League of Legends game

* After the analysis of interview transcripts, the frequencies of codes indicated the following codes were mentioned the most: 
* “Play as a team”: Players don’t feel like they were playing as a team and want to enhance team collaboration. 
* “Extra information”: Players are not getting enough from the game’s built-in mechanism and want more information
* “Communication”: Players find it difficult to communicate with teammates. 
* “Encouragement”: Payers expect the chatbot to send encouragement when they played poorly, and praise when they played well  
* “Chatbox”: Players feel the current chat box in the game is difficult to use

![](https://lh5.googleusercontent.com/E0vwjb36IFxG1rVyk_ffbE_ljuq4izQLLIZxJQJMMSMVt-zxibbXRGZTf16ptXGQXMy06WmnA6pFgFPMkNDtXx7ZGJyLfNRIGkoRzLGqJgIvg1sG0bszBXU7yK-rpCtz61npGoI8)![](https://lh6.googleusercontent.com/wAq2MSR-s6f9Lavky607T-v0HpwmT8hnJAfze_iSycc6NhfahD4QGasNvKMuqBVO5dYb-KFxPGF93rvXmUqBu139FQQvrV3K-hUoDTC3p5DHDxWIyuJrMrhStfW0LKjTStcHBMF5 "Frequency visualization of the top codes ")

**Objective 2** 

> Understand how might a chatbot help facilitate players collaborate with strangers on their team

Medians were calculated for all Likert Scale measurements shown below

From the quantitive data, I learned that

* All groups overwhelmingly indicated that the “ping” system provides insufficient information to be truly helpful. 
* A chatbot can facilitate communication by providing contextual information tp “ping” signals 
* A chatbot that reminders the game would be a welcome feature to the majority of players
* A chatbot can aid in coordination at the beginning of the game for inexperienced players 
* A chatbot can help amplify players’ “call for help” when they are under attack
* A chatbot can encourage players to respond to calls for help

![](https://lh4.googleusercontent.com/DRfaugOdSjuUdBCDAG7igodhm4F6ezVhTMaGTHB860C5d1h3rSHgqVK43EwS83e_2xN6GKhVbBirDsID6KYwG2ojTpEqyjOrWehAAHptwkd90qkpuiKNrO6VuXceWo9H-GJg6kMn)

Age range and frequency of play were found not to have a significant effect on responses. 

![](https://lh4.googleusercontent.com/jC09TtJXmxeEk9c22qmt_YY9kpNJKya8TW1S5EuXA0RC9kDdIRoC7sueu1UqH0WkXMLEB8l0Taqjj2IrHpkDce4bNuJLq7MxJZiD6cg2al-h_tEmGFLlZ-8_7XNLXgTwBvqfBMYg)

After reviewing the interview, survey, focus group, and pseudo-pilot test data, we finally defined the functions of our chatbot. Picture 4 shows the function of our chatbot. We planned to increase players’ sense of being a team by adding functions as “introduction and remind before game” and mediating “When somebody insults you/team”. We decided to provide extra information as “Tower/Inhibitor/Base under attack” and “more information beyond pin”. The full function list here. 

**Objective 3**

> Evaluate the usability of chatbot’s

![](https://lh5.googleusercontent.com/N6Sl7_q3K0SielA8X4kOJ3vk6_BEm65na0xri-EXKAuhMYjPAkaFa1dbPQKu9PIZWsH_Up6K8hkR33ydnCadKPIqtkuqHSDgLMnyUNXR04Q4hAXGWZb8lTCA835D1kOgr_3grcmx)

Chart 1 gives some insight into how players generally saw improvements in every measured category, with players’ self-measurement and teammate-measurement of teamwork showing the greatest improvements. ![](https://lh3.googleusercontent.com/UoumwQ5cE1bLm4PoOjdx4h6Cxc-815LabEcufoIx21KVSbEPTcA5OfdNTp06QLjEHxijhXfyI_NogbAmsbMClTgIXQR4kZg8F2SemRufNh23ZORjkp5IyICfdFp-mJllC_RaAhUZ)

 As this was one of the primary goals of the project, we can tentatively say that we were successful in improving teamwork in the two games that were played with the chatbot. 

The few functions that asked which lanes players would play in before the game started also may have facilitated a greater sense of coordination. Reinforcement of player requests with chatbot phrases encouraging aid may have led to an increase of players’ perceptions of speedy responses and ease of getting help. The chatbot making teammates aware of what a player needed may have also led to greater awareness of teammates’ expectations. 

![](https://lh3.googleusercontent.com/w_0Pg5ij_T3-HYDx1bA12TDDTSMMh4uq0unU7hjRHryWYO2HRnZ5VWABSp-tWiM3r_oSo4NipL1m3g5Czn8K5j9mon33NOw6bwEqVjVQ26wqDysockbML3-nUe78K1M2mZJgRL9h)

The chatbot was appreciated to some extent on every measured scale. Participants strongly indicated that they enjoyed the chatbot’s personality, appreciated the chatbot asking others to help them, felt that the chatbot made them feel like part of the team, and believed the chatbot helped them coordinate. Since these were the primary functions that the chatbot was meant to fulfill, we can say that in these trials at least it was a success.

Players show weaker indications that they wanted to use the chatbot, that it had an effect on the game, that it helped them play “better,” that it was integrated seamlessly into the game, and that it did not interfere with their play experience.

## Key Takeaways 

### The Positives😀:

- **Did the chatbot help players to "collaborate” better?** </br>
**YES.** Whether it was direct or indirect collaboration. The burden of coordinating with teammates was alleviated.

- **Was the chatbot intrusive to their gaming experience?**</br>
**No.** It was easy for them to ignore messages that they didn’t care about and reminded them about helping/coordinating with their teammates.

- **Was the Wizard of Oz Study successful?**</br> 
**Yes!** A player asked me how we made the bot work so seamlessly.  LOL (pun-intended)

- Features of the chatbot were appreciated, especially Personality, functions, and encouragement.

### The negatives🙁: 

- One player mistook the chatbot to be another player for a few moments. 

- Distraction caused by the messages. One player was looking more at the chat-box now rather than the map to draw information.

- One experienced player found some of the things mentioned by the chatbot quite obvious. But on the flip-side, stated that that would work really well for entry-level players.

- Reliablity: We used players' self-reported perceptions of teamwork as our measurement, which negatively impact the reliability of the methods. In retrospect, we could've used a defined set of teamwork behaviors as our metrics. 


## Conclusion

In this project, we explored the use of a chatbot in League of Legends and its influence on team collaboration in games. At the initial stage of the project, we used multiple various methods to study players’ issues and needs, including interviews, focus groups, and surveys. Later, we built a prototype based on our research results and verified the model in two rounds of user tests using the Wizard-of-Oz method. Finally, both qualitative and quantitative methods were employed in the analysis of test results. 

As a result, we received positive feedback on the usefulness of our chatbot which suggests that our chatbot did improve players’ collaborations with their teammates without breaking the fairness in the game. Yet, there are still limitations to this project. More features can be added to the next iteration of the chatbot and new evaluation metrics should be employed to improve reliability.   
