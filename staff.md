---
layout: page
title: Staff
nav_order: 3
description: Meet the CRUP team and instructors.
---

<style>
.staffer {
  display: flex;
  margin-bottom: 2rem;
  padding: 1.5rem;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  background-color: #ffffff;
  transition: box-shadow 0.2s ease;
}

.staffer:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.staffer-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-right: 1.5rem;
  border: 3px solid #e1e4e8;
  flex-shrink: 0;
}

.staffer-name {
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.5rem;
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

.staffer-badge {
  display: inline-block;
  background-color: #0366d6;
  color: white;
  padding: 0.25rem 0.5rem;
  border-radius: 12px;
  font-size: 0.75rem;
  font-weight: 500;
  margin-left: 0.5rem;
}

.staffer-role {
  font-weight: 500;
  color: #0366d6;
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.staffer-meta {
  font-size: 0.9rem;
  color: #586069;
  margin-bottom: 0.5rem;
}

.staffer p {
  margin-bottom: 0.5rem;
}

.staffer p a {
  color: #0366d6;
  text-decoration: none;
}

.staffer p a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .staffer {
    flex-direction: column;
    text-align: center;
  }
  
  .staffer-image {
    margin-right: 0;
    margin-bottom: 1rem;
    width: 120px;
    height: 120px;
  }
}
</style>

# Staff

## Course Staff Email

{: .important }
> Contact course staff **via Ed** with any questions or concerns. For general inquiries, you can reach us at [crup@codebase.berkeley.edu](mailto:crup@codebase.berkeley.edu).

## Executive Vice Presidents (EdVPs)

{% assign edvps = site.staffers | where: 'role', 'EdVP' %}
{% for staffer in edvps %}
{{ staffer }}
{% endfor %}

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants

{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

## Mentors

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
