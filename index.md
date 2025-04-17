---
layout: splash
title: "Ashutosh Ramola"
subtitle: "Engineer | Developer | Learner"
permalink: /
description: "Ashutosh Ramola's personal portfolio, resume, blog, and interests. Aerospace engineer, developer, and lifelong learner."
image: /images/profile.jpg
---

<img src="/images/profile.jpg" alt="Ashutosh Ramola" style="width:150px;border-radius:50%;margin-bottom:1em;">

# Hi, I'm Ashutosh Ramola

I'm an Aerospace Engineer, Full Stack Developer, and lifelong learner. I love building things, solving problems, and sharing knowledge. Welcome to my online portfolio and blog!

- [About Me](/about/)
- [Resume / CV](/cv/)
- [Portfolio](/_portfolio/)
- [Blog](/archive-layout-with-content/)
- [Interests](/interests/)
- [Contact](/#contact)

<div style="margin-top:2em">
  <a href="/cv/" class="btn">Download Resume</a>
  <a href="mailto:ashutoshramola@email.com" class="btn">Contact Me</a>
</div>

---

## Featured Projects

{% for item in site.portfolio limit:3 %}
- [{{ item.title }}]({{ item.url }})
  <br><span style="font-size:0.9em;color:#888;">{{ item.summary }}</span>
{% endfor %}

<a href="/_portfolio/" class="btn">View All Projects</a>

---

## Latest Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) <span style="font-size:0.9em;color:#888;">({{ post.date | date: "%b %-d, %Y" }})</span>
  <br><span style="font-size:0.9em;">{{ post.excerpt | strip_html | truncate: 120 }}</span>
{% endfor %}

<a href="/archive-layout-with-content/" class="btn">Read All Blog Posts</a>

---

## Connect

- [GitHub](https://github.com/ashutoshramola)
- [LinkedIn](https://linkedin.com/in/ashutoshramola)
- [Twitter](https://twitter.com/ashutoshramola)

---

## Contact

Want to connect, collaborate, or just say hi? [Email me](mailto:ashutoshramola@email.com) or reach out on [LinkedIn](https://linkedin.com/in/ashutoshramola).

---

## Extras

- <b>Testimonials:</b> <i>"Ashutosh is a brilliant engineer and a great team player!"</i> – Colleague
- <b>Newsletter:</b> Coming soon! Stay tuned for updates on my work and blog.

<!-- SEO & Analytics are handled via _includes/seo.html and analytics.html -->
