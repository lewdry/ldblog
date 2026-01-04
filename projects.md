---
layout: page
title: Projects
description: A portfolio of digital tools and wood craft by Lewis Dryburgh, spanning Svelte development, data governance and woodworking.
---

I build tools that bridge the gap between complex information and human-centred design. This selection covers my work in **software development**, **data visualisation**, and **woodworking**.

<div class="projects-grid">
{% assign sorted_projects = site.projects | sort: "order" | reverse %}
{% for project in sorted_projects %}
  <article class="project-card">
    {% if project.image %}
      <img src="{{ project.image | relative_url }}" 
           alt="{{ project.title }}: {{ project.description }}" 
           class="project-image"
           loading="lazy">
    {% endif %}
    <h3>{{ project.title }}</h3>
    <p class="project-description">{{ project.description }}</p>
    
    {% if project.built_with %}
      <div class="project-tags" aria-label="Technologies used">
        {% for tag in project.built_with %}
          <span class="tag">{{ tag }}</span>
        {% endfor %}
      </div>
    {% endif %}

    {% if project.project_url %}
      <a href="{{ project.project_url }}" class="project-link" target="_blank" rel="noopener">
        Explore {{ project.title }} →
      </a>
    {% endif %}

    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "SoftwareApplication",
      "name": "{{ project.title }}",
      "description": "{{ project.description }}",
      "applicationCategory": "DeveloperApplication",
      "operatingSystem": "Web",
      "author": {
        "@type": "Person",
        "name": "Lewis Dryburgh"
      },
      "url": "{{ project.project_url }}",
      "image": "{{ project.image | absolute_url }}"
    }
    </script>
  </article>
{% endfor %}
</div>

---

### **Technical Toolkit**
I primarily work with:
* **Frontend:** Svelte, JavaScript (ES6+), D3.js
* **Backend & Data:** Python, SQL, RSS, NLP
* **Design & Workflow:** Human-Centred Design, Data Governance

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
  margin-bottom: 3rem;
}

.project-card {
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 1.5rem;
  background: #fff;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
}

.project-image {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 2px;
  margin-bottom: 1.2rem;
}

.project-card h3 {
  margin: 0 0 0.75rem 0;
  font-size: 1.3rem;
  color: #222;
}

.project-description {
  color: #444;
  font-size: 1rem;
  line-height: 1.5;
  margin: 0 0 1.2rem 0;
  flex-grow: 1;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
}

.tag {
  background: #f4f4f4;
  color: #555;
  padding: 0.25rem 0.75rem;
  border-radius: 0px;
  font-size: 0.8rem;
  font-weight: 500;
  border: 1px solid #e0e0e0;
}

.project-link {
  display: inline-block;
  color: #0070f3;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
}

.project-link:hover {
  text-decoration: underline;
}
</style>