---
layout: default
title: Find Your Collaborator
permalink: /find-your-collaborator/
---

<section class="fycollab">
  <h2>Find Your Collaborator</h2>
  <p>Contribute your details and browse others looking to collaborate on carbon pricing reviews.</p>

  <div class="tabs">
    <button class="tab-btn active" data-target="#tab-individuals">Individuals</button>
    <button class="tab-btn" data-target="#tab-teams">Existing Teams</button>
  </div>

  <!-- INDIVIDUALS TAB -->
  <div id="tab-individuals" class="tab-panel active">
    <h3>Submit (Individuals)</h3>
    <div class="embed-wrap">
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdk3hVpg7Xika-25qbiVxPHvIURtBxer2eHI7tvnoiahlWE9w/viewform?embedded=true"
              width="100%" height="1626" frameborder="0" marginheight="0" marginwidth="0"
              title="Individuals form">
        Loading…
      </iframe>
    </div>

    <h3>Browse (Individuals)</h3>
    <p class="note">This table displays the latest published responses. Use the filter/search in Google Sheets for advanced views.</p>
    <div class="embed-wrap">
      <iframe src="https://docs.google.com/spreadsheets/d/1HfqjOv6TXA5gV1Sg3DPxuErkqidtF7HL0Q2yPM5ZZlA/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=true"
              width="100%" height="800" frameborder="0" title="Individuals responses">
      </iframe>
    </div>
  </div>

  <!-- TEAMS TAB -->
  <div id="tab-teams" class="tab-panel">
    <h3>Submit (Teams)</h3>
    <div class="embed-wrap">
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfkB3p6XHlIfSkKmkUlERPZfphFM6U3jwWs07GpFv0NRxmN1A/viewform?embedded=true"
              width="100%" height="1268" frameborder="0" marginheight="0" marginwidth="0"
              title="Teams form">
        Loading…
      </iframe>
    </div>

    <h3>Browse (Teams)</h3>
    <p class="note">This table displays the latest published responses. Use the filter/search in Google Sheets for advanced views.</p>
    <div class="embed-wrap">
      <iframe src="https://docs.google.com/spreadsheets/d/1TPWt_qw8WN7On_nFc0pHo2zBI_DKnbS9oLc-5AMIrmM/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=true"
              width="100%" height="800" frameborder="0" title="Teams responses">
      </iframe>
    </div>
  </div>

  <details class="privacy">
    <summary>Privacy & Moderation</summary>
    <p>By submitting, you consent to display of the information you provide on this page. Please avoid sharing sensitive personal data. If you want an entry edited or removed, contact <a href="mailto:stephan.bruns@uhasselt.be">stephan.bruns@uhasselt.be</a> or <a href="mailto:jan.minx@pik-potsdam.de">jan.minx@pik-potsdam.de</a>.</p>
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
