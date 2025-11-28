---
layout: splash
title: "Current research"
permalink: /portfolio/
author_profile: true
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.2"
---

{% include base_path %}

## Research focus

Kaicheng Huang develops electric-field based micromanipulation platforms that couple robotics, control, and microfluidics to achieve reliable cell and droplet handling. The projects below highlight how automated planning, machine vision, and high-precision actuation converge to deliver robust lab-on-chip workflows.

---

## Automated DEP platform

**Automatic Cell Manipulation and Patterning System using Dielectrophoresis (DEP)** leverages a relay-controlled microchip to energize dot-electrodes individually, enabling both precise particle transport and rapid pattern generation. Optimization strategies, path planning, and closed-loop vision controllers ensure only the target particle settles on each electrode while nearby particles are repelled.


<div style="text-align: center; margin: 2em 0;">
  <img src="{{ site.baseurl }}/images/device.png" alt="Automated DEP platform" style="max-width: 720px; width: 90%; height: auto; border-radius: 12px; box-shadow: 0 8px 18px rgba(0,0,0,0.12);">
</div>


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
