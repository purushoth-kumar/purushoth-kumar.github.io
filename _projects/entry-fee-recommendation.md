---
layout: single
title: "Entry Fee Recommendation System"
date: 2023-01-01
excerpt: "Contextual Multi-Armed Bandit using XGBoost and SquareCB to improve user retention and revenue."
image: /assets/images/pic01.jpg
project:
  company: "Games 24x7"
  role: "Senior Applied Data Scientist"
  period: "Apr 2022 – Present"
  skills: [Python, XGBoost, Bandit Algorithms, Data Science, Causal Inference, A/B Testing]
---

<!-- Project Hero Section -->
<section class="section section--hero" style="min-height: 40vh;">
  <div class="container">
    <div class="hero">
      <div class="card__subtitle" style="text-align: center; margin-bottom: var(--space-md);">{{ page.project.company }}</div>
      <h1 class="hero__title">{{ page.title }}</h1>
      <p class="hero__description">{{ page.excerpt }}</p>
    </div>
  </div>
</section>

<!-- Project Details Section -->
<section class="section">
  <div class="container">
    <div style="max-width: 900px; margin: 0 auto;">
      
      <!-- Project Overview -->
      <div class="card" style="margin-bottom: var(--space-2xl);">
        <h2>Project Overview</h2>
        <p>
          Built a Contextual Multi-Armed Bandit system using XGBoost and SquareCB algorithms to optimize entry fee recommendations 
          for Games 24x7's gaming platform. The system dynamically adjusts recommendations based on user context and behavior patterns 
          to maximize user retention and revenue.
        </p>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: var(--space-lg); margin-top: var(--space-xl);">
          <div style="text-align: center;">
            <div style="font-size: 2rem; font-weight: 700; color: var(--accent-orange);">7%</div>
            <div style="color: var(--text-secondary);">MoM Retention Improvement</div>
          </div>
          <div style="text-align: center;">
            <div style="font-size: 2rem; font-weight: 700; color: var(--accent-orange);">1.2%</div>
            <div style="color: var(--text-secondary);">ARPU Lift</div>
          </div>
          <div style="text-align: center;">
            <div style="font-size: 2rem; font-weight: 700; color: var(--accent-orange);">24/7</div>
            <div style="color: var(--text-secondary);">Real-time Optimization</div>
          </div>
        </div>
      </div>
      
      <!-- Technical Approach -->
      <div class="card" style="margin-bottom: var(--space-2xl);">
        <h2>Technical Approach</h2>
        
        <h3>Multi-Armed Bandit Framework</h3>
        <p>
          Implemented a contextual bandit system that learns from user interactions in real-time. The system uses SquareCB 
          (Square Contextual Bandit) algorithm which provides theoretical guarantees for exploration-exploitation trade-offs.
        </p>
        
        <h3>XGBoost Integration</h3>
        <p>
          Leveraged XGBoost for feature engineering and context representation. The model processes user features including:
        </p>
        <ul style="color: var(--text-secondary); line-height: 1.7;">
          <li>User engagement metrics and historical behavior</li>
          <li>Game preferences and playing patterns</li>
          <li>Demographic and contextual information</li>
          <li>Real-time session data and interactions</li>
        </ul>
        
        <h3>Inverse Probability Weighting (IPW)</h3>
        <p>
          Applied IPW techniques to de-bias training data and handle selection bias in observational data. This ensures 
          that the model learns from unbiased samples and provides more accurate recommendations.
        </p>
      </div>
      
      <!-- Implementation Details -->
      <div class="card" style="margin-bottom: var(--space-2xl);">
        <h2>Implementation Details</h2>
        
        <h3>Data Pipeline</h3>
        <p>
          Built a robust data pipeline that processes real-time user interactions and feeds contextual information 
          to the recommendation engine. The pipeline includes data validation, feature engineering, and model serving components.
        </p>
        
        <h3>Model Architecture</h3>
        <p>
          The system architecture consists of:
        </p>
        <ul style="color: var(--text-secondary); line-height: 1.7;">
          <li><strong>Feature Engineering Layer:</strong> XGBoost-based feature extraction and transformation</li>
          <li><strong>Contextual Bandit:</strong> SquareCB algorithm for dynamic recommendation generation</li>
          <li><strong>Exploration Strategy:</strong> Epsilon-greedy with adaptive exploration rates</li>
          <li><strong>Feedback Loop:</strong> Real-time reward collection and model updates</li>
        </ul>
        
        <h3>Experimentation Framework</h3>
        <p>
          Designed comprehensive A/B testing framework to measure the impact of different recommendation strategies. 
          The framework includes statistical significance testing, multiple comparison corrections, and long-term effect analysis.
        </p>
      </div>
      
      <!-- Results & Impact -->
      <div class="card" style="margin-bottom: var(--space-2xl);">
        <h2>Results & Impact</h2>
        
        <h3>Key Metrics</h3>
        <ul style="color: var(--text-secondary); line-height: 1.7;">
          <li><strong>User Retention:</strong> 7% month-over-month improvement in user retention rates</li>
          <li><strong>Revenue Impact:</strong> 1.2% increase in Average Revenue Per User (ARPU)</li>
          <li><strong>Engagement:</strong> 15% improvement in user session duration</li>
          <li><strong>Conversion:</strong> 8% higher conversion rates for recommended entry fees</li>
        </ul>
        
        <h3>Business Impact</h3>
        <p>
          The recommendation system has become a critical component of Games 24x7's user experience optimization strategy. 
          It has contributed to significant improvements in user satisfaction, retention, and overall platform revenue.
        </p>
        
        <h3>Scalability</h3>
        <p>
          The system is designed to handle millions of daily recommendations with sub-second latency, 
          making it suitable for real-time gaming applications with high user concurrency.
        </p>
      </div>
      
      <!-- Skills & Technologies -->
      <div class="card">
        <h2>Skills & Technologies Used</h2>
        <div class="project-card__skills" style="margin-top: var(--space-lg);">
          {% for skill in page.project.skills %}
            <span class="skill-tag">{{ skill }}</span>
          {% endfor %}
        </div>
      </div>
      
    </div>
  </div>
</section>

<!-- CTA Section -->
<section class="section" style="background: var(--bg-secondary);">
  <div class="container">
    <div class="text-center">
      <h2>Interested in Similar Projects?</h2>
      <p style="max-width: 600px; margin: 0 auto 2rem auto; color: var(--text-secondary);">
        I'm passionate about building data-driven solutions that drive business impact. 
        Let's discuss how we can work together on your next project.
      </p>
      <div style="display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;">
        <a href="/projects/" class="btn btn--secondary">
          <i class="fas fa-arrow-left"></i>
          View All Projects
        </a>
        <a href="mailto:purushoth.iitkgp@gmail.com" class="btn btn--primary">
          <i class="fas fa-envelope"></i>
          Get In Touch
        </a>
      </div>
    </div>
  </div>
</section> 