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
.wide-img{width:100%;border-radius:12px;display:block;margin:1.2rem 0 0}
.readers{margin:1.6rem 0 2rem}
.readers [role=tablist]{display:flex;flex-wrap:wrap;gap:.5rem;margin:.6rem 0 1rem}
.readers [role=tab]{font:inherit;font-size:.95rem;padding:.35rem .95rem;border-radius:999px;border:1px solid var(--global-divider-color);background:transparent;color:var(--global-text-color);cursor:pointer;transition:background-color .2s,color .2s,border-color .2s}
.readers [role=tab][aria-selected=true]{background:var(--global-theme-color);border-color:var(--global-theme-color);color:var(--global-bg-color)}
.readers [role=tabpanel]{border-left:2px solid var(--global-theme-color);padding-left:1rem;animation:readerin .35s ease}
.readers [role=tabpanel] p:last-child{margin-bottom:0}
@keyframes readerin{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:none}}
@media (prefers-reduced-motion:reduce){.readers [role=tabpanel]{animation:none}}
.area{display:grid;grid-template-columns:13rem 1fr;gap:.2rem 1.2rem;padding:.8rem 0;border-top:1px solid var(--global-divider-color)}
.area:last-of-type{border-bottom:1px solid var(--global-divider-color)}
.area b{font-weight:500}
.area p{margin:0}
.area .ref{font-size:.85rem;margin-top:.3rem}
@media (max-width:576px){.area{grid-template-columns:1fr}}
</style>

_Prodigy in an infant state on career progression path._

I am an engineer and researcher at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences, Germany. I work on the safety and security of artificial intelligence (AI) in automated driving.

<div class="readers">
<p id="readers-label">Select the description of my work that fits you:</p>
<div role="tablist" aria-labelledby="readers-label">
<button role="tab" id="t-general" aria-controls="p-general" aria-selected="true">General reader</button>
<button role="tab" id="t-industry" aria-controls="p-industry" aria-selected="false" tabindex="-1">Industry or funding body</button>
<button role="tab" id="t-researcher" aria-controls="p-researcher" aria-selected="false" tabindex="-1">Researcher</button>
<button role="tab" id="t-teaching" aria-controls="p-teaching" aria-selected="false" tabindex="-1">Student or teacher</button>
</div>
<div role="tabpanel" id="p-general" aria-labelledby="t-general">
<p>Some vehicles can drive parts of a journey without the driver. For this, software has to recognise people, other vehicles and the road from sensor data. This software uses AI and can make errors, for example in heavy rain or when someone manipulates a sensor.</p>
<p>I study how engineers can find such errors before the vehicle is on the road, and how they can demonstrate to an independent assessor that the remaining risk is acceptable.</p>
</div>
<div role="tabpanel" id="p-industry" aria-labelledby="t-industry" hidden>
<p>Before release, a manufacturer or supplier has to show that an automated driving function meets the standards for functional safety, safety of the intended functionality, cybersecurity and AI.</p>
<p>I develop methods that produce this evidence: simulation-based tests, performance measurements for AI-based perception, and assurance cases that combine safety and cybersecurity. I am open to industry exchange and joint research projects.</p>
</div>
<div role="tabpanel" id="p-researcher" aria-labelledby="t-researcher" hidden>
<p>My research addresses the assurance of AI-based perception components with respect to ISO 26262, ISO 21448, ISO/SAE 21434 and ISO/PAS 8800. Current topics are uncertainty evaluation for LiDAR object detection, assurance argument patterns that integrate cybersecurity claims, and assurance in operation. Earlier work covers reasonably foreseeable misuse by the driver and trajectory planning.</p>
<p>The <a href="{{ '/publications/' | relative_url }}">publications</a> link to their code where code exists.</p>
</div>
<div role="tabpanel" id="p-teaching" aria-labelledby="t-teaching" hidden>
<p>I supervise bachelor's and master's theses and internships on automated driving, AI-based perception and safety.</p>
<p>I also develop teaching material in which learners run an object detector, observe where it fails and derive the engineering response. The <a href="{{ '/projects/' | relative_url }}">projects</a> page links a school workshop and two interactive explanations.</p>
</div>
</div>

## Areas of work

<div class="area"><b>Performance of AI-based perception</b><div><p>Measurement of how well object detection performs under adverse weather, with sensor data generated in simulation, and evaluation of the uncertainty of each detection.</p><p class="ref"><a href="https://doi.org/10.5220/0014967200004030">Uncertainty evaluation</a> · <a href="https://doi.org/10.1007/978-3-032-23187-1_10">uncertainty representation</a> · <a href="https://doi.org/10.5220/0012707300003702">performance evaluation</a></p></div></div>
<div class="area"><b>Safety and cybersecurity assurance</b><div><p>An assurance case is a structured argument, supported by evidence, that a system is acceptably safe. I work on assurance cases that contain safety claims and cybersecurity claims, at release and in operation.</p><p class="ref"><a href="https://doi.org/10.1007/978-3-032-35506-5_55">Assurance argument pattern</a> · <a href="{{ '/projects/' | relative_url }}">assurance case explorer</a></p></div></div>
<div class="area"><b>Driver and automation</b><div><p>Simulation-based testing of reasonably foreseeable misuse of automated driving functions by the driver, and evaluation of countermeasures.</p><p class="ref"><a href="https://doi.org/10.1007/978-981-99-3043-2_15">Testing of foreseeable misuse</a> · <a href="https://doi.org/10.47953/sae-pp-00371">mitigation of foreseeable misuse</a></p></div></div>
<div class="area"><b>Scenario-based testing</b><div><p>Definition of driving scenarios and trajectory planning for the verification and validation of automated driving functions in simulation.</p><p class="ref"><a href="https://doi.org/10.1109/ICECCME52200.2021.9591044">Trajectory planning</a> · <a href="https://doi.org/10.1109/hora52670.2021.9461313">transverse guidance</a></p></div></div>
<div class="area"><b>State of research</b><div><p>A systematic literature review of the safety of the intended functionality (SOTIF) for automated driving systems.</p><p class="ref"><a href="https://doi.org/10.4271/2025-01-5030">Systematic literature review</a></p></div></div>
<div class="area"><b>Education</b><div><p>Thesis supervision, workshops for students from European partner universities in the Erasmus+ programme, and teaching material from school level to engineering practice.</p><p class="ref"><a href="{{ '/projects/' | relative_url }}">Projects and teaching material</a></p></div></div>

<img class="wide-img" src="{{ '/assets/img/lifecycle.svg' | relative_url }}" alt="The safety lifecycle of an AI component: concept and requirements, data and design, verification and validation, release, operation, and updates.">

## Background

I have been a Research Associate at IFM since 2021 and am a PhD candidate. I hold a B.Tech. in Instrumentation and Control Engineering (India) and an M.Sc. in Smart Systems (Germany). Before research, I developed a supervisory control and data acquisition (SCADA) system for quality checks in the machine tool industry. I review manuscripts for scientific journals and conferences. The [CV]({{ '/cv/' | relative_url }}) gives the details.

<script>
(function(){
  var tabs=[].slice.call(document.querySelectorAll('.readers [role=tab]'));
  function show(t,focus){tabs.forEach(function(x){var on=x===t;x.setAttribute('aria-selected',on);x.tabIndex=on?0:-1;document.getElementById(x.getAttribute('aria-controls')).hidden=!on;});if(focus)t.focus();}
  tabs.forEach(function(t,i){
    t.addEventListener('click',function(){show(t);});
    t.addEventListener('keydown',function(e){
      if(e.key==='ArrowRight'){e.preventDefault();show(tabs[(i+1)%tabs.length],true);}
      if(e.key==='ArrowLeft'){e.preventDefault();show(tabs[(i-1+tabs.length)%tabs.length],true);}
    });
  });
})();
</script>
