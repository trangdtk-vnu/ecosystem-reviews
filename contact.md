---
layout: default
title: Contact
permalink: /contact/
---

# 📬 Contact Us

<div class="contact-container">
  <div class="contact-form">
    <h2>Send a Message</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" name="name" placeholder="Your name" required>
      </div>
      
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" name="email" placeholder="your.email@example.com" required>
      </div>
      
      <div class="form-group">
        <label for="message">Your Message</label>
        <textarea name="message" placeholder="How can we help?" required></textarea>
      </div>
      
      <button type="submit" class="submit-btn">
        <span class="btn-text">Send Message</span>
        <span class="btn-icon">→</span>
      </button>
    </form>
  </div>

  <div class="contact-info">
    <h2>Direct Contacts</h2>
    <div class="contact-card">
      <div class="contact-icon">📧</div>
      <div>
        <h3>Email</h3>
        <p><a href="mailto:stephan.bruns@uhasselt.be">stephan.bruns@uhasselt.be</a></p>
      </div>
    </div>
    
    <div class="contact-card">
      <div class="contact-icon">🏢</div>
      <div>
        <h3>Institution</h3>
        <p>Hasselt University</p>
      </div>
    </div>
    
    <div class="contact-card">
      <div class="contact-icon">🌍</div>
      <div>
        <h3>Location</h3>
        <p>Hasselt, Belgium</p>
      </div>
    </div>
  </div>
</div>
