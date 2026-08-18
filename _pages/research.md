---
layout: page
permalink: /research/
title: research
description: Adaptive and applied artificial intelligence research
nav: true
nav_order: 4
hide_title: true
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
    <a href="#adaptive-ai"><span>01</span><strong>Adaptive &amp; trustworthy AI</strong><small>Methods for changing data and environments</small><em class="research-map__cue">View section</em></a>
    <a href="#health-ai"><span>02</span><strong>AI for health</strong><small>Computer vision, triage and clinical decisions</small><em class="research-map__cue">View section</em></a>
    <a href="#applied-ai"><span>03</span><strong>Applied &amp; responsible AI</strong><small>Environment, enterprise and public value</small><em class="research-map__cue">View section</em></a>
    <a href="#neural-engineering"><span>04</span><strong>Neural engineering</strong><small>EEG, MEG and brain–computer interfaces</small><em class="research-map__cue">View section</em></a>
  </nav>

  <section class="research-section" id="methodological-foundations">
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
      <details class="research-cluster" id="adaptive-ai" open>
        <summary><span class="cluster-index">01</span><span class="cluster-title"><strong>Adaptive &amp; trustworthy AI</strong><small>Domain adaptation, dataset-shift detection and efficient visual intelligence</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <div class="contribution-block">
            <h3>Domain adaptation for non-stationary systems</h3>
            <p>My research develops learning methods that remain effective when the statistical properties of data change between training and deployment. I have designed adaptive mechanisms that update a model’s understanding as new patterns emerge, improving resilience across subjects, devices, sessions, and real-world operating conditions.</p>
            <p>This work has produced active and passive adaptation approaches, ensemble-learning frameworks, and methods for handling covariate shift in online systems {% cite raza2014adaptive raza2015learning raza2016adaptive raza2018covariate raza2019covariate %}.</p>
          </div>
          <div class="contribution-block">
            <h3>Change and covariate-shift detection</h3>
            <p>I contributed methods for identifying changes in a data distribution in both online and retrospective settings. These tests help determine when a deployed model can no longer rely on its original assumptions and when adaptation or retraining is required {% cite raza2013ewma raza2013dataset raza2015ewma %}.</p>
          </div>
          <div class="contribution-block">
            <h3>Efficient and explainable vision transformers</h3>
            <p>With my doctoral researchers, I investigate lightweight Vision Transformers that can be trained without dependence on generic ImageNet weights. The work focuses on data-efficient learning, interpretability, robustness, and specialist architectures for medical images and other resource-constrained domains {% cite ali2024explainable ali2025optimising ali2026aistats %}.</p>
          </div>
          <div class="contribution-block">
            <h3>Trustworthy, agentic and multimodal AI</h3>
            <p>My current work extends these foundations to human-centred systems combining language, vision, organisational knowledge, and decision support. The emphasis is on explainability, fairness, dependable evaluation, and responsible adoption rather than capability alone.</p>
          </div>
          <div class="research-tags" aria-label="Topics"><span>Domain adaptation</span><span>Dataset shift</span><span>Explainable AI</span><span>Vision transformers</span><span>Multimodal AI</span></div>
        </div>
      </details>

      <details class="research-cluster" id="health-ai">
        <summary><span class="cluster-index">02</span><span class="cluster-title"><strong>AI for health &amp; clinical decisions</strong><small>Earlier diagnosis, intelligent triage and explainable medical vision</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <div class="contribution-block">
            <h3>Skin-cancer detection</h3>
            <p>In partnership with Check4Cancer, I led research to develop an AI engine for melanoma detection using dermoscopic and digital images collected over two decades. The work advances explainable computer vision and efficient Vision Transformers, with particular attention to robustness and reducing false-negative decisions in a mobile diagnostic pathway {% cite islam2024leveraging islam2024unlocking islam2026advancing %}.</p>
          </div>
          <div class="contribution-block">
            <h3>AI-assisted NHS patient triage</h3>
            <p>With Provide Community, our team designed, developed, and deployed a Smart Referral System for musculoskeletal services. The architecture supports real-time triage, directs patients to appropriate clinical pathways, standardised referral routes across 12 clinical services, and reduced decisions that previously took weeks or months to a matter of hours. The partnership received Best Associate and Best Academic recognition.</p>
          </div>
          <div class="contribution-block">
            <h3>Forensic dentistry and medical imaging</h3>
            <p>I collaborate internationally on AI for dental radiography, periodontology, and forensic dentistry. Contributions include age and sex estimation from molar and panoramic radiographs, mental-foramen detection and segmentation, dental-disease classification, and the development of structured imaging datasets {% cite raza2024segmentation raza2024optimizing malik2026multimodel %}.</p>
          </div>
          <div class="contribution-block">
            <h3>Predictive health analytics</h3>
            <p>My wider health research includes intelligent clinical pathways, decision support using electronic health records, and population-health analysis. A longitudinal study linked accelerometer and health-record data to identify gestational and postnatal factors associated with physical activity in 12-month-old infants {% cite raza2017identification %}.</p>
          </div>
          <div class="project-links" aria-label="Related health projects"><a href="/projects/KTP_C4C/">Skin cancer diagnosis <span>↗</span></a><a href="/projects/KTP_Provide/">NHS patient triage <span>↗</span></a><a href="/projects/KTP-Hurdle/">Data-driven healthcare <span>↗</span></a><a href="/projects/Royal-Society-IE/">Trustworthy medical AI <span>↗</span></a><a href="/projects/ESNEFT-Colchester-Hospital/">Clinical AI collaboration <span>↗</span></a></div>
        </div>
      </details>

      <details class="research-cluster" id="applied-ai">
        <summary><span class="cluster-index">03</span><span class="cluster-title"><strong>Applied &amp; responsible AI</strong><small>Environment, enterprise, engineering and public value</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <div class="contribution-block">
            <h3>Environment, agriculture and conservation</h3>
            <p>I apply machine learning, computer vision, graph methods, and connected sensing to forest-fire prediction, biodiversity monitoring, crop analysis, water and ecosystem wellbeing, and evidence-led policy. My contributions include IoT-based early-warning approaches and event-detection methods for environmental monitoring {% cite singh2022event singh2024graph pandey2023development %}.</p>
            <div class="project-links" aria-label="Related environment projects"><a href="/projects/GCRF-Forest-Fire/">Forest-fire prediction <span>↗</span></a><a href="/projects/KTP-RSPB/">Conservation technology <span>↗</span></a><a href="/projects/Contract-Alula/">AlUla smart city &amp; environment <span>↗</span></a><a href="/projects/ESRC-BLGDRC/">Data and public policy <span>↗</span></a></div>
          </div>
          <div class="contribution-block">
            <h3>Enterprise, engineering and operational AI</h3>
            <p>Through Knowledge Transfer Partnerships and collaborative R&amp;D, I translate research into dependable products and organisational processes. This includes intelligent construction planning with real-time information delivery, engineering and manufacturing analytics, logistics optimisation, revenue intelligence, generative AI, and assessment of organisational readiness for responsible adoption.</p>
            <p>The work combines technical development with knowledge exchange so that models are embedded into practical workflows, evaluated with domain experts, and capable of delivering sustained organisational value.</p>
            <div class="project-links" aria-label="Related enterprise projects"><a href="/projects/KTP_Mersea/">Construction intelligence <span>↗</span></a><a href="/projects/KTP-MEL/">Engineering analytics <span>↗</span></a><a href="/projects/KTP_Trunk/">Digital operations <span>↗</span></a><a href="/projects/KTP-Strom/">Industrial AI <span>↗</span></a><a href="/projects/KTP-Unisurge/">Manufacturing innovation <span>↗</span></a><a href="/projects/KTP-RevWise/">Revenue optimisation <span>↗</span></a><a href="/projects/East-AI-Studio/">Enterprise AI adoption <span>↗</span></a></div>
          </div>
        </div>
      </details>

      <details class="research-cluster" id="neural-engineering">
        <summary><span class="cluster-index">04</span><span class="cluster-title"><strong>Neural engineering &amp; brain–computer interfaces</strong><small>Adaptive learning for EEG, MEG, motor imagery and rehabilitation</small></span><span class="cluster-toggle" aria-hidden="true"></span></summary>
        <div class="cluster-content">
          <div class="contribution-block">
            <h3>Adaptive EEG-based BCI</h3>
            <p>I helped develop a covariate-shift detection test and adaptive learning algorithms for non-stationary EEG data {% cite raza2015ewma raza2016adaptive %}. I subsequently proposed a covariate-shift-estimation adaptive ensemble for motor-imagery BCI {% cite raza2019covariate %} and evaluated automatic frequency-band-selection methods for learning discriminative Common Spatial Pattern features {% cite raza2015optimising %}. The resulting online system has continued to support research in the BCI laboratory at Ulster University.</p>
          </div>
          <div class="contribution-block">
            <h3>Open MEG data and cognitive decoding</h3>
            <p>Our team released a public 306-channel MEG dataset recorded from 17 participants across hand, feet, subtraction, and word-generation imagery tasks, enabling wider development and comparison of MEG pattern-recognition methods {% cite rathee2021magnetoencephalography %}. International collaboration also produced new evidence on how numeracy and literacy are represented in the human brain {% cite nara2023decoding %}.</p>
          </div>
          <div class="contribution-block">
            <h3>Personalised stroke rehabilitation</h3>
            <p>With collaborators at IIT Kanpur, I contributed to a BCI-operated neurorehabilitation system for recovering finger movement after stroke. We developed cortico-muscular-coupling and EEG–EMG feature methods, integrated covariate-shift adaptation, and evaluated the system with healthy participants and stroke survivors {% cite chowdhury2019eeg chowdhury2017online chowdhury2018active %}.</p>
          </div>
          <div class="research-tags" aria-label="Topics"><span>EEG &amp; MEG</span><span>BCI</span><span>Motor imagery</span><span>Domain adaptation</span><span>Neurorehabilitation</span></div>
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

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const revealResearchSection = function () {
      const sectionId = decodeURIComponent(window.location.hash.slice(1));
      const target = sectionId ? document.getElementById(sectionId) : null;
      if (target && target.matches("details.research-cluster")) {
        target.open = true;
        window.requestAnimationFrame(function () {
          target.scrollIntoView({ block: "start" });
        });
      }
    };

    document.querySelectorAll(".research-map a[href^='#']").forEach(function (link) {
      link.addEventListener("click", function () {
        const target = document.querySelector(link.getAttribute("href"));
        if (target && target.matches("details.research-cluster")) target.open = true;
      });
    });

    revealResearchSection();
    window.addEventListener("hashchange", revealResearchSection);
  });
</script>
