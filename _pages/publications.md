---
layout: splash
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.2"
---

{% include base_path %}

## Publications overview

Decades of work across micromanipulation, robotics, and bioengineering are captured in the publications below. Each paper blends theory, instrumentation, and algorithm design to make automated microsystems more precise and reliable for translational research.

<div style="display: flex; flex-wrap: wrap; gap: 1.25em; margin: 1.5em 0;">
  <div style="flex: 1 1 220px; background: #f7f8fb; border-radius: 14px; padding: 1.25em 1.5em; box-shadow: 0 10px 25px rgba(0,0,0,0.08);">
    <h3 style="margin-top: 0;">Core themes</h3>
    <p style="margin-bottom: 0;">Dielectrophoresis, microfluidics, precision robotics, intelligent control.</p>
  </div>
  <div style="flex: 1 1 220px; background: #f7f8fb; border-radius: 14px; padding: 1.25em 1.5em; box-shadow: 0 10px 25px rgba(0,0,0,0.08);">
    <h3 style="margin-top: 0;">Lead venues</h3>
    <p style="margin-bottom: 0;">IEEE T-ASE, TBME, T-MECH, CASE, ICRA, AIM, ROBIO.</p>
  </div>
  <div style="flex: 1 1 220px; background: #f7f8fb; border-radius: 14px; padding: 1.25em 1.5em; box-shadow: 0 10px 25px rgba(0,0,0,0.08);">
    <h3 style="margin-top: 0;">Collaboration</h3>
    <p style="margin-bottom: 0;">Joint efforts with SUSTech, PolyU, HKU, and international robotics labs.</p>
  </div>
</div>

{% assign scholar_url = site.author.googlescholar %}
{% assign researchgate_url = site.author.researchgate %}
{% if scholar_url or researchgate_url %}
<div style="display: flex; flex-wrap: wrap; gap: 0.75em; margin-bottom: 2em;">
  {% if scholar_url %}
    <a class="btn" href="{{ scholar_url }}" target="_blank" rel="noopener">Google Scholar</a>
  {% endif %}
  {% if researchgate_url %}
    <a class="btn" href="{{ researchgate_url }}" target="_blank" rel="noopener">ResearchGate</a>
  {% endif %}
</div>
{% endif %}

---

## Full publication list

<div class="archive__items" style="margin-top: 1.5em;">
{% if site.publications and site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>The publication archive is being updated. Please check back soon.</p>
{% endif %}
</div>
