---
layout: default
title: Find Your Collaborator
permalink: /find-your-collaborator/
---

<section class="fycollab">
  <h2>Find Your Collaborator</h2>
  <p>Browse collaborators and teams below. To add yourself or your team, use the buttons to open the form in a new tab.</p>

  <!-- SLIDE DECK (PDF) -->
  <div class="slide-wrap">
    <div class="slide-aspect">
      <object
        data="{{ '/assets/slides/contributing.pdf#page=1&zoom=125&toolbar=0&navpanes=0&scrollbar=0' | relative_url }}"
        type="application/pdf"
        aria-label="Contributing to the ecosystem of reviews - slide deck">
        <p>Your browser can’t display PDFs. <a href="{{ '/assets/slides/contributing.pdf' | relative_url }}" target="_blank" rel="noopener">Open the slides (PDF)</a>.</p>
      </object>
    </div>
    <div class="slide-actions">
      <a class="btn" href="{{ '/assets/slides/contributing.pdf' | relative_url }}" target="_blank" rel="noopener">Open slides (PDF)</a>
      <a class="btn ghost" href="{{ '/assets/slides/contributing.pdf' | relative_url }}" download>Download</a>
    </div>
  </div>

  <div class="tabs">
    <button class="tab-btn active" data-target="#tab-individuals">Individuals</button>
    <button class="tab-btn" data-target="#tab-teams">Existing Teams</button>
  </div>

  <!-- INDIVIDUALS TAB -->
  <div id="tab-individuals" class="tab-panel active">
    <div class="cta">
      <a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSdk3hVpg7Xika-25qbiVxPHvIURtBxer2eHI7tvnoiahlWE9w/viewform" target="_blank" rel="noopener">➕ Submit Individual Entry</a>
    </div>

    <h3>Browse (Individuals)</h3>
    <div class="embed-wrap">
      <iframe
        src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSfl6_UQ-9iKiRE7KKybBakut09l3JBKs6ZyW9yLHF_gLX8eWL3QWuCHUZGHSArNKnv6pxxYqSBr-zl/pubhtml?gid=1319926747&single=true&widget=true&headers=false"
        width="100%" height="800" frameborder="0" title="Individuals responses" loading="lazy">
      </iframe>
    </div>
  </div>

  <!-- TEAMS TAB -->
  <div id="tab-teams" class="tab-panel">
    <div class="cta">
      <a class="btn" href="https://docs.google.com/forms/d/e/1FAIpQLSfkB3p6XHlIfSkKmkUlERPZfphFM6U3jwWs07GpFv0NRxmN1A/viewform" target="_blank" rel="noopener">➕ Submit Team Entry</a>
    </div>

    <h3>Browse (Existing Teams)</h3>
    <div class="embed-wrap">
      <iframe
        src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS2E5A8uKZcCqP4PV1ZZ0wFinUwLqRoZqJD4ebCKpZhFAoF-ENRRjo6-wXtiMiQeoJIJt4reOShtY8W/pubhtml?widget=true&headers=false"
        width="100%" height="800" frameborder="0" title="Teams responses" loading="lazy">
      </iframe>
    </div>
  </div>

  <details class="privacy">
    <summary>Privacy & Moderation</summary>
    <p>By submitting, you consent to display of the information you provide on this page. Please avoid sharing sensitive personal data. If you want an entry edited or removed, contact <strong>Stephan Bruns</strong> <a href="mailto:stephan.bruns@uhasselt.be">stephan.bruns@uhasselt.be</a> and/or <strong>Jan Minx</strong> <a href="mailto:jan.minx@pik-potsdam.de">jan.minx@pik-potsdam.de</a>.</p>
  </details>
</section>

<script>
  // Simple tabs
  document.addEventListener('DOMContentLoaded', function () {
    const btns = document.querySelectorAll('.tab-btn');
    const panels = document.querySelectorAll('.tab-panel');
    btns.forEach(btn => {
      btn.addEventListener('click', () => {
        btns.forEach(b => b.classList.remove('active'));
        panels.forEach(p => p.classList.remove('active'));
        btn.classList.add('active');
        const target = document.querySelector(btn.dataset.target);
        if (target) target.classList.add('active');
      });
    });
  });
</script>
