---
layout: page
permalink: /projects/
title: portfolio
description: Research, teaching, engineering projects, industry work and tools. Select a field.
nav: true
nav_order: 2
---

<style>
.pf-chips{display:flex;flex-wrap:wrap;gap:.5rem;margin:0 0 1.6rem}
.pf-chips button{font:inherit;font-size:.9rem;padding:.3rem .9rem;border-radius:999px;border:1px solid var(--global-divider-color);background:transparent;color:var(--global-text-color);cursor:pointer;transition:background-color .2s,color .2s,border-color .2s}
.pf-chips button:hover{border-color:var(--global-theme-color)}
.pf-chips button[aria-pressed=true]{background:var(--global-theme-color);border-color:var(--global-theme-color);color:var(--global-bg-color)}
.pf-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:1rem}
.pf-card{border:1px solid var(--global-divider-color);border-top:2px solid var(--global-theme-color);border-radius:0 0 10px 10px;padding:.9rem 1rem;transition:transform .25s ease,box-shadow .25s ease}
.pf-card:hover{transform:translateY(-3px);box-shadow:0 6px 18px rgba(0,0,0,.08)}
.pf-card.wide{grid-column:span 3;display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1.2fr);column-gap:1.2rem}
.pf-card.wide .pf-shot{grid-row:span 5}
.pf-card[hidden]{display:none}
.pf-card.show{animation:pfin .4s ease both}
@keyframes pfin{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
.pf-card h3{font-size:1.05rem;font-weight:500;margin:0 0 .4rem}
.pf-card p{margin:0 0 .5rem;font-size:.93rem}
.pf-type{font-size:.75rem !important;letter-spacing:.06em;text-transform:uppercase;color:var(--global-theme-color);margin-bottom:.25rem !important}
.pf-links,.pf-tags{font-size:.82rem !important}
.pf-tags{opacity:.65;margin:0 !important}
.pf-shot{display:block;border:1px solid var(--global-divider-color);border-radius:8px;overflow:hidden}
.pf-shot img{width:100%;height:210px;object-fit:cover;object-position:top;display:block}
@media (max-width:900px){.pf-grid{grid-template-columns:repeat(2,minmax(0,1fr))}.pf-card.wide{grid-column:span 2}}
@media (max-width:600px){.pf-grid{grid-template-columns:1fr}.pf-card.wide{grid-column:span 1;display:block}.pf-shot{margin-bottom:.7rem}}
@media (prefers-reduced-motion:reduce){.pf-card.show{animation:none}.pf-card:hover{transform:none}}
</style>

<div class="pf-chips" role="group" aria-label="Filter the portfolio by field" id="pf-chips"><button type="button" data-k="all" aria-pressed="true">All fields</button><button type="button" data-k="driving" aria-pressed="false">Automated driving</button><button type="button" data-k="ai" aria-pressed="false">AI and machine learning</button><button type="button" data-k="safety" aria-pressed="false">Safety and cybersecurity</button><button type="button" data-k="simulation" aria-pressed="false">Simulation</button><button type="button" data-k="robotics" aria-pressed="false">Robotics</button><button type="button" data-k="automation" aria-pressed="false">Industrial automation</button><button type="button" data-k="sensors" aria-pressed="false">Sensors and electronics</button><button type="button" data-k="teaching" aria-pressed="false">Teaching</button><button type="button" data-k="tools" aria-pressed="false">Software tools</button></div>

<div class="pf-grid" id="pf-grid">
<article class="pf-card wide" data-f="safety ai driving"><a class="pf-shot" href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"><img src="{{ '/assets/img/project-assurance.png' | relative_url }}" alt="Preview of: Assurance case explorer"></a><p class="pf-type">Research</p><h3>Assurance case explorer</h3><p>Interactive website with an assurance case for an AI-based perception component. Each claim names the source clause in the standard.</p><p class="pf-links"><a href="https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/">Open</a> · <a href="https://github.com/milinpatel07/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case">Code</a> · <a href="https://doi.org/10.1007/978-3-032-35506-5_55">Publication</a></p><p class="pf-tags">Safety and cybersecurity · AI and machine learning · Automated driving</p></article>
<article class="pf-card wide" data-f="safety ai"><a class="pf-shot" href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"><img src="{{ '/assets/img/project-rain.png' | relative_url }}" alt="Preview of: Statistical test for a performance target in heavy rain"></a><p class="pf-type">Research</p><h3>Statistical test for a performance target in heavy rain</h3><p>Test of an uncertainty threshold of a perception model under a triggering condition (ISO 21448). The linked page explains the test without formulas.</p><p class="pf-links"><a href="https://milinpatel07.github.io/lidar-performance-target-applicability/story.html">Open</a> · <a href="https://github.com/milinpatel07/lidar-performance-target-applicability">Code</a></p><p class="pf-tags">Safety and cybersecurity · AI and machine learning</p></article>
<article class="pf-card" data-f="ai safety driving"><p class="pf-type">Research</p><h3>Uncertainty evaluation for LiDAR object detection</h3><p>Evaluation pipeline with an ensemble of object detectors, weather augmentation, calibration analysis and a safety class for each frame.</p><p class="pf-links"><a href="https://github.com/milinpatel07/SOTIF_Uncertainty_Evaluation_Lidar_Object_Detection">Code</a> · <a href="https://doi.org/10.5220/0014967200004030">Publication</a></p><p class="pf-tags">AI and machine learning · Safety and cybersecurity · Automated driving</p></article>
<article class="pf-card" data-f="simulation ai driving"><p class="pf-type">Research</p><h3>Simulated LiDAR dataset with 21 weather conditions</h3><p>Generation of LiDAR point cloud data in the CARLA simulator and evaluation of 3D object detectors on the dataset.</p><p class="pf-links"><a href="https://github.com/milinpatel07/SOTIF-PCOD">Code</a> · <a href="https://doi.org/10.5220/0012707300003702">Publication</a></p><p class="pf-tags">Simulation · AI and machine learning · Automated driving</p></article>
<article class="pf-card" data-f="driving safety simulation"><p class="pf-type">Research</p><h3>Driver misuse of automated driving functions</h3><p>Simulation-based tests of reasonably foreseeable misuse by the driver, with test requirements and evaluation criteria for countermeasures.</p><p class="pf-links"><a href="https://doi.org/10.1007/978-981-99-3043-2_15">Publication</a> · <a href="https://doi.org/10.47953/sae-pp-00371">Preprint</a></p><p class="pf-tags">Automated driving · Safety and cybersecurity · Simulation</p></article>
<article class="pf-card" data-f="simulation driving"><p class="pf-type">Research</p><h3>Simulation model of a lane change assistance system</h3><p>MATLAB/Simulink model for the validation of a transverse guidance assist system, with trajectory planning by a high-order polynomial.</p><p class="pf-links"><a href="https://github.com/milinpatel07/TGAS-Sim">Code</a> · <a href="https://doi.org/10.1109/ICECCME52200.2021.9591044">Publication</a></p><p class="pf-tags">Simulation · Automated driving</p></article>
<article class="pf-card" data-f="safety driving"><p class="pf-type">Research</p><h3>Systematic literature review on SOTIF</h3><p>Review of the published research on the safety of the intended functionality, with research gaps and a comparison of methods.</p><p class="pf-links"><a href="https://doi.org/10.4271/2025-01-5030">Publication</a></p><p class="pf-tags">Safety and cybersecurity · Automated driving</p></article>
<article class="pf-card" data-f="safety ai automation"><p class="pf-type">Research community</p><h3>Peer review</h3><p>Reviews for Control Engineering Practice, IEEE Transactions on Software Engineering, Journal of Experimental &amp; Theoretical Artificial Intelligence, and Reliability Engineering &amp; System Safety.</p><p class="pf-links"><a href="https://orcid.org/0000-0002-8357-6018">ORCID record</a></p><p class="pf-tags">Safety and cybersecurity · AI and machine learning · Industrial automation</p></article>
<article class="pf-card" data-f="teaching ai"><p class="pf-type">Teaching</p><h3>School workshop on AI-based perception</h3><p>Pupils run an object detector on a street scene. The detector misses pedestrians in fog and fails on a manipulated image. In German, without programming.</p><p class="pf-links"><a href="https://github.com/milinpatel07/campustage-2026-sicher-durch-zufall">Workshop</a></p><p class="pf-tags">Teaching · AI and machine learning</p></article>
<article class="pf-card" data-f="teaching driving"><p class="pf-type">Teaching</p><h3>Thesis supervision</h3><p>Supervision of bachelor's and master's theses and internships at IFM.</p><p class="pf-tags">Teaching · Automated driving</p></article>
<article class="pf-card" data-f="teaching"><p class="pf-type">Teaching</p><h3>Erasmus+ workshops</h3><p>Workshops for students from European countries in the Erasmus+ programme.</p><p class="pf-tags">Teaching</p></article>
<article class="pf-card" data-f="tools ai"><p class="pf-type">Tool</p><h3>Document chat</h3><p>Question answering on uploaded documents, with a page reference and the source passage for each answer. Retrieval-augmented generation with Streamlit.</p><p class="pf-links"><a href="https://github.com/milinpatel07/doc-chat">Code</a></p><p class="pf-tags">Software tools · AI and machine learning</p></article>
<article class="pf-card" data-f="automation"><p class="pf-type">Industry</p><h3>SCADA monitoring system for quality checks</h3><p>Supervisory control and data acquisition (SCADA) system with automatic reports in the machine tool industry, connected to Schneider Electric programmable logic controllers.</p><p class="pf-tags">Industrial automation</p></article>
<article class="pf-card" data-f="automation sensors"><p class="pf-type">Engineering project</p><h3>Real-time Ethernet for an industrial process</h3><p>EtherCAT communication between a Raspberry Pi master and STM Nucleo boards with a Hilscher netSHIELD, programmed in embedded C.</p><p class="pf-tags">Industrial automation · Sensors and electronics</p></article>
<article class="pf-card" data-f="robotics sensors"><p class="pf-type">Engineering project</p><h3>2D mapping with a LiDAR sensor</h3><p>Simultaneous localisation and mapping (SLAM) with ROS, an RPLidar sensor and a Raspberry Pi, with the ROS toolbox of MATLAB.</p><p class="pf-tags">Robotics · Sensors and electronics</p></article>
<article class="pf-card" data-f="robotics"><p class="pf-type">Engineering project</p><h3>Pick-and-place robotic arm</h3><p>Robotic arm with three degrees of freedom, servo motors and an Arduino controller.</p><p class="pf-tags">Robotics</p></article>
<article class="pf-card" data-f="sensors"><p class="pf-type">Engineering project</p><h3>Solar cell fabrication</h3><p>Fabrication of a photovoltaic cell on a silicon wafer in a clean room, with deposition, etching and lithography.</p><p class="pf-tags">Sensors and electronics</p></article>
<article class="pf-card" data-f="sensors"><p class="pf-type">Engineering project</p><h3>Heart-rate measurement with a smartphone camera</h3><p>Video of a fingertip on the camera lens, processed in MATLAB for the heart rate.</p><p class="pf-tags">Sensors and electronics</p></article>
<article class="pf-card" data-f="automation"><p class="pf-type">Engineering project</p><h3>Composter bin for organic waste</h3><p>Prototype of a kitchen appliance for the conversion of organic waste into manure.</p><p class="pf-tags">Industrial automation</p></article>
</div>

<script>
(function(){
  var chips=[].slice.call(document.querySelectorAll('#pf-chips button')), cards=[].slice.call(document.querySelectorAll('#pf-grid .pf-card'));
  function apply(k){
    var n=0;
    chips.forEach(function(c){c.setAttribute('aria-pressed',c.dataset.k===k);});
    cards.forEach(function(c){
      var on=k==='all'||c.dataset.f.split(' ').indexOf(k)>-1;
      c.hidden=!on; c.classList.remove('show');
      if(on){ c.style.animationDelay=(n*45)+'ms'; void c.offsetWidth; c.classList.add('show'); n++; }
    });
  }
  chips.forEach(function(c){c.addEventListener('click',function(){apply(c.dataset.k); history.replaceState(null,'',c.dataset.k==='all'?location.pathname:'#'+c.dataset.k);});});
  var h=location.hash.replace('#','');
  apply(chips.some(function(c){return c.dataset.k===h;})?h:'all');
})();
</script>
