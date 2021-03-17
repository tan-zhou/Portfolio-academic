---
title: "Usability Design: League of Legend Chatbot"
date: "2018-03-07T01:00:00.000Z"
tags:
- Usability Evaluation
- Survey 
- Interview
- User Research
- Interaction Design 

summary: How can the chatbot help facilitate collaborations among a temporarily assembled team in League of Legends?
draft: false
featured: false
external_link: ""


image:
  focal_point: Smart
  preview_only: false
  caption: 'Image Credit: [**Riot Games, Inc.**](https://www.riotgames.com/en)'
---

## Overview

**My Role:** Lead UX Researcher in a team of 4 researchers and 2 developers 

**Methods:** Interviews, Focus groups, Surveys, Thematics analysis, Observations, Moderated usability test, and Descriptive statistical analysis 

**Data Sources:** Interview transcripts, Observation notes, Survey result, and In-game chat logs 

**Deliverables:** Research report and Chatbot prototype

**Tools**: AutoHotKeys, League of Legend spectator mode, Google Docs, Google Slides, Google Forms, Excel, OBS Studio, and Slack

**Background/Context:** In this project, the client requested our team study the usefulness of a chatbot for improving group collaboration. We grounded our research in the context of League of Legends games, where team collaboration is the key theme of the gameplay experience. In an LoL game, the temporarily assembled team encounters various challenges in communicating and coordinating, e.g. not understanding other player’s intentions, requests for help going unanswered. These challenges, if not resolved, could be detrimental to the team in League of Legends’ fast-paced gameplay.

**Project Overview:** The overarching question is to understand "How can a chatbot help facilitate collaborations among a temporarily assembled team in League of Legends?". 

**Client:** [Dakuo Wang, IBM Research](https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Dakuo.Wang) 
</br>
</br>

{{< toc >}} 

## Objective

* Understand what obstacles impede collaborations among a temporarily assembled team in League of Legends
* Understand how a chatbot might help players collaborate with strangers on their team 
* Evaluate the usability of the chatbot 
</br>
</br>

## Opportunity and Process

### Opportunity  

Many League of Legend players said that they had a better chance of winning when they coordinated with their team. However, the current game doesn’t have any built-in mechanism that proactively encourages players to communicate with their teammates. A chatbot can provide additional useful information for the team members and engage them to better communicate with each other. 

### Process

Several UX research approaches were used to design the chatbot. 

We completed interviews and focus groups to understand problems players experience in team collaboration. 
We conducted surveys to determine the chatbot functions. 
 We built a chatbot prototype with learnings from the previous two steps.
We carried out a Wizard of Oz experiment to verify the usability of the functions
</br>
</br>

## Strategy 

### Interview and Focus Groups 

We conducted 9 interviews with players to learn more about their attitude toward and experience with team collaborations during their most recent gameplay. We encouraged participants to describe frustrating situations where their teammate didn’t respond timely to their calls for help, where they had difficulties with the built-in chatbot - the main channel of in-game communication. We also asked about positive moments when they felt connected to the team, and when they successfully operate tactics. These interviews allowed us to better understand the current state of in-game collaborations and their points of breakdown.  

We then held 2 focus groups, in which we specifically asked participants to list the things they asked their teammates to do, the channels through which they made their requests and the responses they received from their teammates. The focus groups’ back and forth conversations allowed us to generate a rather extensive list of ideas for potential chatbot functions.  

### Survey

After thematic analysis of the interviews and focus groups, we synthesized a few broad genres of chatbot functions to improve upon. We designed a survey to gather quantitative data on the qualitative findings so we could then prioritize the list of topics. 

### Prototype

We then developed prototype functions around the areas deemed most important. We developed a list of functions showing what the chatbot would say in response to a variety of scenarios.  

### Wizard of Oz Test

Due to the difficulty of inserting a chatbot function into an already mature and complex game system, we have decided to use a Wizard of Oz study in which a research team member would play as the chatbot in testing sessions. 

A fundamental requirement of this Wizard of Oz study is that the participants cannot know that an actual person is behind the curtain. Instead, they must believe they are interacting with a fully automated chatbot. 

{{< figure src="chatbot2.png" caption="Prototype Chatbot `Introduction` Function" >}}
{{< figure src="chatbot3.png" caption="Prototype Chatbot `Encourage` & `Response` Function" >}}

Although this was a challenge, we leveraged [AutoHotKey](https://www.autohotkey.com/) - a scripting software that allows the test operator to send pre-scripted messages with keyboard shortcuts - to simulate the speed, accuracy, and efficiency of a real-world chatbot system. 

### User Testing Process 

1. Recruit participants via emails with details about the study and compensation
2. Participants play two rounds of the game, the first without a chatbot facilitating and the second with our Wizard of Oz chatbot
3. Survey participants about their experience after each round of game 
4. Complete additional survey about the chatbot’s performance after final round 


</br>
</br>

## Outcomes

>**Objective 1:** Understand what obstacles impede in-game collaborations among a temporarily assembled team in a League of Legends game

After analyzing interview transcripts, the most highly mentioned codes were: 
* “Play as a team”: Players don’t feel like they were playing as a team and want to enhance team collaboration. 
* “Extra information”: Players are not getting enough from the game’s built-in mechanism and want more information
* “Communication”: Players find it difficult to communicate with teammates. 
* “Encouragement”: Players expect the chatbot to send encouragement when they played poorly, and praise when they played well  
* “Chatbox”: Players feel the current chat box in the game is difficult to use

![Frequency visualization for top codes](https://lh6.googleusercontent.com/wAq2MSR-s6f9Lavky607T-v0HpwmT8hnJAfze_iSycc6NhfahD4QGasNvKMuqBVO5dYb-KFxPGF93rvXmUqBu139FQQvrV3K-hUoDTC3p5DHDxWIyuJrMrhStfW0LKjTStcHBMF5)



>**Objective 2:** Understand how a chatbot might help facilitate collaboration among a team of strangers

Medians were calculated for all Likert Scale measurements shown below

![](https://lh4.googleusercontent.com/DRfaugOdSjuUdBCDAG7igodhm4F6ezVhTMaGTHB860C5d1h3rSHgqVK43EwS83e_2xN6GKhVbBirDsID6KYwG2ojTpEqyjOrWehAAHptwkd90qkpuiKNrO6VuXceWo9H-GJg6kMn)

From the quantitative results, we determined that a chatbot could:

* facilitate communication by providing contextual information to “ping” signals 
* remind players their progress 
* aid in coordination at the beginning of the game for inexperienced players 
* amplify players’ “call for help” when they are under attack
* encourage players to respond to calls for help 

After pseudo-pilot test data, we defined the functions of our chatbot. We planned to increase players’ sense of being a team by adding functions as “introduction and reminder before game” and mediating “When somebody insults you/team”. We decided to provide extra information as “Tower/Inhibitor/Base under attack” and “more information beyond pin”. The full function list here. 

![](https://lh4.googleusercontent.com/jC09TtJXmxeEk9c22qmt_YY9kpNJKya8TW1S5EuXA0RC9kDdIRoC7sueu1UqH0WkXMLEB8l0Taqjj2IrHpkDce4bNuJLq7MxJZiD6cg2al-h_tEmGFLlZ-8_7XNLXgTwBvqfBMYg)




> **Objective 3:** Evaluate the usability of chatbot

![](https://lh5.googleusercontent.com/N6Sl7_q3K0SielA8X4kOJ3vk6_BEm65na0xri-EXKAuhMYjPAkaFa1dbPQKu9PIZWsH_Up6K8hkR33ydnCadKPIqtkuqHSDgLMnyUNXR04Q4hAXGWZb8lTCA835D1kOgr_3grcmx)

The above chart showed players generally saw improvements in every measured category, with players’ self-measurement and teammate-measurement of teamwork showing the greatest improvements. 

The chatbot also appeared to facilitate a greater sense of coordination among players, make it easier for them to get help from teammates, increase their perceptions of speedy responses from teammates, and improve their awareness of teammates’ expectations.

![](https://lh3.googleusercontent.com/w_0Pg5ij_T3-HYDx1bA12TDDTSMMh4uq0unU7hjRHryWYO2HRnZ5VWABSp-tWiM3r_oSo4NipL1m3g5Czn8K5j9mon33NOw6bwEqVjVQ26wqDysockbML3-nUe78K1M2mZJgRL9h)

Players appreciated the chatbot to some extent on every measured scale. Participants strongly indicated that they enjoyed the chatbot’s personality, appreciated the chatbot asking others to help them, felt that the chatbot made them feel like part of the team, and believed the chatbot helped them coordinate. Since these were the primary functions that the chatbot was meant to fulfill, we can say that it was, in these trials at least, a success.

</br>
</br>

## Key Takeaways 

### The Positives😀:

- **Did the chatbot help players collaborate better?** </br>
**Yes.** The chatbot alleviated the burden of both direct and indirect collaboration.  

- **Was the chatbot intrusive to their gaming experience?**</br>
**No.** The chatbot reminded players to help/coordinate with their teammates, but it was easy for players to ignore messages if they wanted to.

- **Was the Wizard of Oz Study successful?**</br> 
**Yes.** One player asked me how we made the bot work so seamlessly.

-**Did players like our chatbot?**
- **Yes.** Players especially appreciated the chatbot’s personality, functions, and encouragement.

### The negatives🙁: 

- One player briefly mistook the chatbot for another player. 

- One player was distracted by the chat box and did not pay enough attention to the gameplay.

- One player stated that the chatbot would work really well for entry-level players but wasn’t as helpful for more experienced players.

</br>
</br>

## Conclusion

In this project, we explored the use of a chatbot in League of Legends and its influence on in-game team collaboration. At the initial stage of the project, we studied players’ issues and needs using interviews, focus groups, and surveys. We then built a prototype based on our research results and verified it through two rounds of Wizard of Oz user tests. Finally, we evaluated the chatbot’s performance using surveys and interviews following players’ interaction with the chatbot during gameplay. 

Players found the chatbot useful and said it improved their collaborations with teammates while maintaining the fairness of the game. We used players’ self-reported perceptions of teamwork as our measurement. However, similar studies on team collaboration may want to also include more objective measurements for cross validation. 
