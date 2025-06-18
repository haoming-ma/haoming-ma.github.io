---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---
My research systematically incorporates machine-learning algorithms and multiscale measurement techniques for geo-energy system analysis, coupling numerical methods with techno-economic analysis and life-cycle assessment to enable the industrial-scale deployment of sustainable geo-energy extraction.


<!-- ▸ Video + “Research Keywords” figure, equal heights & perfectly centered captions -->
<div style="
     display:grid;
     grid-template-columns:repeat(auto-fit,minmax(360px,1fr));
     gap:1.5rem;
     justify-items:center;   /* center each figure inside its grid cell */
     align-items:start;
">

  <!-- Video -->
  <figure style="
        margin:0;
        display:flex;              /* stack media + caption vertically */
        flex-direction:column;
        align-items:center;        /* horizontally center child elements */
  ">
    <video autoplay loop muted playsinline
           style="width:100%; height:300px; object-fit:contain; object-position:center;">
      <source src="{{ '/images/Geosystem_video.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption style="margin-top:0.5rem; text-align:center;">
      <em>Complex Geo-Energy System Demonstration</em>
    </figcaption>
  </figure>

  <!-- Image -->
  <figure style="
        margin:0;
        display:flex;
        flex-direction:column;
        align-items:center;
  ">
    <img src="{{ '/images/Research Keywords.jpg' | relative_url }}"
         alt="Research Keywords"
         style="width:100%; height:280px; object-fit:contain; object-position:center;">
    <figcaption style="margin-top:0.5rem; text-align:center;">
      <em>Keywords</em>
    </figcaption>
  </figure>

</div>



<details class="accordion">
  <summary><strong>Cluster 1: Integrated System Modeling Tool</strong></summary>
     
  <p>I lead efforts to develop a Geo-Energy System Modeling (GESM) toolkit that addresses two key knowledge gaps: the disconnect between simulations of surface and subsurface engineering activities and the lack of integration between techno-economic analysis (TEA) and life-cycle assessment (LCA). By constructing data-enriched reduced-order models (ROMs) with machine-learning algorithms that accurately predict reservoir performance, I combine these ROMs with process-level mass and energy balance estimates to create an integrated platform for unified TEA LCA evaluation. This end-to-end integration quantifies economic and environmental outcomes concurrently, clarifying the socio-economic trade-offs associated with emerging innovations. The GESM toolkit has already been deployed at industrial scale to assess subsurface CO2 utilization and storage processes, including CO2-enhanced oil recovery (CO2-EOR), CO2-enhanced shale-gas recovery (CO2-ESGR), and CO2-enhanced coalbed methane recovery (CO2-ECBM), as well as enhanced geothermal systems and underground hydrogen storage.</p>
     
<!-- Cluster-1 figure, centered with caption -->
<figure style="text-align:center; margin:1rem 0;">
  <img src="{{ '/images/cluster1_fig.jpg' | relative_url }}"
       alt="Cluster 1 diagram"
       style="max-width:80%; height:auto; display:block; margin:0 auto;">
  <figcaption style="margin-top:0.5rem;">
    <em>Schematic Overview of GESM</em>
  </figcaption>
</figure>



</details>



<details class="accordion">
  <summary><strong>Cluster 2: Measurement-Informed Life Cycle Assessment</strong></summary>

  <!-- Cluster-2 figure, left-aligned -->
  <img src="{{ '/images/cluster2_fig.jpg' | relative_url }}"
       alt="Cluster 2 diagram"
       style="display:block; max-width:80%; height:auto; margin:1rem 0;">

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
