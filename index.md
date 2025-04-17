---
layout: splash
title: "Ashutosh Ramola"
subtitle: "Engineer | Developer | Learner"
permalink: /
description: "Ashutosh Ramola's personal portfolio, resume, blog, and interests. Aerospace engineer, developer, and lifelong learner."
image: /images/profile.jpg
---

<div class="hero">
  <img src="/images/profile.jpg" alt="Ashutosh Ramola" class="profile">
  <h1>Ashutosh Ramola</h1>
  <p class="subtitle">Engineer | Developer | Learner</p>
  <a href="/cv/" class="btn-modern">Download Resume</a>
  <a href="mailto:ashutoshramola@email.com" class="btn-modern">Contact Me</a>
</div>

<div class="section">
  <div class="section-header">About Me</div>
  <div class="divider"></div>
  <p>I'm an Aerospace Engineer, Full Stack Developer, and lifelong learner. I love building things, solving problems, and sharing knowledge. Welcome to my online portfolio and blog!</p>
  <ul>
    <li><a href="/about/">About Me</a></li>
    <li><a href="/cv/">Resume / CV</a></li>
    <li><a href="/_portfolio/">Portfolio</a></li>
    <li><a href="/archive-layout-with-content/">Blog</a></li>
    <li><a href="/interests/">Interests</a></li>
    <li><a href="/#contact">Contact</a></li>
  </ul>
</div>

<div class="section">
  <div class="section-header">Featured Projects</div>
  <div class="divider"></div>
  <div class="card-list">
    {% for item in site.portfolio limit:3 %}
    <div class="card">
      <div class="card-title">{{ item.title }}</div>
      <div class="card-desc">{{ item.summary }}</div>
      <a href="{{ item.url }}" class="btn-modern">View Project</a>
    </div>
    {% endfor %}
  </div>
  <a href="/_portfolio/" class="btn-modern">View All Projects</a>
</div>

<div class="section" style="background:#fff;">
  <div class="section-header">Latest Blog Posts</div>
  <div class="divider"></div>
  <div class="card-list">
    {% for post in site.posts limit:3 %}
    <div class="card">
      <div class="card-title">{{ post.title }}</div>
      <div class="card-meta">{{ post.date | date: "%b %-d, %Y" }}</div>
      <div class="card-desc">{{ post.excerpt | strip_html | truncate: 120 }}</div>
      <a href="{{ post.url }}" class="btn-modern">Read More</a>
    </div>
    {% endfor %}
  </div>
  <a href="/archive-layout-with-content/" class="btn-modern">Read All Blog Posts</a>
</div>

<div class="section">
  <div class="section-header">Connect</div>
  <div class="divider"></div>
  <ul>
    <li><a href="https://github.com/ashutoshramola">GitHub</a></li>
    <li><a href="https://linkedin.com/in/ashutoshramola">LinkedIn</a></li>
    <li><a href="https://twitter.com/ashutoshramola">Twitter</a></li>
  </ul>
</div>

<div class="section">
  <div class="section-header">Contact</div>
  <div class="divider"></div>
  <p>Want to connect, collaborate, or just say hi? <a href="mailto:ashutoshramola@email.com">Email me</a> or reach out on <a href="https://linkedin.com/in/ashutoshramola">LinkedIn</a>.</p>
</div>

<div class="section" style="background:#fff;">
  <div class="section-header">Extras</div>
  <div class="divider"></div>
  <ul>
    <li><b>Testimonials:</b> <i>"Ashutosh is a brilliant engineer and a great team player!"</i> – Colleague</li>
    <li><b>Newsletter:</b> Coming soon! Stay tuned for updates on my work and blog.</li>
  </ul>
</div>

<!-- SEO & Analytics are handled via _includes/seo.html and analytics.html -->
