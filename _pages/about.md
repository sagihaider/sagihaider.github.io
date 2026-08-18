---
layout: page
title: about
permalink: /
hide_title: true
---

<div class="home-preview home-preview--editorial">
  <header class="editorial-hero">
    <div class="editorial-hero__copy">
      <p class="home-preview__eyebrow">Academic · Entrepreneur · AI advisor</p>
      <h1>Haider Raza</h1>
      <p class="editorial-hero__statement">Advancing adaptive and trustworthy artificial intelligence—from methodological research to responsible real-world impact.</p>
      <div class="home-preview__actions"><a class="home-preview__button home-preview__button--primary" href="/research/">Explore research</a><a class="home-preview__button" href="/projects/">View funded projects</a></div>
    </div>
    <figure class="editorial-hero__portrait"><img src="/assets/img/prof_pic.jpg" alt="Haider Raza" width="420" height="520"><figcaption>Senior Lecturer in Artificial Intelligence<br>University of Essex</figcaption></figure>
  </header>

  <section class="editorial-intro">
    <p class="home-preview__eyebrow">Profile</p>
    <h2>Research, education, and enterprise connected by one purpose.</h2>
    <div><p>I am an Indian-born British computer scientist, AI researcher, educator, and entrepreneur. I am a Senior Lecturer (Associate Professor) at the University of Essex, Founder of <a href="https://sensiwise.ai/">Sensiwise AI</a>, and AI Advisor to <a href="https://www.check4cancer.com/">Check4Cancer</a>.</p><p>My work develops reliable intelligent systems for changing, high-stakes environments and translates them into healthcare, neural engineering, environmental, and organisational applications.</p></div>
  </section>

  <section class="editorial-focus" aria-labelledby="editorial-focus-title">
    <div class="home-preview__section-heading"><p class="home-preview__eyebrow">Areas of work</p><h2 id="editorial-focus-title">A connected academic practice</h2></div>
    <div class="editorial-focus__grid">
      <a href="/research/"><span>01</span><h3>Research</h3><p>Adaptive learning, explainable AI, multimodal systems, and intelligent decision support.</p></a>
      <a href="/projects/"><span>02</span><h3>Enterprise</h3><p>Funded partnerships translating AI research into dependable products and processes.</p></a>
      <a href="/teaching/"><span>03</span><h3>Education</h3><p>Teaching, supervision, and mentoring across artificial intelligence and data science.</p></a>
      <a href="/people/"><span>04</span><h3>Leadership</h3><p>Interdisciplinary teams, research communities, professional service, and collaboration.</p></a>
    </div>
  </section>

  <section class="editorial-credentials">
    <div><p class="home-preview__eyebrow">Academic foundation</p><h2>From neural engineering to applied AI</h2></div>
    <p>I received my PhD in Computer Science from Ulster University in 2016 for research on adaptive learning in EEG-based brain–computer interfaces. Before and after my doctorate, I held academic and research positions across India, Ethiopia, Ulster, Swansea, and Essex.</p>
    <div class="editorial-credentials__badges"><span>PhD</span><span>FHEA</span><span>Senior Member, IEEE</span><a href="https://www.essex.ac.uk/people/razah72409">University profile ↗</a></div>
  </section>

  {% include home_preview_locked.liquid %}

  <section class="home-preview__locked" aria-labelledby="editorial-publications-title"><p class="home-preview__eyebrow">Selected work</p><h2 id="editorial-publications-title"><a href="/publications/">Selected publications</a></h2>{% include selected_papers.liquid %}</section>

  <section class="home-preview__social" aria-label="Social profiles">
    <div class="social">
      <div class="contact-icons">{% include social.liquid %}</div>
      <div class="contact-note">{{ site.contact_note }}</div>
    </div>
  </section>
</div>
