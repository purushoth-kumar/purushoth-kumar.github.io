---
layout: single
title: "About Me"
permalink: /about/
---

<!-- Hero Section -->
<section class="section section--hero" style="min-height: 60vh;">
  <div class="container">
    <div class="hero">
      <h1 class="hero__title">About Me</h1>
      <p class="hero__description">
        Senior Applied Data Scientist with 5+ years of experience transforming data into actionable insights
      </p>
    </div>
  </div>
</section>

<!-- About Content Section -->
<section class="section about-section">
  <div class="container">
    <div class="about-grid">
      <div class="about-content">
        <h2>R M Purushoth Kumar</h2>
        <h3 style="color: var(--accent-orange); margin-bottom: var(--space-lg);">Senior Applied Data Scientist</h3>
        
        <p>
          I'm a passionate data scientist with over 5 years of experience in Data Science & Analytics, 
          specializing in Causal Inference, Recommendation Systems, and Product Analytics. 
          My work focuses on delivering actionable insights through advanced analytics, A/B testing, and intuitive dashboards.
        </p>
        
        <p>
          Currently working at <strong>Games 24x7</strong> as a Senior Applied Data Scientist, 
        </p>
        
        <p>
          My expertise spans across machine learning, statistical analysis, and product analytics, 
          with a proven track record of driving business impact through data-driven decision making.
        </p>
        
        <div style="margin-top: var(--space-xl);">
          <h4 style="color: var(--primary-blue); margin-bottom: var(--space-md);">Key Areas of Expertise</h4>
          <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: var(--space-md);">
            <div class="card" style="padding: var(--space-md);">
              <h5 style="color: var(--accent-orange); margin-bottom: var(--space-sm);">Causal Inference</h5>
              <p style="font-size: 0.9rem; margin: 0;">Design and analyze experiments to measure causal effects</p>
            </div>
            <div class="card" style="padding: var(--space-md);">
              <h5 style="color: var(--accent-orange); margin-bottom: var(--space-sm);">Recommendation Systems</h5>
              <p style="font-size: 0.9rem; margin: 0;">Build contextual bandit algorithms and ML models</p>
            </div>
            <div class="card" style="padding: var(--space-md);">
              <h5 style="color: var(--accent-orange); margin-bottom: var(--space-sm);">Product Analytics</h5>
              <p style="font-size: 0.9rem; margin: 0;">Transform data into actionable business insights</p>
            </div>
          </div>
        </div>
      </div>
      
      <div class="contact-info">
        <h3>Get In Touch</h3>
        <ul>
          <li>
            <i class="fas fa-envelope" style="color: var(--accent-orange);"></i>
            <strong>Email:</strong> 
            <a href="mailto:purushoth.iitkgp@gmail.com">purushoth.iitkgp@gmail.com</a>
          </li>
          <li>
            <i class="fab fa-linkedin" style="color: var(--accent-orange);"></i>
            <strong>LinkedIn:</strong> 
            <a href="https://linkedin.com/in/purushothkumar" target="_blank">linkedin.com/in/purushothkumar</a>
          </li>
          <li>
            <i class="fab fa-github" style="color: var(--accent-orange);"></i>
            <strong>GitHub:</strong> 
            <a href="https://github.com/purushoth-kumar" target="_blank">github.com/purushoth-kumar</a>
          </li>
        </ul>
        
        <div style="margin-top: var(--space-xl); padding-top: var(--space-lg); border-top: 1px solid var(--border-color);">
          <h4 style="color: var(--primary-blue); margin-bottom: var(--space-md);">Download Resume</h4>
          <a href="/resume_purushoth.pdf" download class="btn btn--primary" style="width: 100%; text-align: center;">
            <i class="fas fa-download"></i>
            Download PDF Resume
          </a>
          <p style="font-size: 0.8rem; color: var(--text-light); margin-top: var(--space-sm); text-align: center;">
            {% assign resume = site.static_files | where: "path", "/resume_purushoth.pdf" | first %}
            {% if resume %}
              Updated on: {{ resume.modified_time | date: "%B %d, %Y" }}
            {% else %}
              (file not found)
            {% endif %}
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Experience Timeline Section -->
<section class="section">
  <div class="container">
    <div class="text-center mb-5">
      <h2>Professional Experience</h2>
      <p style="max-width: 600px; margin: 0 auto; color: var(--text-secondary);">
        My journey in data science and analytics
      </p>
    </div>
    
    <div style="max-width: 800px; margin: 0 auto;">
      <div class="card" style="margin-bottom: var(--space-lg);">
        <div class="card__subtitle">Games 24x7</div>
        <h3 class="card__title">Senior Applied Data Scientist</h3>
        <p style="color: var(--text-secondary); margin-bottom: var(--space-md);">April 2022 – Present</p>
        <div class="card__content">
          <ul style="color: var(--text-secondary); line-height: 1.7;">
            <li>Filler Text</li>
            <li>Filler Text</li>
          </ul>
        </div>
      </div>
      
      <div class="card">
        <div class="card__subtitle">Previous Experience</div>
        <h3 class="card__title">Data Science & Analytics</h3>
        <p style="color: var(--text-secondary); margin-bottom: var(--space-md);">5+ Years Total Experience</p>
        <div class="card__content">
          <p style="color: var(--text-secondary);">
            Proven track record in delivering actionable insights through advanced analytics, 
            A/B testing, and intuitive dashboards across multiple domains and industries.
          </p>
        </div>
      </div>
    </div>
  </div>
</section> 