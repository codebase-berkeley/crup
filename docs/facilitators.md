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

.person {
  display: flex;
  flex-basis: 45%;
  padding: 0.75rem;
  margin-bottom: 0.75rem;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  background-color: #ffffff;
  transition: box-shadow 0.2s ease;
}

.person:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.person-image {
  border-radius: 50%;
  height: 60px;
  width: 60px;
  margin-right: 0.75rem;
  object-fit: contain;
  flex-shrink: 0;
}

.person-name {
  margin: 0.25rem 0;
  font-size: 1rem;
  font-weight: 600;
  color: #24292e;
}

.person-name a {
  color: #0366d6;
  text-decoration: none;
}

.person-name a:hover {
  text-decoration: underline;
}

.person-role {
  font-weight: 500;
  color: #0366d6;
  margin: 0.25rem 0;
  font-size: 0.9rem;
}

.person p {
  margin: 0.25rem 0;
  line-height: 1.4;
  font-size: 0.85rem;
}

/* Responsive design */
@media (max-width: 768px) {
  .person {
    flex-direction: column;
    text-align: center;
    padding: 0.75rem;
    flex-basis: 100%;
  }
  
  .person-image {
    margin-right: 0;
    margin-bottom: 0.5rem;
  }
  
  .role {
    flex-direction: column;
  }
}
</style>

# Faciliators

Running CRUP would not be possible without these amazing people!

<div class="role">
{% assign edvps = site.people | where: 'role', 'VP of Education' %}
{% for person in edvps %}
{{ person }}
{% endfor %}
</div>

<div class="role">
{% assign instructors = site.people | where: 'role', 'Client PM' %}
{% for person in instructors %}
{{ person }}
{% endfor %}
</div>

<div class="role">
{% assign tas = site.people | where: 'role', 'Mentored PM' %}
{% for person in tas %}
{{ person }}
{% endfor %}
</div>

<div class="role">
{% assign mentors = site.people | where: 'role', 'Member' %}
{% for person in mentors %}
{{ person }}
{% endfor %}
</div>