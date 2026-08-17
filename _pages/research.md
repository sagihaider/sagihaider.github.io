---
layout: page
permalink: /research/
title: research
description: Adaptive and applied artificial intelligence research
nav: true
nav_order: 4
---

<div class="research-page">
  <header class="research-hero">
    <p class="research-eyebrow">Research profile</p>
    <h1>Adaptive AI that works in the real world</h1>
    <p class="research-lede">My research connects advances in machine learning with problems that matter in healthcare, neural engineering, organisations, and the environment. A recurring question guides the work: how can intelligent systems remain reliable when people, data, and operating conditions change?</p>
    <div class="research-actions" aria-label="Explore research">
      <a class="research-button research-button--primary" href="#research-clusters">Explore research themes</a>
      <a class="research-button" href="/projects/">View funded projects</a>
      <a class="research-button" href="/publications/">Browse publications</a>
    </div>
  </header>

  <nav class="research-map" aria-label="Research areas">
    <a href="#adaptive-ai"><span>01</span><strong>Adaptive &amp; trustworthy AI</strong><small>Methods for changing data and environments</small></a>
    <a href="#neural-engineering"><span>02</span><strong>Neural engineering</strong><small>EEG, MEG and brain–computer interfaces</small></a>
    <a href="#health-ai"><span>03</span><strong>AI for health</strong><small>Computer vision, triage and clinical decisions</small></a>
    <a href="#applied-ai"><span>04</span><strong>Applied &amp; responsible AI</strong><small>Environment, enterprise and public value</small></a>
  </nav>

  <section class="research-section" id="adaptive-ai">
    <div class="research-section__intro">
      <p class="research-eyebrow">Methodological foundations</p>
      <h2>Building intelligence for changing conditions</h2>
      <p>My methodological work provides a common foundation across the application areas below. It focuses on models that adapt, explain their reasoning, and operate efficiently beyond controlled laboratory settings.</p>
    </div>
    <div class="method-grid">
      <article><span class="method-number">01</span><h3>Domain adaptation</h3><p>Learning methods that remain useful when training and deployment data come from different distributions, subjects, devices, or settings.</p></article>
      <article><span class="method-number">02</span><h3>Dataset-shift detection</h3><p>Online and retrospective approaches for recognising covariate shift early and supporting reliable model adaptation.</p></article>
      <article><span class="method-number">03</span><h3>Efficient vision transformers</h3><p>Lightweight, explainable vision models trained for specialist domains, with particular emphasis on medical imaging.</p></article>
      <article><span class="method-number">04</span><h3>Agentic &amp; multimodal AI</h3><p>Human-centred systems that combine language, vision, organisational knowledge, and accountable decision support.</p></article>
    </div>
  </section>

  <section class="research-section" id="research-clusters">
    <div class="research-section__intro">
      <p class="research-eyebrow">Applied research clusters</p>
      <h2>From methods to measurable impact</h2>
      <p>Each cluster brings together a research problem, selected evidence, and the funded programmes through which the work is translated into practice.</p>
    </div>

    <div class="cluster-list">
      <details class="research-cluster" id="neural-engineering" open>
        <summary><span class="cluster-index">01</span><span class="cluster-title"><strong>Neural engineering &amp; brain–computer interfaces</strong><small>Adaptive learning for EEG, MEG, motor imagery and rehabilitation</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <p>I develop adaptive machine-learning methods for non-stationary neural signals. This includes covariate-shift detection and adaptive ensembles for EEG-based BCI {% cite raza2015ewma raza2016adaptive raza2019covariate %}, frequency-band selection {% cite raza2015optimising %}, and cortico-muscular coupling for personalised stroke rehabilitation {% cite chowdhury2019eeg chowdhury2017online chowdhury2018active %}.</p>
          <p>Our team also released a public 306-channel MEG imagery dataset {% cite rathee2021magnetoencephalography %} and collaborated internationally on decoding numeracy and literacy in the human brain {% cite nara2023decoding %}.</p>
          <div class="research-tags" aria-label="Topics"><span>EEG &amp; MEG</span><span>BCI</span><span>Domain adaptation</span><span>Neurorehabilitation</span></div>
        </div>
      </details>

      <details class="research-cluster" id="health-ai">
        <summary><span class="cluster-index">02</span><span class="cluster-title"><strong>AI for health &amp; clinical decisions</strong><small>Earlier diagnosis, intelligent triage and explainable medical vision</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <p>This cluster translates computer vision and predictive analytics into practical clinical tools. Current themes include explainable skin-cancer detection, AI-assisted patient triage, forensic dentistry, medical imaging, and decision support built around patient and clinician needs.</p>
          <p>The work ranges from efficient vision models to deployed service redesign, including a smart referral system that accelerated musculoskeletal triage and a partnership developing robust melanoma-detection technology.</p>
          <div class="project-links" aria-label="Related health projects">
            <a href="/projects/KTP_C4C/">Skin cancer diagnosis <span>↗</span></a><a href="/projects/KTP_Provide/">NHS patient triage <span>↗</span></a><a href="/projects/KTP-Hurdle/">Data-driven healthcare <span>↗</span></a><a href="/projects/Royal-Society-IE/">Trustworthy medical AI <span>↗</span></a><a href="/projects/ESNEFT-Colchester-Hospital/">Clinical AI collaboration <span>↗</span></a>
          </div>
        </div>
      </details>

      <details class="research-cluster" id="applied-ai">
        <summary><span class="cluster-index">03</span><span class="cluster-title"><strong>Environment &amp; public-interest AI</strong><small>Evidence for ecosystems, climate resilience and public policy</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <p>I apply machine learning, computer vision, and connected sensing to environmental challenges including forest-fire prediction, biodiversity monitoring, crop analysis, and evidence-led policy. The emphasis is on useful, context-aware systems developed with domain and community partners.</p>
          <div class="project-links" aria-label="Related environment projects"><a href="/projects/GCRF-Forest-Fire/">Forest-fire prediction <span>↗</span></a><a href="/projects/KTP-RSPB/">Conservation technology <span>↗</span></a><a href="/projects/Contract-Alula/">AlUla smart city &amp; environment <span>↗</span></a><a href="/projects/ESRC-BLGDRC/">Data and public policy <span>↗</span></a></div>
        </div>
      </details>

      <details class="research-cluster">
        <summary><span class="cluster-index">04</span><span class="cluster-title"><strong>Enterprise, engineering &amp; operational AI</strong><small>Responsible transformation through knowledge exchange</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <p>Through Knowledge Transfer Partnerships and collaborative R&amp;D, I help organisations convert research into dependable products and processes. Themes include construction intelligence, manufacturing, logistics, revenue optimisation, generative AI, and organisational readiness for responsible adoption.</p>
          <div class="project-links" aria-label="Related enterprise projects"><a href="/projects/KTP_Mersea/">Construction intelligence <span>↗</span></a><a href="/projects/KTP-MEL/">Engineering analytics <span>↗</span></a><a href="/projects/KTP_Trunk/">Digital operations <span>↗</span></a><a href="/projects/KTP-Strom/">Industrial AI <span>↗</span></a><a href="/projects/KTP-Unisurge/">Manufacturing innovation <span>↗</span></a><a href="/projects/KTP-RevWise/">Revenue optimisation <span>↗</span></a><a href="/projects/East-AI-Studio/">Enterprise AI adoption <span>↗</span></a></div>
        </div>
      </details>
    </div>
  </section>

  <section class="research-principle" aria-labelledby="research-principle-title">
    <p class="research-eyebrow">Research philosophy</p>
    <h2 id="research-principle-title">Rigorous methods. Responsible translation. Enduring partnerships.</h2>
    <p>The strongest research moves fluently between theory and practice. My work combines methodological depth, interdisciplinary collaboration, and sustained engagement with the people who will use—or be affected by—the resulting technology.</p>
    <div class="research-actions"><a class="research-button research-button--primary" href="/projects/">Explore all projects</a><a class="research-button" href="/publications/">Read the research outputs</a></div>
  </section>
</div>
