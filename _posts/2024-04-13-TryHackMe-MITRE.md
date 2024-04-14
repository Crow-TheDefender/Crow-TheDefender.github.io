---
title: "TryHackMe - MITRE"
date: 2024-04-13
categories:
  - blog
tags:
  - TryHackMe
  - MITRE
#header:
#  image: /assets/images/bio-photo.jpg
#  caption: "Photo credit: [Designed by Freepik](http://www.freepik.com)"

---

I have been paying for a [TryHackMe](https://tryhackme.com/) subscription for over a year and have yet to start a room, mostly because I have been struggling to motivate myself to study between work and my personal life. I'm hoping this blog will change that as I used to really enjoy studying and learning... anyway I digress.

Today I thought I would start with an easy one, the [MITRE Room](https://tryhackme.com/r/room/mitre).

## Brief Intro to MITRE Room

In this room, they focus on projects/research that the US-based non-profit MITRE Corporation has created for the cybersecurity community, specifically:

* ATT&CK® (Adversarial Tactics, Techniques, and Common Knowledge) Framework
* CAR (Cyber Analytics Repository) Knowledge Base
* ENGAGE
* D3FEND (Detection, Denial, and Disruption Framework Empowering Network Defense)
* AEP (ATT&CK Emulation Plans)

### Brief Intro to MITRE ATT&CK®
[MITRE ATT&CK®](https://attack.mitre.org/) is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations. It is used to record and document common TTPs (Tactics, Techniques, and Procedures) that APT (Advanced Persistent Threat) groups used against enterprise networks. It covers the seven-stages of the Cyber Attack Lifecycle.

* The Tactic is the adversary's goal or objective.
* The Technique is how the adversary achieves the goal or objective.
* The Procedure is how the technique is executed.

The [MITRE ATT&CK®](https://attack.mitre.org/) is something I use regularly, especially if I am working on threat intelligence.

### Brief Intro to CAR (Cyber Analytics Repository)

The [MITRE Cyber Analytics Repository (CAR)](https://car.mitre.org/) is a knowledge base of analytics developed by MITRE based on the MITRE ATT&CK® adversary model. CAR defines a data model that is leveraged in its pseudocode representations but also includes implementations directly targeted at specific tools (e.g., Splunk, EQL) in its analytics. With respect to coverage, CAR is focused on providing a set of validated and well-explained analytics, in particular with regards to their operating theory and rationale.

The [MITRE Cyber Analytics Repository](https://car.mitre.org/) isn't something I have had alot of exposure to, but something I'm going to spend some more time getting acquainted with.

### Brief Intro to ENGAGE

[MITRE Engage](https://engage.mitre.org/starter-kit/) is a framework for planning and discussing adversary engagement operations, it is considered an "Adversary Engagement Approach". 
 [Engage matrix](https://engage.mitre.org/matrix/) is made up of a few different parts:
* Prepare the set of operational actions that will lead to your desired outcome (input)
* Expose adversaries when they trigger your deployed deception activities 
* Affect adversaries by performing actions that will have a negative impact on their operations
* Elicit information by observing the adversary and learn more about their modus operandi (TTPs)
* Understand the outcomes of the operational actions (output) 

I have never used [MITRE Engage](https://engage.mitre.org/starter-kit/) and have been the hardest questions to answer so far.

### Brief Intro to D3FEND

[D3FEND](https://d3fend.mitre.org/) stands for Detection, Denial, and Disruption Framework Empowering Network Defense and is a knowledge graph of cybersecurity countermeasures that is still in beta.

I have never used [D3FEND](https://d3fend.mitre.org/) but was easy enough to understand and work with.

### Brief Intro to ATT&CK® Emulation Plans

Included in this is:
* [Center of Threat-Informed Defense (CTID)](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/)
* [The Adversary Emulation Library](https://medium.com/mitre-engenuity/introducing-the-all-new-adversary-emulation-plan-library-234b1d543f6b)
* [ATT&CK® Emulation Plans](https://github.com/center-for-threat-informed-defense/adversary_emulation_library)

The [Center of Threat-Informed Defense (CTID)](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/) consists of various companies and vendors from around the globe. Their objective is to conduct research on cyber threats and their TTPs and share this research to improve cyber defense for all. 

[The Adversary Emulation Library](https://medium.com/mitre-engenuity/introducing-the-all-new-adversary-emulation-plan-library-234b1d543f6b) & [ATT&CK® Emulation Plans](https://github.com/center-for-threat-informed-defense/adversary_emulation_library) is a public library making adversary emulation plans a free resource for blue/red teamers. The library and the emulations are a contribution from CTID.

### TryHackMe - MITRE Room

This room is broken down into 9 tasks, but only 6 of these tasks require you to answer questions.

After providing details relating to a specific framework (task), it will ask you to answer some questions which will require you to navigate through the various frameworks mentioned above. An example of the formatting can be seen below.

![MITRE Question Example](/assets/images/Blog Images/THM-MITRE.png)

## Conclusion

I selected this room because I thought it would be an easy one, and while it wasn't technical in the slightest it was quiet informative. I found out there are multiple frameworks that I need to get more exposure to.