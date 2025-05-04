---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---

My group develops AI-enabled modelling tool-kits that integrate reservoir
simulation, geostatistics, multi-scale emission data, and TEA/LCA to resolve
the techno-economic and environmental trade-offs of geo-energy systems.

<details class="accordion" open>
  <summary><strong>Theme 1: Subsurface CO₂ Utilization &amp; Sequestration</strong></summary>
  <p>Put your detailed content for Theme 1 here…</p>
</details>

<details class="accordion">
  <summary><strong>Theme 2: Methane Emissions in Oil-and-Gas Supply Chains</strong></summary>
  <p>Put your detailed content for Theme 2 here…</p>
</details>

<details class="accordion">
  <summary><strong>Theme 3: Hydrogen Production & Underground Storage</strong></summary>
  <p>Put your detailed content for Theme 3 here…</p>
</details>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const accordions = document.querySelectorAll('details.accordion');
  accordions.forEach((acc) => {
    acc.addEventListener('toggle', () => {
      if (acc.open) {
        accordions.forEach((other) => {
          if (other !== acc) other.open = false;
        });
      }
    });
  });
});
</script>
