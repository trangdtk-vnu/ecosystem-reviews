---
layout: default
title: Home
---

<div class="header-container">
  <h1>🌍 Ecosystem of Reviews for Carbon Pricing</h1>
</div>

<p>
Explore the Ecosystem of Reviews for Carbon Pricing, a centralised hub tracking research progress across key climate policy topics.
This project is designed for researchers and policymakers to prevent duplication, identify gaps, and accelerate evidence synthesis for effective carbon pricing policies.
</p>

<!-- Graph -->
<div class="graph-container">
  <iframe src="/ecosystem-reviews/carbon_pricing_graph.html" width="100%" height="700"></iframe>
</div>

<!-- Shared Width Wrapper -->
<div class="stacked-container">
  
  <!-- Legend -->
  <div class="legend-box">
    <h3>Legend</h3>
    <div class="legend-item">
      <span class="color-dot finished"></span>
      <strong>Finished:</strong> Effectiveness –  
      <a href="https://www.nature.com/articles/s41467-024-48512-w" target="_blank">Published Paper</a><br>
      <em>Contact: Niklas Döbbeling-Hildebrandt (<a href="mailto:niklas.doebbeling-hildebrandt@pik-potsdam.de">Email</a>)</em>
    </div>
    <div class="legend-item">
      <span class="color-dot in-progress"></span> In Progress
    </div>
    <div class="legend-item">
      <span class="color-dot needs-review"></span> Needs Review
    </div>
  </div>

  <!-- Table -->
  <div class="table-container">
    <h2>External Systematic Reviews</h2>
    {% include reviews-table.html %}
    <p class="contribute-note">
      <strong>How to contribute?</strong>  
      Email <a href="mailto:xxx@gmail.com">xxx@gmail.com</a> to suggest additions.
    </p>
  </div>
</div>
