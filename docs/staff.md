---
layout: home
title: Faciliators
nav_order: 3
description: Meet the CRUP team and instructors.
---

<style>
.role {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.staffer {
  display: flex;
  flex-basis: 90%;
  padding: 1rem;
  padding-right: 2rem;
  margin-bottom: 1rem;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  background-color: #ffffff;
  transition: box-shadow 0.2s ease;
}

.staffer:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.staffer-image {
  border-radius: 50%;
  height: 100px;
  width: 100px;
  margin-right: 1rem;
  object-fit: cover;
  flex-shrink: 0;
}

.staffer-name {
  margin: 0.25rem 0;
  font-size: 1.2rem;
  font-weight: 600;
  color: #24292e;
}

.staffer-name a {
  color: #0366d6;
  text-decoration: none;
}

.staffer-name a:hover {
  text-decoration: underline;
}

.staffer-role {
  font-weight: 500;
  color: #0366d6;
  margin: 0.25rem 0;
  font-size: 1rem;
}

.staffer p {
  margin: 0.25rem 0;
  line-height: 1.5;
}

/* Responsive design */
@media (max-width: 768px) {
  .staffer {
    flex-direction: column;
    text-align: center;
    padding: 1rem;
  }
  
  .staffer-image {
    margin-right: 0;
    margin-bottom: 1rem;
  }
  
  .role {
    flex-direction: column;
  }
  
  .staffer {
    flex-basis: 100%;
  }
}
</style>

# Faciliators

Running CRUP would not be possible without these amazing people!

<div class="role">
{% assign edvps = site.staffers | where: 'role', 'VP of Exec' %}
{% for staffer in edvps %}
{{ staffer }}
{% endfor %}
</div>

<div class="role">
{% assign instructors = site.staffers | where: 'role', 'Client PM' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

<div class="role">
{% assign tas = site.staffers | where: 'role', 'Mentored PM' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}
</div>

<div class="role">
{% assign mentors = site.staffers | where: 'role', 'Member' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
</div>