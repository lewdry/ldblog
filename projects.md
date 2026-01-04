---
layout: page
title: Projects
---

A selection of things I've built, tinkered with, or brought to life.

<div class="projects-grid">
{% assign sorted_projects = site.projects | sort: "order" | reverse %}
{% for project in sorted_projects %}
  <div class="project-card">
    {% if project.image %}
      <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" class="project-image">
    {% endif %}
    <h3>{{ project.title }}</h3>
    <p class="project-description">{{ project.description }}</p>
    {% if project.built_with %}
      <div class="project-tags">
        {% for tag in project.built_with %}
          <span class="tag">{{ tag }}</span>
        {% endfor %}
      </div>
    {% endif %}
    {% if project.data.url or project.url %}
      <a href="{{ project.data.url | default: project.url }}" class="project-link" target="_blank" rel="noopener">View Project →</a>
    {% endif %}
  </div>
{% endfor %}
</div>

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.project-card {
  border: 1px solid #e1e1e1;
  border-radius: 8px;
  padding: 1.25rem;
  background: #fff;
  transition: box-shadow 0.2s ease;
}

.project-card:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.project-image {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 4px;
  margin-bottom: 1rem;
}

.project-card h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.2rem;
}

.project-description {
  color: #555;
  font-size: 0.95rem;
  margin: 0 0 1rem 0;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-bottom: 1rem;
}

.tag {
  background: #f0f0f0;
  color: #333;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.8rem;
}

.project-link {
  display: inline-block;
  color: #0066cc;
  text-decoration: none;
  font-weight: 500;
}

.project-link:hover {
  text-decoration: underline;
}
</style>
