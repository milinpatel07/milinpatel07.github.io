---
layout: page
permalink: /projects/
title: projects
description: Interactive explanations, teaching material and research tools.
nav: true
nav_order: 2
---

<style>
.proj{margin:0 0 2.4rem}
.proj h3{margin-bottom:.4rem}
.proj-shot{display:block;border:1px solid var(--global-divider-color);border-radius:10px;overflow:hidden;margin:0 0 .9rem;transition:transform .25s ease,border-color .25s ease}
.proj-shot:hover{transform:translateY(-3px);border-color:var(--global-theme-color)}
.proj-shot img{width:100%;display:block;height:300px;object-fit:cover;object-position:top}
@media (prefers-reduced-motion:reduce){.proj-shot:hover{transform:none}}
</style>

<div class="proj">
<a class="proj-shot" href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"><img src="{{ '/assets/img/project-assurance.png' | relative_url }}" alt="Start page of the assurance case explorer."></a>
<h3>Assurance case explorer</h3>
<p>An assurance case is a structured argument, supported by evidence, that a system is acceptably safe for a defined use. This website presents an assurance case for an AI-based perception component. The case contains safety claims and cybersecurity claims, and each claim names the clause of the standard it derives from.</p>
<p><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/">Open the assurance case</a> · <a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">Code</a></p>
</div>

<div class="proj">
<a class="proj-shot" href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><img src="{{ '/assets/img/project-rain.png' | relative_url }}" alt="First scene of the explanation: a detector reports right and wrong detections."></a>
<h3>Applicability of a performance target under a triggering condition</h3>
<p>ISO 21448 defines a triggering condition as a condition of a scenario that initiates hazardous behaviour without a fault. Heavy rain is an example for LiDAR-based perception. This project tests whether an uncertainty threshold of a perception model, selected under one condition, still meets its performance target under a triggering condition. The linked page explains the statistical test without formulas.</p>
<p><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html">Read the explanation</a> · <a href="https://github.com/milinpatel07/lidar-performance-target-applicability">Code</a></p>
</div>

<div class="proj">
<h3>School workshop on AI-based perception (in German)</h3>
<p>Pupils run an object detector on a street scene. They then observe that it misses pedestrians in fog and fails on a manipulated image. The workshop requires no programming.</p>
<p><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall">Open the workshop</a></p>
</div>

<div class="proj">
<h3>Document question answering with source references</h3>
<p>A research tool that answers questions from uploaded documents only. Each answer gives the page reference and the source passage, so a reader can check it.</p>
<p><a href="https://github.com/milinpatel07/doc-chat">View the tool</a></p>
</div>

## Teaching material

Learners run an object detector, observe where it fails, and derive the engineering response. The material addresses a different question at each level:

- **School:** How does a vehicle perceive its surroundings?
- **University:** Why does AI-based perception fail?
- **Engineering practice:** How is sufficient safety demonstrated?
