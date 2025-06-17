---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---
<!-- ▸ Introductory video with caption underneath -->
<figure style="width:50%; margin:auto; text-align:center;">
  <video autoplay loop muted playsinline style="width:100%; height:auto;">
    <source src="{{ '/images/Geosystem_video.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption style="display:block; margin-top:0.5rem; text-align:center;">
    <em>Complex Geo-Energy System Demonstration</em>
  </figcaption>
</figure>

My research systematically incorporates machine-learning algorithms and multiscale measurement techniques for geo-energy system analysis, coupling numerical methods with techno-economic analysis and life-cycle assessment to enable the industrial-scale deployment of sustainable geo-energy extraction.

<!-- ▸ Side-by-side figures with truly centered captions -->
<div style="display:flex; gap:1rem; justify-content:center; flex-wrap:wrap;">

  <figure style="flex:1; min-width:250px; text-align:center;">
    <img src="{{ '/images/research-area.jpg' | relative_url }}"
         alt="Research Areas"
         style="max-width:100%; height:auto; display:block; margin:0 auto;">
    <figcaption style="margin-top:0.5rem; text-align:center;">
      <em>Research Areas</em>
    </figcaption>
  </figure>

  <figure style="flex:1; min-width:250px; text-align:center;">
    <img src="{{ '/images/Research Keywords.jpg' | relative_url }}"
         alt="Research Keywords"
         style="max-width:100%; height:auto; display:block; margin:0 auto;">
    <figcaption style="margin-top:0.5rem; text-align:center;">
      <em>Research Keywords</em>
    </figcaption>
  </figure>

</div>


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
