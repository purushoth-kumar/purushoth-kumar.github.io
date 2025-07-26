---
layout: single
title: "Projects"
permalink: /projects/
---

<!-- Hero Section -->
<section class="section section--hero" style="min-height: 50vh;">
  <div class="container">
    <div class="hero">
      <h1 class="hero__title">Projects</h1>
      <p class="hero__description">
        A collection of my work in data science, machine learning, and analytics
      </p>
    </div>
  </div>
</section>

<!-- Projects Section -->
<section class="section">
  <div class="container">
    <div class="project-grid">
      {% for project in site.projects %}
      <article class="project-card">
        <div class="project-card__image">
          {% if project.image %}
            <img src="{{ project.image }}" alt="{{ project.title }}">
          {% else %}
            <div style="display: flex; align-items: center; justify-content: center; height: 100%; color: var(--text-light);">
              <i class="fas fa-chart-line" style="font-size: 3rem;"></i>
            </div>
          {% endif %}
        </div>
        <div class="project-card__content">
          <div class="project-card__company">{{ project.project.company }}</div>
          <h2 class="project-card__title">{{ project.title }}</h2>
          <p class="project-card__description">{{ project.excerpt }}</p>
          
          <div style="margin-bottom: var(--space-md);">
            <strong style="color: var(--text-primary);">Role:</strong> 
            <span style="color: var(--text-secondary);">{{ project.project.role }}</span>
          </div>
          
          <div style="margin-bottom: var(--space-lg);">
            <strong style="color: var(--text-primary);">Period:</strong> 
            <span style="color: var(--text-secondary);">{{ project.project.period }}</span>
          </div>
          
          <div class="project-card__skills">
            {% for skill in project.project.skills %}
              <span class="skill-tag">{{ skill }}</span>
            {% endfor %}
          </div>
          
          <div style="margin-top: var(--space-lg);">
            <a href="{{ project.url }}" class="btn btn--outline" style="width: 100%; text-align: center;">
              <i class="fas fa-arrow-right"></i>
              View Details
            </a>
          </div>
        </div>
      </article>
      {% endfor %}
    </div>
  </div>
</section>

<!-- CTA Section -->
<section class="section" style="background: var(--bg-secondary);">
  <div class="container">
    <div class="text-center">
      <h2>Interested in Working Together?</h2>
      <p style="max-width: 600px; margin: 0 auto 2rem auto; color: var(--text-secondary);">
        I'm always open to discussing new opportunities and collaborations. 
        Let's explore how we can work together on your next data science project.
      </p>
      <div style="display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;">
        <a href="mailto:purushoth.iitkgp@gmail.com" class="btn btn--primary">
          <i class="fas fa-envelope"></i>
          Get In Touch
        </a>
        <a href="/about/" class="btn btn--secondary">
          <i class="fas fa-user"></i>
          Learn More About Me
        </a>
      </div>
    </div>
  </div>
</section> 