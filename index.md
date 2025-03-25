---
layout: default
title: Home
---

<div class="header-container">
  <h1>🌍 Ecosystem of Reviews for Carbon Pricing</h1>
</div>

Explore the Ecosystem of Reviews for Carbon Pricing, a centralized hub tracking research progress across key climate policy topics.
This project is designed for researchers and policymakers to prevent duplication, identify gaps, and accelerate evidence synthesis for effective carbon pricing policies.


<div class="content-wrapper">
  <!-- Interactive Graph Section -->
  <div class="graph-container">
    <iframe src="/ecosystem-reviews/carbon_pricing_graph.html" width="800" height="700" style="border:none;"></iframe>
  </div>

  <!-- Legend Section -->
  <div class="legend-box">
    <h3>Legend</h3>
    <div class="legend-item">
      <div class="color-dot finished"></div>
      <div class="legend-text">
        <strong>Finished:</strong> Effectiveness -  
        <a href="https://www.nature.com/articles/s41467-024-48512-w" target="_blank">Published Paper</a><br>
        <em>Contact: Niklas Döbbeling-Hildebrandt (<a href="mailto:niklas.doebbeling-hildebrandt@pik-potsdam.de">Email</a>)</em>
      </div>
    </div>

    <div class="legend-item">
      <div class="color-dot in-progress"></div>
      <div class="legend-text">
        <strong>In Progress:</strong>
      </div>
    </div>
    <div class="sub-items">
      <div>Innovation - <em>Contact: Trang Dong (<a href="mailto:trang.dong@uhasselt.be">Email</a>)</em></div>
      <div>Carbon Intensity - <em>Contact: XXXX (<a href="mailto:XXXX@example.com">Email</a>)</em></div>
      <div>Leakage - <em>Contact: YYYY (<a href="mailto:YYYY@example.com">Email</a>)</em></div>
      <div>Labour Market - <em>Contact: ZZZZ (<a href="mailto:ZZZZ@example.com">Email</a>)</em></div>
    </div>

    <div class="legend-item">
      <div class="color-dot needs-review"></div>
      <div class="legend-text">
        <strong>Needs Review:</strong> Distribution, Public Perception, Competitiveness
      </div>
    </div>
  </div>

  <!-- External Reviews Table -->
  <div class="table-container">
    <h2>External Systematic Reviews</h2>
    {% include reviews-table.html %}
    <p class="contribute-note">
      <strong>How to contribute?</strong>  
      Email <a href="mailto:xxx@gmail.com">xxx@gmail.com</a> to suggest additions.
    </p>
  </div>
</div>
