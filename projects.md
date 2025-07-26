---
layout: single
title: "Projects"
permalink: /projects/
---

# Projects

A collection of my work in data science, machine learning, and analytics.

---

{% for project in site.projects %}
## {{ project.title }}

**Company:** {{ project.project.company }}  
**Role:** {{ project.project.role }}  
**Period:** {{ project.project.period }}

{{ project.excerpt }}

**Skills:**
{% for skill in project.project.skills %}
- {{ skill }}
{% endfor %}

[View Details]({{ project.url }})

---
{% endfor %}

## Interested in Working Together?

I'm always open to discussing new opportunities and collaborations. Let's explore how we can work together on your next data science project.

[Get In Touch](mailto:purushoth.iitkgp@gmail.com) &nbsp; | &nbsp; [Learn More About Me](/about/) 