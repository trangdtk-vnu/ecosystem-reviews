---
layout: default
title: Home
---

<div class="home-header">
  <h1>🌍 Ecosystem of Reviews for Carbon Pricing</h1>
  <p class="tagline">Tracking research progress for effective climate policy</p>
</div>

<div class="intro-card">
  <p>Explore our centralized hub for systematic reviews on carbon pricing. Designed for researchers and policymakers, this platform helps:</p>
  <ul class="feature-list">
    <li>📌 Prevent research duplication</li>
    <li>🔍 Identify critical evidence gaps</li>
    <li>⚡ Accelerate policy-relevant synthesis</li>
  </ul>
</div>

<!-- Map Section -->
<div class="map-section">
  <div class="graph-container">
    <iframe src="/ecosystem-reviews/carbon_pricing_graph.html" width="800" height="700" style="border:none;"></iframe>
  </div>

  <!-- Legend positioned below map -->
  <div class="legend-box">
    <h3><i class="fas fa-key"></i> Legend</h3>
    <div class="legend-items">
      <div class="legend-item">
        <div class="color-dot finished"></div>
        <div class="legend-text">
          <strong>Completed:</strong> Effectiveness -  
          <a href="https://www.nature.com/articles/s41467-024-48512-w" target="_blank">Published Paper</a>
          <div class="contact-badge">
            <i class="fas fa-envelope"></i> Niklas Döbbeling-Hildebrandt
          </div>
        </div>
      </div>

      <div class="legend-item">
        <div class="color-dot in-progress"></div>
        <div class="legend-text">
          <strong>In Progress:</strong>
          <div class="sub-items">
            <div>Innovation <span class="contact-badge"><i class="fas fa-envelope"></i> Trang Dong</span></div>
            <div>Carbon Intensity <span class="contact-badge"><i class="fas fa-envelope"></i> XXXX</span></div>
            <div>Leakage <span class="contact-badge"><i class="fas fa-envelope"></i> YYYY</span></div>
            <div>Labour Market <span class="contact-badge"><i class="fas fa-envelope"></i> ZZZZ</span></div>
          </div>
        </div>
      </div>

      <div class="legend-item">
        <div class="color-dot needs-review"></div>
        <div class="legend-text">
          <strong>Needs Review:</strong> Distribution, Public Perception, Competitiveness
        </div>
      </div>
    </div>
  </div>
</div>

<!-- External Reviews Section -->
<div class="reviews-section">
  <h2><i class="fas fa-table"></i> External Systematic Reviews</h2>
  <div class="table-container">
    {% include reviews-table.html %}
  </div>
  <div class="cta-box">
    <p>Have a review to contribute?</p>
    <a href="mailto:xxx@gmail.com" class="cta-button">
      <i class="fas fa-paper-plane"></i> Suggest an Addition
    </a>
  </div>
</div>
