---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<p class="prism-lead">We build AI-enabled smart sensing platforms, computer vision &amp; generative-AI pipelines, and physics-informed digital twins that turn infrastructure data into actionable intelligence for safer, more resilient communities.</p>

<figure class="prism-figure"><img src="/images/research-overview.png" alt="Multidisciplinary research overview: seismic sensing, machine-vision sensor, digital twin, LLMs and generative AI, SHM and edge AI, PINN machine learning, and UAV"></figure>

## Current Projects

<section class="prism-project">
  <div class="prism-project__media prism-project__media--pair">
    <img src="/images/projects/lifeark-test-setup-actuator.png" alt="Reaction frame and hydraulic actuator loading a full-scale LifeArk unit">
    <img src="/images/projects/lifeark-test-setup-plan.png" alt="Full-scale LifeArk unit anchored to the strong floor">
  </div>
  <div class="prism-project__text">
    <h3>Full-scale seismic testing of LifeArk modular buildings</h3>
    <p class="prism-project__meta">PI, with Co-PI Robert K. Dowell &middot; Funded by LifeArk &middot; 2026&ndash;27</p>
    <p>Six full-scale HDPE composite building units under monotonic, cyclic, and shake-table loading to establish the <strong>first code-recognized seismic performance factors</strong> (R, &Omega;<sub>0</sub>, C<sub>d</sub>) for this housing system under FEMA P-695 and AC494. A custom reaction frame and hydraulic actuator are paired with stereo-camera 3D vision measurement and nonlinear OpenSees models. Outcome: a permitting pathway for rapidly deployable <a href="https://lifeark.net/disaster-relief" target="_blank" rel="noopener">disaster-relief housing</a>.</p>
  </div>
</section>

<section class="prism-project">
  <div class="prism-project__media prism-project__media--wide">
    <img src="/images/projects/csmip-physics-ai.svg" alt="Pipeline: instrumented building, multi-event ground-motion records, physics-informed neural network, story-level damage map">
  </div>
  <div class="prism-project__text">
    <h3>Physics-informed AI for post-earthquake damage identification</h3>
    <p class="prism-project__meta">PI &middot; California Department of Conservation (CSMIP) &middot; $100K &middot; 2026&ndash;27</p>
    <p>Decades of strong-motion records from instrumented California buildings, used together rather than one event at a time. A physics-informed network constrained by the equations of motion learns story stiffness across events, separating <strong>recoverable softening from irreversible seismic damage</strong>.</p>
  </div>
</section>

<section class="prism-project">
  <div class="prism-project__media">
    <img src="/images/publications/pinn.jpg" alt="Physics-informed recurrent neural network for bridge response and damage identification">
  </div>
  <div class="prism-project__text">
    <h3>Physics-informed neural networks for bridge damage detection</h3>
    <p>An unsupervised PINN framework that fuses inspection, drone survey, and finite-element model information. <strong>Over 95% damage identification accuracy</strong> for train crossings on the full-scale Calumet Bridge, Chicago.</p>
  </div>
</section>

<section class="prism-project">
  <div class="prism-project__media">
    <img src="/images/publications/drone-bridge-inspection.jpg" alt="UAV flight path over a reconstructed bridge point cloud">
  </div>
  <div class="prism-project__text">
    <h3>Drone-based damage mapping with deep learning</h3>
    <p>3D damage localization and severity mapping of steel truss bridges from UAV video in GPS-denied settings, validated on a <strong>100-year-old truss bridge</strong>.</p>
  </div>
</section>

<style>
.prism-lead {
  font-size: 1.15em;
  line-height: 1.6;
  color: var(--prism-muted);
  margin-bottom: 1.5em;
}

.prism-project {
  display: grid;
  grid-template-columns: 300px 1fr;
  gap: 1.75rem;
  align-items: start;
  padding: 1.75rem 0;
  border-top: 1px solid var(--prism-border);
}
.prism-project:last-of-type { border-bottom: 1px solid var(--prism-border); }
.prism-project__media img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 10px;
  background: #fff;
}
.prism-project__media--pair {
  display: grid;
  gap: 0.6rem;
}
.prism-project__media--wide {
  grid-column: 1 / -1;
}
.prism-project__media--wide img {
  max-width: 820px;
  margin: 0 auto;
  padding: 0.5rem 0;
}
.archive .prism-project__text h3 {
  margin: 0 0 0.3rem;
  font-size: 1.2rem;
  line-height: 1.3;
}
.prism-project__meta {
  margin: 0 0 0.7rem;
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: var(--prism-red-text);
}
.prism-project__text p {
  margin: 0;
  font-size: 0.97rem;
  line-height: 1.65;
}
html[data-theme="dark"] .prism-project__media img { padding: 0.4rem; }
@media (max-width: 760px) {
  .prism-project { grid-template-columns: 1fr; gap: 1rem; }
}
</style>
