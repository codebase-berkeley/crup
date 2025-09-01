---
layout: page
title: Staff
nav_order: 3
description: Meet the CRUP team and instructors.
---

<style>
/* Staff layout inspired by Data 100 fa25 */
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

.staffer-badge {
  display: inline-block;
  background-color: #f6f8fa;
  color: #0366d6;
  padding: 0.16em 0.56em;
  border-radius: 6px;
  font-size: 0.8em;
  font-weight: 500;
  margin-left: 0.5rem;
  text-transform: uppercase;
  border: 1px solid #e1e4e8;
}

.staffer-role {
  font-weight: 500;
  color: #0366d6;
  margin: 0.25rem 0;
  font-size: 1rem;
}

.staffer-meta {
  font-size: 0.9rem;
  color: #586069;
  margin: 0.25rem 0;
}

.staffer p {
  margin: 0.25rem 0;
  line-height: 1.5;
}

.staffer p a {
  color: #0366d6;
  text-decoration: none;
}

.staffer p a:hover {
  text-decoration: underline;
}

/* Role-specific styling */
.label-EdVP {
  background-color: #624099;
  color: white;
  border: none;
}

.label-Instructor {
  background-color: #5e1c82;
  color: white;
  border: none;
}

.label-TA {
  background-color: #935CBC;
  color: white;
  border: none;
}

.label-Mentor {
  background-color: #006C67;
  color: white;
  border: none;
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

# Staff

## Course Staff Email

{: .important }
> Contact course staff **via Ed** with any questions or concerns. For general inquiries, you can reach us at [crup@codebase.berkeley.edu](mailto:crup@codebase.berkeley.edu).

## Executive Vice Presidents (EdVPs)

<div class="role">
{% assign edvps = site.staffers | where: 'role', 'EdVP' %}
{% for staffer in edvps %}
{{ staffer }}
{% endfor %}
</div>

## Instructors

<div class="role">
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

## Teaching Assistants

<div class="role">
{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}
</div>

## Mentors

<div class="role">
{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
</div>
