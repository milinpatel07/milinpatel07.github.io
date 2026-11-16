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
.lc{background:#0b1226;color:#e8eef8;border-radius:14px;padding:1.4rem;display:grid;grid-template-columns:minmax(0,1fr) minmax(0,1.1fr);gap:2.6rem;margin:1.2rem 0 2rem}
.lc a{color:#5ad1f0}
.lc p,.lc b{color:#e8eef8}
.lc-ring{position:relative;aspect-ratio:1/1;max-width:430px;width:100%;margin:0 auto}
.lc-ring svg{position:absolute;inset:0;width:100%;height:100%}
.lc-orbit{fill:none;stroke:#2a3a63;stroke-width:1;stroke-dasharray:2 5}
.lc-arm{transform-origin:50px 50px;transition:transform .7s cubic-bezier(.4,0,.2,1)}
.lc-dot{fill:none;stroke:#5ad1f0;stroke-width:.6;opacity:.7}
.lc-centre{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);text-align:center;font-size:.72rem;letter-spacing:.08em;text-transform:uppercase;color:#8fa3c8;line-height:1.35;width:6.5rem}
.lc-node{position:absolute;transform:translate(-50%,-50%);width:2.3rem;height:2.3rem;background:none;border:0;padding:0;font:inherit;cursor:pointer}
.lc-node span.n{display:grid;place-items:center;width:100%;height:100%;border-radius:50%;border:1.5px solid #3a4f85;background:#12203f;font-size:.85rem;font-weight:500;color:#e8eef8;transition:background-color .3s,border-color .3s,transform .3s}
.lc .lc-node span.l{position:absolute;width:5.2rem;font-size:.8rem;line-height:1.2;color:#b9c6e0}
.lc-node.right span.l{left:calc(100% + .5rem);top:50%;transform:translateY(-50%);text-align:left}
.lc-node.left span.l{right:calc(100% + .5rem);top:50%;transform:translateY(-50%);text-align:right}
.lc-node.top span.l{bottom:calc(100% + .35rem);left:50%;transform:translateX(-50%);text-align:center;width:9rem}
.lc-node.bottom span.l{top:calc(100% + .35rem);left:50%;transform:translateX(-50%);text-align:center;width:9rem}
.lc-node:hover span.n{border-color:#5ad1f0}
.lc .lc-node[aria-selected=true] span.l{color:#fff}
.lc-node[aria-selected=true] span.n{background:#5ad1f0;border-color:#5ad1f0;color:#0b1226;transform:scale(1.12)}
.lc-node:focus-visible{outline:2px solid #5ad1f0;outline-offset:4px;border-radius:6px}
.lc-panel{align-self:center;min-height:17rem}
.lc-panel.swap{animation:lcin .4s ease}
@keyframes lcin{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
.lc .lc-panel .ph{font-size:.75rem;letter-spacing:.08em;text-transform:uppercase;color:#5ad1f0;margin:0 0 .2rem}
.lc-panel h3{font-size:1.35rem;font-weight:500;margin:0 0 .7rem;color:#fff}
.lc-panel p{margin:0 0 .7rem;font-size:.97rem}
.lc-panel .res{border-left:2px solid #5ad1f0;padding-left:.8rem}
.lc-panel .ref{font-size:.86rem;margin:0}
.lc-nav{display:flex;gap:.6rem;margin-top:1rem}
.lc-nav button{font:inherit;font-size:.85rem;color:#e8eef8 !important;background:#12203f;border:1px solid #3a4f85;border-radius:999px;padding:.3rem .9rem;cursor:pointer}
.lc-nav button:hover{border-color:#5ad1f0}
.social .contact-icons a i,.social .contact-icons a svg{font-size:1.9rem}
@media (max-width:760px){.lc{grid-template-columns:1fr;padding:1rem}.lc-ring{max-width:300px;margin:1.6rem auto}.lc .lc-node span.l{width:4rem;font-size:.7rem}.lc-panel{min-height:0}}
@media (prefers-reduced-motion:reduce){.lc-arm{transition:none}.lc-panel.swap{animation:none}}
</style>

_Prodigy in an infant state on career progression path._

I am an engineer and researcher at the [Institute for Driver Assistance and Connected Mobility (IFM)](https://www.hs-kempten.de/ifm) of Kempten University of Applied Sciences, Germany. I work on the safety and cybersecurity of artificial intelligence (AI) in automated driving.

Some vehicles can drive parts of a journey without the driver. Software in the vehicle has to recognise people, other vehicles and the road from sensor data. The software uses AI and can make errors, for example in heavy rain or when someone manipulates a sensor.

I develop methods to find errors of AI-based perception before the release of a vehicle and during its operation, and to demonstrate to an independent assessor that the remaining risk is acceptable. The methods are simulation-based tests, performance measurements, and assurance cases that combine safety and cybersecurity.

## My work along the lifecycle of an AI component

An AI component passes through the phases shown in the figure, from concept to updates. Each phase raises a question about safety and cybersecurity. Select a phase to read the question, my work on it, and the result.

<div class="lc" id="lc">
  <div class="lc-ring">
    <svg viewBox="0 0 100 100" aria-hidden="true"><ellipse class="lc-orbit" cx="50" cy="50" rx="34" ry="38"/><g class="lc-arm" id="lc-arm"><circle class="lc-dot" cx="50" cy="50" r="8"/></g></svg>
    <div class="lc-centre">Lifecycle of an AI component</div>
    <div role="tablist" aria-label="Phases of the lifecycle" id="lc-tabs"></div>
  </div>
  <div>
    <div class="lc-panel" id="lc-panel" role="tabpanel" aria-live="polite"></div>
    <div class="lc-nav"><button type="button" id="lc-prev">Previous phase</button><button type="button" id="lc-next">Next phase</button></div>
  </div>
</div>

<noscript><p>The phases are: concept and requirements, data and design, verification and validation, release, operation, and updates. The <a href="{{ '/publications/' | relative_url }}">publications</a> page lists the work for each phase.</p></noscript>

Besides this research, I supervise bachelor's and master's theses and conduct workshops for students from European countries in the Erasmus+ programme. The [projects]({{ '/projects/' | relative_url }}) page shows a school workshop and two interactive explanations of my research.

## Background

I have been a Research Associate at IFM since 2021 and am a PhD candidate. I hold a B.Tech. in Instrumentation and Control Engineering (India) and an M.Sc. in Smart Systems (Germany). Before research, I developed a supervisory control and data acquisition (SCADA) system for quality checks in the machine tool industry. I review manuscripts for scientific journals and conferences. The [CV]({{ '/cv/' | relative_url }}) gives the details.

<script>
(function(){
  var D="https://doi.org/", P=[
   {t:"Concept and requirements", q:"What can go wrong?", pos:[50,12,"top"],
    w:"Before design, I analyse hazards. One source is reasonably foreseeable misuse of an automated driving function by the driver. A second source is the limits of the function itself, which the safety of the intended functionality (SOTIF) covers: hazards that arise without a fault.",
    r:"Research gaps and a comparison of the methods that support SOTIF, from a systematic literature review. Test requirements and evaluation criteria for misuse scenarios.",
    l:[["Systematic literature review",D+"10.4271/2025-01-5030"],["Mitigation of foreseeable misuse",D+"10.47953/sae-pp-00371"]]},
   {t:"Data and design", q:"Are the data fit for purpose?", pos:[79,30,"right"],
    w:"An AI-based object detector depends on the data used to train and test it. I generate LiDAR (laser-based distance sensor) data in simulation, where each weather condition can be set and repeated.",
    r:"A simulated LiDAR dataset with 21 weather conditions, with public code.",
    l:[["Performance evaluation in simulation",D+"10.5220/0012707300003702"],["Code","https://github.com/milinpatel07/SOTIF-PCOD"]]},
   {t:"Verification and validation", q:"Are the targets met?", pos:[79,70,"right"],
    w:"I test automated driving functions in simulation, and I evaluate the uncertainty of each detection of an AI-based object detector.",
    r:"Disagreement between several detectors separates incorrect detections from correct ones. A statistical test checks whether a performance target still holds in a condition such as heavy rain.",
    l:[["Uncertainty evaluation",D+"10.5220/0014967200004030"],["Uncertainty representation",D+"10.1007/978-3-032-23187-1_10"],["Testing of foreseeable misuse",D+"10.1007/978-981-99-3043-2_15"],["Trajectory planning",D+"10.1109/ICECCME52200.2021.9591044"],["Explanation of the statistical test","https://milinpatel07.github.io/lidar-performance-target-applicability/story.html"]]},
   {t:"Release", q:"Is the case complete?", pos:[50,88,"bottom"],
    w:"An assurance case is a structured argument, supported by evidence, that a system is acceptably safe. I combine the safety claims and the cybersecurity claims for an AI-based perception component in one assurance case.",
    r:"At the verification and validation goal, the evidence types of the standards use different measurement scales, and no standard prescribes how they combine.",
    l:[["Assurance argument pattern",D+"10.1007/978-3-032-35506-5_55"],["Assurance case explorer","https://milinpatel07.github.io/Assurance-Gaps-in-an-Integrated-Safety-and-Cybersecurity-Case/"]]},
   {t:"Operation", q:"Does it hold in operation?", pos:[21,70,"left"],
    w:"In operation, no ground truth is available. An anomaly in the perception output carries no label for its cause, which can be a performance insufficiency or an attack.",
    r:"A position paper that states this gap at the level of the clauses of the standards and sets requirements for a method that resolves it.",
    l:[["Position paper, listed under publications","{{ '/publications/' | relative_url }}"]]},
   {t:"Updates", q:"Does it hold after updates?", pos:[21,30,"left"],
    w:"An update of an AI component can invalidate evidence that was produced for the earlier version. The question is part of my current research.",
    r:"No publication yet.",
    l:[]}
  ];
  var tabs=document.getElementById('lc-tabs'), panel=document.getElementById('lc-panel'), arm=document.getElementById('lc-arm'), cur=0, btns=[];
  P.forEach(function(p,i){
    var b=document.createElement('button'); b.type='button'; b.className='lc-node '+p.pos[2]; b.setAttribute('role','tab'); b.id='lc-t'+i;
    b.setAttribute('aria-controls','lc-panel'); b.style.left=p.pos[0]+'%'; b.style.top=p.pos[1]+'%';
    b.innerHTML='<span class="n">'+(i+1)+'</span><span class="l">'+p.t+'</span>';
    b.addEventListener('click',function(){show(i,false);});
    b.addEventListener('keydown',function(e){
      if(e.key==='ArrowRight'||e.key==='ArrowDown'){e.preventDefault();show((cur+1)%P.length,true);}
      if(e.key==='ArrowLeft'||e.key==='ArrowUp'){e.preventDefault();show((cur+P.length-1)%P.length,true);}
    });
    tabs.appendChild(b); btns.push(b);
  });
  function show(i,focus){
    cur=i; var p=P[i];
    btns.forEach(function(b,j){b.setAttribute('aria-selected',j===i); b.tabIndex=j===i?0:-1;});
    arm.style.transform='translate('+(p.pos[0]-50)+'px,'+(p.pos[1]-50)+'px)';
    var links=p.l.map(function(x){return '<a href="'+x[1]+'">'+x[0]+'</a>';}).join(' · ');
    panel.setAttribute('aria-labelledby','lc-t'+i);
    panel.innerHTML='<p class="ph">Phase '+(i+1)+': '+p.t+'</p><h3>'+p.q+'</h3><p>'+p.w+'</p><p class="res"><b>Result.</b> '+p.r+'</p>'+(links?'<p class="ref">'+links+'</p>':'');
    panel.classList.remove('swap'); void panel.offsetWidth; panel.classList.add('swap');
    if(focus) btns[i].focus();
  }
  document.getElementById('lc-prev').addEventListener('click',function(){show((cur+P.length-1)%P.length,false);});
  document.getElementById('lc-next').addEventListener('click',function(){show((cur+1)%P.length,false);});
  show(0,false);
})();
</script>
