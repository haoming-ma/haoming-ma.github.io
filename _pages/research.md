---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---
<!-- ▸ Introductory video -->
<video controls width="100%" playsinline>
  <source src="{{ '/images/Geosystem_video.mp4' | relative_url }}" type="video/mp4">
  Your browser does not support the video tag.
</video>

My research systematically incorporates machine-learning algorithms and multiscale measurement techniques for geo-energy system analysis, coupling numerical methods with techno-economic analysis and life cycle assessment to enable the industrial-scale deployment of sustainable geo-energy extraction.

<details class="accordion">
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
