---
layout: archive
title:  "Research"
permalink: /research/
author_profile: true
---
My research systematically incorporates machine-learning algorithms and multiscale measurement techniques for developing geo-energy system modeling and analysis tools, coupling numerical methods with techno-economic analysis (TEA) and life cycle assessment (LCA) to enable the industrial-scale deployment of sustainable geo-energy extraction.


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
  <summary><strong>Theme&nbsp;1: Integrated Geo-Energy System Modeling and Analysis</strong></summary>

  <p>
    I lead efforts to develop a Geo-Energy System Modeling&nbsp;(GESM) toolkit that addresses two key knowledge gaps: the disconnect between simulations of surface and subsurface engineering activities and the lack of integration between TEA and LCA. By constructing data-enriched reduced-order models&nbsp;(ROMs) using machine learning algorithms that accurately predict reservoir performance, I combine these ROMs with process-level mass and energy balance estimates to create an integrated platform for unified the TEA and LCA evaluations. This end-to-end integration quantifies economic and environmental outcomes concurrently, clarifying the socio-economic trade-offs of the emerging geo-energy technological innovations. The GESM toolkit has already been deployed at industrial scale to assess geological carbon utilization and storage activities, such as CO<sub>2</sub>-enhanced oil recovery&nbsp;(CO<sub>2</sub>-EOR), CO<sub>2</sub>-enhanced shale-gas recovery&nbsp;(CO<sub>2</sub>-ESGR), and CO<sub>2</sub>-enhanced coal-bed-methane recovery&nbsp;(CO<sub>2</sub>-ECBM), as well as enhanced geothermal systems and underground hydrogen storage.
  </p>
<!-- Cluster-1 figure, centred with caption -->
<figure style="margin:1rem auto; max-width:80%; text-align:center;">
  <img src="{{ '/images/cluster1_fig.jpg' | relative_url }}"
       alt="Schematic Overview of GESM"
       style="width:100%; height:auto; display:block;">
  <figcaption style="margin-top:0.5rem; text-align:center;">
    <em>Schematic Overview of GESM</em>
  </figcaption>
</figure>
</details>






<details class="accordion">
  <summary><strong>Theme 2: Geospatial Measurement-Informed Carbon Accounting and Management</strong></summary>
  <p>I developed a Geospatial Measurement-Informed Life Cycle Assessment (GMLCA) framework that leverages both bottom-up and top-down methane emission data acquired from multiscale remote sensing techniques. Addressing the communication gap between measurement-based methane inventories and national greenhouse gas emission inventories (GHGEI), this framework reconciles discrepancies by explicitly accounting for the intermittent emissions from super-emitters captured in top-down aerial surveys of global LNG supply chains. By applying GMLCA, I concluded that the GHG emissions of the international LNG trade were underestimated by up to 33% in 2023. This framework is now being extended to the blue hydrogen supply chains associated with steam methane reforming (SMR).</p>
  
<!-- Cluster-2 figure, centred with caption -->
<figure style="margin:1rem auto; max-width:80%; text-align:center;">
  <img src="{{ '/images/cluster2_fig.jpg' | relative_url }}"
       alt="Schematic Overview of GMLCA"
       style="width:100%; height:auto; display:block;">
  <figcaption style="margin-top:0.5rem; text-align:center;">
    <em>Schematic Overview of GMLCA</em>
  </figcaption>
</figure>
</details>




