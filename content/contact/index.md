---
title: "Contact Me"
layout: "single"  # Use the default single layout instead of custom contact layout
---

<form action="https://formspree.io/f/xvgojpag" method="POST" class="contact-form">
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" name="name" id="name" required>
  </div>
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" name="email" id="email" required>
  </div>
  <div class="form-group">
    <label for="subject">Subject:</label>
    <input type="text" name="subject" id="subject" required>
  </div>
  <div class="form-group">
    <label for="message">Message:</label>
    <textarea name="message" id="message" rows="5" required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>

<style>
.contact-form {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
}
.form-group {
  margin-bottom: 20px;
}
label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 8px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}
textarea {
  resize: vertical;
}
button {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
}
button:hover {
  background-color: #0056b3;
}
</style>