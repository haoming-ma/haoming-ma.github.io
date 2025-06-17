---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---
My research systematically incorporates machine-learning algorithms and multiscale measurement techniques for geo-energy system analysis, coupling numerical methods with techno-economic analysis and life-cycle assessment to enable the industrial-scale deployment of sustainable geo-energy extraction.


<!-- ▸ Video + “Research Keywords” figure, equal heights & aligned captions -->
<div style="
     display:grid;
     grid-template-columns:repeat(auto-fit,minmax(360px,1fr));
     gap:1.5rem;
     justify-items:center;
     align-items:start;
">

  <!-- Video -->
  <figure style="margin:0; text-align:center;">
    <video autoplay loop muted playsinline
           style="display:block; width:100%; height:300px;
                  object-fit:contain; object-position:center;">
      <source src="{{ '/images/Geosystem_video.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption style="margin-top:0.5rem;"><em>Complex Geo-Energy System Demonstration</em></figcaption>
  </figure>

  <!-- Image -->
  <figure style="margin:0; text-align:center;">
    <img src="{{ '/images/Research Keywords.jpg' | relative_url }}"
         alt="Research Keywords"
         style="display:block; width:100%; height:280px;
                object-fit:contain; object-position:center;">
    <figcaption style="margin-top:0.5rem;"><em>Research Keywords</em></figcaption>
  </figure>

</div>


<details class="accordion">
  <summary><strong>Cluster 1: Integrated System Modeling Tool </strong></summary>
  <p>Put your detailed content for Theme 1 here…</p>
</details>

<details class="accordion">
  <summary><strong>Cluster 2: Measurement-Informed Life Cycle Assessment </strong></summary>
  <p>Put your detailed content for Theme 2 here…</p>
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
