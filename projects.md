---
layout: page
title: "Projects"
permalink: /projects/
---

<div style="text-align: center; padding: 2rem 0 1rem 0; background: linear-gradient(135deg, #14b8a6 0%, #5eead4 100%); color: #fff; border-radius: 1.5rem; margin-bottom: 2rem;">
  <h1 style="font-size: 2.5rem; font-weight: 800; margin-bottom: 0.5rem;">Projects</h1>
  <p style="font-size: 1.1rem; max-width: 700px; margin: 0 auto 1.5rem auto; line-height: 1.6; opacity: 0.95;">
    A collection of my work in data science, machine learning, and analytics.
  </p>
</div>

{% for project in site.projects %}
<div class="card" style="max-width: 700px; margin: 2rem auto;">
  <h2 style="color: #14b8a6; font-size: 1.5rem; font-weight: 700; margin-bottom: 0.5rem;">{{ project.title }}</h2>
  <div style="color: #64748b; font-size: 1rem; margin-bottom: 0.5rem;">
    <strong>Company:</strong> {{ project.project.company }} &nbsp; | &nbsp;
    <strong>Role:</strong> {{ project.project.role }} &nbsp; | &nbsp;
    <strong>Period:</strong> {{ project.project.period }}
  </div>
  <div style="margin-bottom: 0.5rem;">{{ project.excerpt }}</div>
  <div style="margin-bottom: 0.5rem;"><strong>Skills:</strong> {% for skill in project.project.skills %}<span style="background: #e0f7f4; color: #0f766e; border-radius: 0.5rem; padding: 0.2rem 0.7rem; margin-right: 0.4rem; font-size: 0.95rem;">{{ skill }}</span>{% endfor %}</div>
  <a href="{{ project.url }}" class="btn btn-secondary" style="margin-top: 0.5rem;">View Details</a>
</div>
{% endfor %}

<div style="text-align: center; margin: 3rem 0;">
  <a href="mailto:purushoth.iitkgp@gmail.com" class="btn btn-primary" style="min-width: 160px;">Get In Touch</a>
  <a href="/about/" class="btn btn-secondary" style="min-width: 160px;">Learn More About Me</a>
</div> 