---
layout: page
title: projects
permalink: /projects/
description: A collection of ongoing and successfully completed funded projects.
nav: true
nav_order: 2
hide_title: true
---

{% assign current_projects = site.projects | where: "status", "current" | sort: "start_year" | reverse %}
{% assign completed_projects = site.projects | where: "status", "completed" | sort: "start_year" | reverse %}

<div class="project-directory">
  <header class="project-directory__hero">
    <p class="project-directory__eyebrow">Funded research &amp; knowledge exchange</p>
    <h1>Projects built through partnership</h1>
    <p class="project-directory__lede">A complete record of {{ site.projects.size }} funded, contract, consultancy, and collaborative programmes spanning healthcare, environmental intelligence, enterprise transformation, and public policy.</p>
    <div class="project-directory__stats" aria-label="Project summary">
      <div><strong>{{ site.projects.size }}</strong><span>All projects</span></div>
      <div><strong>{{ current_projects.size }}</strong><span>Current</span></div>
      <div><strong>{{ completed_projects.size }}</strong><span>Completed</span></div>
    </div>
  </header>

  <section class="project-controls" aria-label="Filter projects">
    <div class="project-filter-group" role="group" aria-label="Filter by status">
      <span>Status</span>
      <button type="button" class="is-active" data-project-status="all" aria-pressed="true">All</button>
      <button type="button" data-project-status="current" aria-pressed="false">Current</button>
      <button type="button" data-project-status="completed" aria-pressed="false">Completed</button>
    </div>
    <div class="project-filter-group" role="group" aria-label="Filter by research theme">
      <span>Theme</span>
      <button type="button" class="is-active" data-project-theme="all" aria-pressed="true">All themes</button>
      <button type="button" data-project-theme="healthcare" aria-pressed="false">Healthcare</button>
      <button type="button" data-project-theme="environment" aria-pressed="false">Environment</button>
      <button type="button" data-project-theme="enterprise" aria-pressed="false">Enterprise</button>
      <button type="button" data-project-theme="public-policy" aria-pressed="false">Public policy</button>
    </div>
    <p class="project-results" aria-live="polite"><strong>{{ site.projects.size }}</strong> projects shown</p>
  </section>

  <section class="project-group" data-project-group="current" aria-labelledby="current-projects-title">
    <div class="project-group__heading">
      <p class="project-directory__eyebrow">In progress</p>
      <h2 id="current-projects-title">Current &amp; recent programmes</h2>
    </div>
    <div class="project-grid">
      {% for project in current_projects %}
        {% include project_directory_card.liquid %}
      {% endfor %}
    </div>
  </section>

  <section class="project-group" data-project-group="completed" aria-labelledby="completed-projects-title">
    <div class="project-group__heading">
      <p class="project-directory__eyebrow">Track record</p>
      <h2 id="completed-projects-title">Completed programmes</h2>
    </div>
    <div class="project-grid">
      {% for project in completed_projects %}
        {% include project_directory_card.liquid %}
      {% endfor %}
    </div>
  </section>

  <div class="project-empty" hidden>
    <h2>No projects match these filters</h2>
    <p>Choose “All” or select another combination to see more projects.</p>
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const directory = document.querySelector(".project-directory");
    if (!directory) return;

    let selectedStatus = "all";
    let selectedTheme = "all";
    const cards = Array.from(directory.querySelectorAll(".project-card"));
    const groups = Array.from(directory.querySelectorAll(".project-group"));
    const results = directory.querySelector(".project-results strong");
    const emptyState = directory.querySelector(".project-empty");

    const updateButtons = function (buttons, activeButton) {
      buttons.forEach(function (button) {
        const active = button === activeButton;
        button.classList.toggle("is-active", active);
        button.setAttribute("aria-pressed", active ? "true" : "false");
      });
    };

    const applyFilters = function () {
      let visibleCount = 0;
      cards.forEach(function (card) {
        const statusMatch = selectedStatus === "all" || card.dataset.status === selectedStatus;
        const themeMatch = selectedTheme === "all" || card.dataset.theme === selectedTheme;
        const visible = statusMatch && themeMatch;
        card.hidden = !visible;
        if (visible) visibleCount += 1;
      });

      groups.forEach(function (group) {
        group.hidden = !group.querySelector(".project-card:not([hidden])");
      });

      results.textContent = visibleCount;
      emptyState.hidden = visibleCount !== 0;
    };

    const statusButtons = Array.from(directory.querySelectorAll("[data-project-status]"));
    statusButtons.forEach(function (button) {
      button.addEventListener("click", function () {
        selectedStatus = button.dataset.projectStatus;
        updateButtons(statusButtons, button);
        applyFilters();
      });
    });

    const themeButtons = Array.from(directory.querySelectorAll("[data-project-theme]"));
    themeButtons.forEach(function (button) {
      button.addEventListener("click", function () {
        selectedTheme = button.dataset.projectTheme;
        updateButtons(themeButtons, button);
        applyFilters();
      });
    });
  });
</script>
