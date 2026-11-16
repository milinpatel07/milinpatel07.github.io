---
layout: about
title: about
permalink: /
subtitle:

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: false
  limit: 5

latest_posts:
  enabled: false
---

<style>.post-header{display:none}.hero-img{width:100%;border-radius:12px;display:block;margin:0 0 1.5rem}</style>

<img class="hero-img" src="{{ '/assets/img/hero.svg' | relative_url }}" alt="Milin Patel. Safety and security of AI-based perception. An animated LiDAR scene shows a runtime monitor reacting as a pedestrian detection becomes uncertain.">

**Research Associate & PhD Candidate \| Safety, Cybersecurity & AI for Automated Driving**<br>
_Prodigy in an infant state on career progression path._

Automated driving systems depend on AI-based perception to detect pedestrians, vehicles and the road layout. These AI components learn their behaviour from data instead of following a written specification, so the established methods of safety engineering cover them only in part. My research addresses this gap.

Since 2021, I have worked as a Research Associate at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences, where I am also a PhD candidate. My approach is simulation-based testing. I use existing models or develop new ones (driver behaviour models, machine learning models for object detection, sensor models) and define safety-relevant driving scenarios. From the results, I build safety and security arguments with respect to the ISO standards: how safe is safe enough, what the functional insufficiencies of the automated driving system are, and where its performance limitations lie.

I came to this field through control engineering. I studied Instrumentation and Control Engineering in India and Smart Systems in Germany. In my first industry role, in the machine tool industry, I developed a supervisory control and data acquisition (SCADA) monitoring system for quality checks. My master's thesis at Kempten investigated scenario-based verification and validation of highly automated lane-keeping functions. It resulted in two publications and led to my current position.

I supervise master's and bachelor's theses and internships, and I review for journals and conferences. Through the Erasmus+ programme, I conducted workshops for students from different European countries.

## Research

The research follows the lifecycle of an AI component, with one guiding question for each stage:

| | Guiding question |
| :-- | :-- |
| **Before release** | Is the performance of the AI-based perception sufficient, including under adverse conditions? |
| **At release** | Do the safety and cybersecurity claims combine into one consistent assurance case? |
| **After release** | Does the evidence remain valid in operation and after each update of the AI component? |

The work brings together functional safety (ISO 26262), safety of the intended functionality (SOTIF, ISO 21448), cybersecurity (ISO/SAE 21434) and AI safety (ISO/PAS 8800), and turns their requirements into evidence that engineers can produce and assessors can check.

<img class="hero-img" src="{{ '/assets/img/lifecycle.svg' | relative_url }}" alt="The safety lifecycle of an AI component: concept and requirements, data and design, verification and validation, release, operation, and updates.">
