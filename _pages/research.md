---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---

My group develops AI‑enabled modelling tool‑kits that integrate reservoir
simulation, geostatistics, multi‑scale emission data, and TEA/LCA to resolve
the techno‑economic and environmental trade‑offs of geo‑energy systems.

<details class="accordion" open>
  <summary>Subsurface CO₂ Utilization & Sequestration</summary>

  <p>Put your detailed content here …</p>
</details>

<details class="accordion">
  <summary>Methane Emissions in Oil‑and‑Gas Supply Chains</summary>

  <p>More content …</p>
</details>

<details class="accordion">
  <summary>Hydrogen Production & Underground Storage</summary>

  <p>More content …</p>
</details>

<script>
/* ╔════════════════════════════════════════════╗
   ║  keep exactly one <details.accordion> open ║
   ╚════════════════════════════════════════════╝ */
document.addEventListener('DOMContentLoaded', () => {
  const items = document.querySelectorAll('details.accordion');
  items.forEach((item) => {
    item.addEventListener('toggle', () => {
      if (item.open) {                     // this one was just opened
        items.forEach((other) => {
          if (other !== item) other.open = false;  // close the rest
        });
      }
    });
  });
});
</script>
