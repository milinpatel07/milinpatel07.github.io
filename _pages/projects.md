---
layout: page
permalink: /projects/
title: projects
description: Interactive explanations, teaching material and research tools.
nav: true
nav_order: 2
---

<style>.proj-img{width:100%;border-radius:12px;display:block;margin:0 0 2rem}.proj{margin:0 0 1.8rem}.proj h3{margin-bottom:.2rem}.proj .tags{font-size:.85rem;opacity:.75}</style>

<img class="proj-img" src="{{ '/assets/img/focus.svg' | relative_url }}" alt="Research areas: perception safety, safety and security, uncertainty, education.">

<div class="proj">
<h3>Walk through a safety argument</h3>
<p>An assurance case is a structured argument, backed by evidence, that a system is safe enough to use. This interactive website presents one for an AI-based perception component, claim by claim, with both safety and cybersecurity claims and the standard behind each one.</p>
<p><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/">Explore the assurance case</a> · <a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">Code</a></p>
<p class="tags">assurance cases · GSN · Python</p>
</div>

<div class="proj">
<h3>Does it still work in rain?</h3>
<p>An AI detector may meet its required accuracy in clear weather and miss it in heavy rain, without any fault. Safety engineers call such a condition a triggering condition. This page explains, without formulas, a statistical test that checks whether the required accuracy still holds under such a condition.</p>
<p><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html">Read the explanation</a> · <a href="https://github.com/milinpatel07/lidar-performance-target-applicability">Code</a></p>
<p class="tags">SOTIF · LiDAR · statistics</p>
</div>

<div class="proj">
<h3>How does a vehicle perceive?</h3>
<p>A school workshop in German. Pupils observe an object detector in a street scene, then see it miss pedestrians in fog and fail under a manipulated image. No programming required.</p>
<p><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall">Open the workshop</a></p>
<p class="tags">outreach · Jupyter · Colab</p>
</div>

<div class="proj">
<h3>Questions to your own documents</h3>
<p>A research tool that answers questions from uploaded documents, with page references and the exact source passages, so every answer can be checked.</p>
<p><a href="https://github.com/milinpatel07/doc-chat">View the tool</a></p>
<p class="tags">retrieval-augmented generation · Streamlit</p>
</div>

## Teaching material

Learners run a real object detector, observe where it fails, and work out the engineering response. The same idea carries from school to engineering practice:

- **School:** How does a vehicle perceive its surroundings?
- **University:** Why does AI-based perception fail?
- **Engineering practice:** How is sufficient safety demonstrated?
