---
layout: default
title: Contact
permalink: /contact/
---

# Contact

<style>
  form {
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 500px;
    margin: 0 auto;
  }
  label {
    font-size: 14px;
    color: #333;
    margin-bottom: 5px;
    display: block;
  }
  input, textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 14px;
    margin-bottom: 15px;
    box-sizing: border-box;
  }
  textarea {
    resize: vertical;
    height: 150px;
  }
  button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 4px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  button:hover {
    background-color: #45a049;
  }
</style>

<form action="https://formspree.io/f/yourformid" method="POST">
  <label for="name">Name:</label>
  <input type="text" name="name" required>

  <label for="email">Email:</label>
  <input type="email" name="email" required>

  <label for="message">Message:</label>
  <textarea name="message" required></textarea>

  <button type="submit">Send</button>
</form>

---

Feel free to reach out!

📧 **Email:** [email@example.com](mailto:stephan.bruns@uhasselt.be)  
🏢 **Institution:** Hasselt University  
🌍 **Location:** Hasselt, Belgium
