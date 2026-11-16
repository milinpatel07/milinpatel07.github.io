---
layout: about
title: about
permalink: /
subtitle:

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: false
  limit: 5

latest_posts:
  enabled: false
---

<style>
.post-header{display:none}
.hero-img{width:100%;border-radius:12px;display:block}
.hero-cap{font-size:.9rem;opacity:.75;margin:.6rem 0 1.6rem}
.stage{display:grid;grid-template-columns:9rem 1fr;gap:.2rem 1.2rem;padding:.9rem 0;border-top:1px solid var(--global-divider-color)}
.stage:last-of-type{border-bottom:1px solid var(--global-divider-color)}
.stage b{font-weight:500}
.stage p{margin:0}
.stage .q{font-weight:500;margin-bottom:.3rem}
.stage .ref{font-size:.85rem;opacity:.7;margin-top:.3rem}
.keypub{margin:0 0 1.1rem}
.keypub .meta{font-size:.85rem;opacity:.7}
@media (max-width:576px){.stage{grid-template-columns:1fr}}
</style>

<img class="hero-img" src="{{ '/assets/img/hero.svg' | relative_url }}" alt="Animated LiDAR scene. A vehicle's AI detects a pedestrian; when the detection becomes uncertain, a runtime monitor switches from nominal to degraded.">
<p class="hero-cap">The animation shows the problem I work on. The vehicle's AI detects a pedestrian. When that detection becomes uncertain, a runtime monitor reports that the system is no longer operating as intended.</p>

**Research Associate & PhD Candidate \| Safety, Cybersecurity & AI for Automated Driving**<br>
_Prodigy in an infant state on career progression path._

A vehicle that drives itself has to recognise people, other vehicles and the road. It does this with AI models trained on recorded data. Nobody writes down in advance how such a model must behave, so engineers cannot check it line by line against a specification. The standards for vehicle safety assume exactly that kind of check. My research works out how to show that an AI-based perception system is safe and secure enough to be released, and that it stays so on the road.

I work at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences in Germany, as a Research Associate since 2021 and as a PhD candidate. I came to this field through control engineering: a degree in Instrumentation and Control Engineering in India, a first job building a monitoring system for quality checks in the machine tool industry, and a Master's in Smart Systems in Germany. My master's thesis on testing automated lane-keeping in simulation brought me to Kempten.

## Research

I test AI-based perception in simulation, under conditions that are rare or dangerous to recreate on a real road, and I turn the results into evidence that a safety assessor can check. The work follows a vehicle's AI from development to operation.

<div class="stage"><b>Before release</b><div><p class="q">Does the AI still detect pedestrians in rain, fog or darkness?</p><p>I build simulated sensor data for such conditions and measure how uncertain the AI is about each detection. Where several AI models disagree, the detection is likely wrong.</p><p class="ref">VEHITS 2024 and 2026, Springer 2026</p></div></div>
<div class="stage"><b>At release</b><div><p class="q">Can one argument show that the system is both safe and secure?</p><p>Heavy rain and a sensor attack can hide the same pedestrian. Safety standards cover the rain and security standards cover the attack, but neither assigns the failure that both can cause. I build one argument that covers both and shows where the gaps remain.</p><p class="ref">SAFECOMP 2026</p></div></div>
<div class="stage"><b>After release</b><div><p class="q">Does the evidence still hold on the road and after each software update?</p><p>On the road, the vehicle sees a sudden drop in detection quality but not its cause. Runtime monitoring, as in the animation above, is one part of the answer.</p><p class="ref">SAFECOMP 2026, position paper</p></div></div>

The questions sit between four ISO standards: ISO 26262 for faults in hardware and software, ISO 21448 for hazards that arise without any fault (also called SOTIF), ISO/SAE 21434 for cybersecurity, and ISO/PAS 8800 for AI in road vehicles.

## Key publications

<div class="keypub"><a href="https://doi.org/10.1007/978-3-032-35506-5_55">Integrating Cybersecurity Into the AI Safety Assurance Argument</a><br>One argument for the safety and the security of an AI-based LiDAR detector, and the failures that no standard assigns to either side.<br><span class="meta">SAFECOMP 2026 Workshops (WAISE), Springer · <a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">code</a></span></div>
<div class="keypub"><a href="https://doi.org/10.5220/0014967200004030">Uncertainty Evaluation to Support Safety of the Intended Functionality Analysis</a><br>Uses the disagreement between several detectors to find detections that are likely wrong, and the weather conditions that cause them.<br><span class="meta">VEHITS 2026 · <a href="https://github.com/milinpatel07/SOTIF_Uncertainty_Evaluation_Lidar_Object_Detection">code</a></span></div>
<div class="keypub"><a href="https://doi.org/10.4271/2025-01-5030">A Systematic Literature Review on Safety of the Intended Functionality for Automated Driving Systems</a><br>What published research says about hazards that arise without any fault, and where it leaves gaps.<br><span class="meta">SAE Technical Paper, 2025, open access</span></div>

[All publications](/publications/)
