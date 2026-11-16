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
.hero-img{width:100%;border-radius:12px;display:block;margin:0 0 1.6rem}
.stage{display:grid;grid-template-columns:11rem 1fr;gap:.2rem 1.2rem;padding:.9rem 0;border-top:1px solid var(--global-divider-color)}
.stage:last-of-type{border-bottom:1px solid var(--global-divider-color)}
.stage b{font-weight:500}
.stage p{margin:0}
.stage .q{font-weight:500;margin-bottom:.3rem}
.stage .ref{font-size:.85rem;margin-top:.4rem}
@media (max-width:576px){.stage{grid-template-columns:1fr}}
</style>

<img class="hero-img" src="{{ '/assets/img/hero.svg' | relative_url }}" alt="Animated LiDAR scene. The perception of the ego vehicle detects a pedestrian. When the detection becomes uncertain, a runtime monitor changes its state from nominal to degraded.">

**Research Associate & PhD Candidate \| Safety, Cybersecurity & AI for Automated Driving**<br>
_Prodigy in an infant state on career progression path._

An automated driving system uses AI-based perception to detect pedestrians, vehicles and lane markings from sensor data. A perception model learns its behaviour from training data. A written specification does not define that behaviour. Safety standards for road vehicles verify a system against its specification, so they cover an AI-based perception component only in part. I develop methods that produce the evidence for the uncovered part: measurements of perception performance under adverse conditions, and an assurance case (a structured argument, supported by evidence, that a system is acceptably safe) that combines safety claims and cybersecurity claims.

I am a Research Associate (since 2021) and PhD candidate at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences, Germany. I hold a B.Tech. in Instrumentation and Control Engineering and an M.Sc. in Smart Systems. Before research, I developed a supervisory control and data acquisition (SCADA) system for quality checks in the machine tool industry. My master's thesis addressed scenario-based verification and validation of highly automated lane keeping.

## Research

The research follows an AI-based perception component through the phases of its lifecycle. Each phase poses a question about the evidence for safety and cybersecurity.

<div class="stage"><b>Development and testing</b><div><p class="q">Does the perception model meet its performance target under adverse weather conditions?</p><p>I generate LiDAR point cloud data in simulation for defined weather conditions. An ensemble of object detection models then evaluates the uncertainty of each detection. Disagreement between the models of the ensemble separates incorrect detections from correct ones and identifies the weather conditions that cause them.</p><p class="ref">Publications: <a href="https://doi.org/10.5220/0014967200004030">uncertainty evaluation</a>, <a href="https://doi.org/10.1007/978-3-032-23187-1_10">uncertainty representation</a>, <a href="https://doi.org/10.5220/0012707300003702">performance evaluation in simulation</a></p></div></div>
<div class="stage"><b>Release for use on public roads</b><div><p class="q">Do the safety claims and the cybersecurity claims form a consistent assurance case?</p><p>Reduced LiDAR point density on an object can result from heavy rain or from a spoofing attack. ISO 21448 treats the rain as a triggering condition and excludes attacks. ISO/SAE 21434 treats the attack as a threat scenario and does not reference ISO 21448. Neither standard allocates a failure that both causes can produce. I extend the assurance argument pattern of ISO/PAS 8800 with the claims of the other standards and identify where this allocation is missing.</p><p class="ref">Publication: <a href="https://doi.org/10.1007/978-3-032-35506-5_55">assurance argument pattern</a> (<a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">code</a>)</p></div></div>
<div class="stage"><b>Operation and updates</b><div><p class="q">Does the evidence remain valid in operation and after an update of the perception model?</p><p>In operation, no ground truth is available. An anomaly in the perception output reaches the vehicle without a label for its cause, which can be a performance insufficiency (ISO 21448) or an attack (ISO/SAE 21434). My position paper states this gap at the level of the clauses of the standards and sets requirements for a method that resolves it.</p><p class="ref">Publication: position paper at SAFECOMP 2026, listed under <a href="{{ '/publications/' | relative_url }}">publications</a></p></div></div>

The work refers to ISO 26262 (functional safety), ISO 21448 (safety of the intended functionality, SOTIF), ISO/SAE 21434 (cybersecurity engineering) and ISO/PAS 8800 (safety and artificial intelligence).
