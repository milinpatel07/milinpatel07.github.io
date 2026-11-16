---
layout: about
title: about
permalink: /
subtitle: Research Associate & PhD Candidate | Safety, Cybersecurity & AI for Automated Driving

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
.wide-img{width:100%;border-radius:12px;display:block;margin:1.2rem 0 2rem}
.areas{display:grid;grid-template-columns:1fr 1fr;gap:1.1rem}
.area{border-top:2px solid var(--global-theme-color);padding:.8rem 0 .2rem;transition:transform .25s ease}
.area:hover{transform:translateY(-3px)}
.area h3{font-size:1.05rem;font-weight:500;margin:0 0 .35rem}
.area p{margin:0 0 .45rem;font-size:.97rem}
.area .res{border-left:2px solid var(--global-divider-color);padding-left:.7rem}
.area .ref{font-size:.85rem}
.areas.reveal .area{opacity:0;transform:translateY(12px);transition:opacity .5s ease,transform .5s ease}
.areas.reveal .area.in{opacity:1;transform:none}
.social .contact-icons a i,.social .contact-icons a svg{font-size:1.9rem}
@media (max-width:700px){.areas{grid-template-columns:1fr}}
@media (prefers-reduced-motion:reduce){.areas.reveal .area{opacity:1;transform:none;transition:none}.area:hover{transform:none}}
</style>


_Prodigy in an infant state on career progression path._

I am an engineer and researcher at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences, Germany. I work on the safety and cybersecurity of artificial intelligence (AI) in automated driving.

Some vehicles can drive parts of a journey without the driver. For this, software has to recognise people, other vehicles and the road from sensor data. This software uses AI and can make errors, for example in heavy rain or when someone manipulates a sensor.

I develop methods to find such errors, before the release of a vehicle and during its operation, and to demonstrate to an independent assessor that the remaining risk is acceptable. The methods are simulation-based tests, performance measurements for AI-based perception, and assurance cases that combine safety and cybersecurity.

<p>The figure shows the lifecycle of an AI component, from concept to updates. My areas of work, listed below it, address its phases.</p>

<img class="wide-img" src="{{ '/assets/img/lifecycle.svg' | relative_url }}" alt="The safety lifecycle of an AI component: concept and requirements, data and design, verification and validation, release, operation, and updates.">

## Areas of work

<div class="areas" id="areas">
<div class="area"><h3>Performance of AI-based perception</h3><p>I measure how well object detection performs in adverse weather, with LiDAR (laser-based distance sensor) data generated in simulation, and I evaluate the uncertainty of each detection.</p><p class="res">Result: a simulated LiDAR dataset with 21 weather conditions, and an evaluation in which disagreement between several detectors separates incorrect detections from correct ones.</p><p class="ref"><a href="https://doi.org/10.5220/0014967200004030">Uncertainty evaluation</a> · <a href="https://doi.org/10.1007/978-3-032-23187-1_10">uncertainty representation</a> · <a href="https://doi.org/10.5220/0012707300003702">performance evaluation</a></p></div>
<div class="area"><h3>Safety and cybersecurity assurance</h3><p>An assurance case is a structured argument, supported by evidence, that a system is acceptably safe. I combine the safety claims and the cybersecurity claims for an AI-based perception component in one assurance case.</p><p class="res">Result: at the verification and validation goal, the evidence types of the standards use different measurement scales, and no standard prescribes how they combine.</p><p class="ref"><a href="https://doi.org/10.1007/978-3-032-35506-5_55">Assurance argument pattern</a> · <a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/">assurance case explorer</a></p></div>
<div class="area"><h3>Driver and automation</h3><p>I test reasonably foreseeable misuse of automated driving functions by the driver in simulation.</p><p class="res">Result: test requirements, evaluation criteria, and a procedure to evaluate measures that prevent or mitigate misuse.</p><p class="ref"><a href="https://doi.org/10.1007/978-981-99-3043-2_15">Testing of foreseeable misuse</a> · <a href="https://doi.org/10.47953/sae-pp-00371">mitigation of foreseeable misuse</a></p></div>
<div class="area"><h3>Scenario-based testing</h3><p>I define driving scenarios and plan trajectories for the verification and validation of automated driving functions in simulation.</p><p class="res">Result: a lane change trajectory planned with a high-order polynomial, analysed in simulation, with a public Simulink model.</p><p class="ref"><a href="https://doi.org/10.1109/ICECCME52200.2021.9591044">Trajectory planning</a> · <a href="https://doi.org/10.1109/hora52670.2021.9461313">transverse guidance</a> · <a href="https://github.com/milinpatel07/TGAS-Sim">model</a></p></div>
<div class="area"><h3>Literature review</h3><p>I reviewed the published research on the safety of the intended functionality (SOTIF), which covers hazards that arise without a fault.</p><p class="res">Result: the research gaps and a comparison of the methods that support SOTIF.</p><p class="ref"><a href="https://doi.org/10.4271/2025-01-5030">Systematic literature review</a></p></div>
<div class="area"><h3>Education</h3><p>I supervise bachelor's and master's theses and conduct workshops for students from European countries in the Erasmus+ programme.</p><p class="res">Result: a public school workshop on AI-based perception and two interactive explanations of my research.</p><p class="ref"><a href="{{ '/projects/' | relative_url }}">Projects and teaching material</a></p></div>
</div>

## Background

I have been a Research Associate at IFM since 2021 and am a PhD candidate. I hold a B.Tech. in Instrumentation and Control Engineering (India) and an M.Sc. in Smart Systems (Germany). Before research, I developed a supervisory control and data acquisition (SCADA) system for quality checks in the machine tool industry. I review manuscripts for scientific journals and conferences. The [CV]({{ '/cv/' | relative_url }}) gives the details.

<script>
(function(){
  var box=document.getElementById('areas'); if(!box||!('IntersectionObserver' in window)) return;
  if(window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
  box.classList.add('reveal');
  var items=[].slice.call(box.children);
  new IntersectionObserver(function(es,o){es.forEach(function(e){ if(e.isIntersecting){ items.forEach(function(el,i){ setTimeout(function(){el.classList.add('in');}, i*70); }); o.disconnect(); } });},{threshold:.08}).observe(box);
})();
</script>
