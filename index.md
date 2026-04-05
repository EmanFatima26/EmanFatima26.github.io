---
layout: default
title: Home
---

<div style="text-align: center;">
  <h1 style="font-size: 2.5em;">✨ Welcome to My Blog! ✨</h1>
  <p style="font-size: 1.2em;">My name is **Eman Fatima** and I am a Computer Engineering student sharing my journey. 🌸</p>
</div>

### 🎀 Quick Links
[🏠 Home](/) &nbsp; [📖 About Me](/about) &nbsp; [💌 Contact](/contact) &nbsp; [✍️ New Post](https://github.com)
{: .nav-buttons}

---

### ✨ My Recent Posts
<ul>
  {% for post in site.posts %}
    <li style="list-style: '🌸 '; margin-bottom: 10px;">
      <a href="{{ post.url }}" style="color: #d4a5a5; font-weight: bold; font-size: 1.1em;">{{ post.title }}</a> 
      <br><small style="color: #999;">Published: {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% else %}
    <p style="color: #999; font-style: italic;">No posts yet! Click "New Post" above to start writing. ✨</p>
  {% endfor %}
</ul>

<style>
  /* Aesthetic "Girlie" Vibe CSS */
  body {
    background-color: #fffafb; /* Soft blush background */
    color: #5d4d50;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  h1, h2, h3 {
    color: #d4a5a5 !important; /* Dusty Rose */
    font-weight: 300;
  }

  /* Navigation Button Styling */
  .nav-buttons a {
    background-color: #f3d1d1;
    color: #7d5a5a !important;
    padding: 12px 20px;
    border-radius: 25px; /* Pill shape */
    text-decoration: none;
    font-weight: 600;
    display: inline-block;
    margin: 8px;
    transition: all 0.3s ease;
    box-shadow: 0 4px 6px rgba(212, 165, 165, 0.2);
  }

  .nav-buttons a:hover {
    background-color: #d4a5a5;
    color: white !important;
    transform: translateY(-3px);
    box-shadow: 0 6px 12px rgba(212, 165, 165, 0.4);
  }

  /* Footer or Email Link Style */
  .contact-footer {
    text-align: center;
    margin-top: 50px;
    font-size: 0.9em;
    color: #d4a5a5;
  }
</style>

<div class="contact-footer">
  🎀 Reach me at: <a href="mailto:feman4768@gmail.com" style="color: #7d5a5a;">feman4768@gmail.com</a>
</div>
