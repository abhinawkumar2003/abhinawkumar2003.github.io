---
title: Research
layout: default
permalink: /pages/research/
---

<p class="research-lead">
My research focuses on <b>bridging coarse-grained and atomistic simulations</b> using
<b>machine-learning–based probabilistic backmapping</b>. I develop generative models that
produce <b>thermodynamically meaningful atomistic ensembles</b> from coarse-grained
configurations, enabling direct connection between efficient CG sampling and atomistic physics.
</p>

<div class="research-bullets">
  <div class="rchip"><span class="dot"></span> Generative models for one-to-many mappings</div>
  <div class="rchip"><span class="dot"></span> Ensemble recovery via reweighting / stabilization</div>
  <div class="rchip"><span class="dot"></span> Proteins & assemblies (IDPs, aggregation)</div>
  <div class="rchip"><span class="dot"></span> Soft matter, nucleation, porous materials</div>
</div>

<hr class="soft-rule">

<section class="research-section">
  <h2>Current Focus</h2>

  <div class="rblock">
    <figure>
      <img class="rfig-img" src="/assets/img/backmapping.png"
        alt="Schematic: coarse-grained configuration → probabilistic atomistic ensemble → reweighting to recover Boltzmann statistics">
      <figcaption>CG configuration → probabilistic AA generation → reweighting to recover Boltzmann statistics.</figcaption>
    </figure>
    <div class="rblock-title">
      Probabilistic CG→AA backmapping with generative models
    </div>
    <div class="rblock-text">
      Using <b>diphenylalanine</b> as a model system, I develop
      <b>probabilistic normalizing-flow–based decoders</b> that generate
      <b>ensembles of atomistic structures</b> consistent with a given coarse-grained configuration.
      The models capture conformational diversity, preserve correlations between internal degrees
      of freedom, and produce physically realistic structures that can be used directly in
      molecular dynamics simulations.
    </div>
    <div class="rblock-text">
      Ongoing work focuses on <b>reweighting generated ensembles</b> to recover
      <b>Boltzmann statistics</b>, enabling quantitative study of
      <b>peptide self-assembly at atomistic resolution</b> while retaining the efficiency of
      coarse-grained sampling.
    </div>
    <div class="rblock-tags">
      <span class="pill">Normalizing flows</span>
      <span class="pill">Probabilistic generation</span>
      <span class="pill">Reweighting</span>
      <span class="pill">Peptide self-assembly</span>
    </div>
  </div>


  <div class="rblock">
    <div class="rblock-title">Stabilizing importance weights (higher effective sample size)</div>
    <div class="rblock-text">
      Because backmapping is intrinsically a <b>high-variance importance-sampling problem</b>,
      practical reweighting can suffer from weight collapse.
      I investigate <b>stabilization strategies</b> that improve effective sample size (ESS)
      while preserving unbiased thermodynamic observables.
    </div>
    <div class="rblock-tags">
      <span class="pill">Reweighting</span>
      <span class="pill">ESS</span>
      <span class="pill">Uncertainty</span>
    </div>
  </div>
</section>

<hr class="soft-rule">

<section class="research-section">
  <h2>Research Themes</h2>

  <div class="research-themes">
    <div class="theme">
      <div class="theme-title">Proteins & intrinsically disordered systems</div>
      <div class="theme-text">
        Sequence–ensemble relationships, aggregation propensity, and multiscale structure generation for IDPs and assemblies.
      </div>
    </div>

    <div class="theme">
      <div class="theme-title">Chromatin / protein–DNA organization</div>
      <div class="theme-text">
        Condensate and chromatin compaction dynamics from simulation, with emphasis on mechanistic, interpretable physical drivers.
      </div>
    </div>

    <div class="theme">
      <div class="theme-title">Self-assembly, nucleation, porous materials</div>
      <div class="theme-text">
        Mesophase self-assembly, polymorph selection, and nucleation pathways in nanoparticle and porous-material systems.
      </div>
    </div>
  </div>
</section>

<hr class="soft-rule">

<section class="research-section">
  <h2>Methods Toolkit</h2>

  <div class="research-cols">
    <div>
      <h3 class="minihead">Machine Learning</h3>
      <ul class="about2-list">
        <li>Normalizing flows / diffusion-style score models (generative decoders)</li>
        <li>Conditional generation with calibrated probabilities</li>
        <li>Evaluation via reweighting, ESS, and observable agreement</li>
      </ul>
    </div>

    <div>
      <h3 class="minihead">Simulation &amp; Analysis</h3>
      <ul class="about2-list">
        <li>Molecular dynamics, coarse-graining, internal-coordinate representations</li>
        <li>Statistical mechanics, free energies, reweighting diagnostics</li>
        <li>Reproducible pipelines for training + generation + analysis</li>
      </ul>
    </div>
  </div>
</section>

<hr class="soft-rule">

<section class="research-section">
  <h2>Selected Outputs</h2>
  <p class="muted">
    See <a href="/pages/publications/">Publications</a> and <a href="/pages/talks/">Talks &amp; Posters</a> for details.
  </p>
</section>
