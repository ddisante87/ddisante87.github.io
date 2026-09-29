---
layout: page
title: research
permalink: /projects/
description: Correlations, topology, and computation in quantum materials
nav: true
nav_order: 2
display_categories: [research]
horizontal: false
---

My research explores how electron interactions, crystal geometry, and topology give rise to new properties of quantum materials. I combine first-principles electronic structure calculations with many-body theory and machine learning, working closely with experimental collaborators to connect microscopic models with measurable phenomena.

The four directions below connect the development of computational methods with questions about kagome metals, topological materials, and unconventional superconductivity. Recent highlights include electronic nematicity and spin-orbital responses in kagome systems, the limits of topological edge-state protection, and neural-network representations of electronic interactions and density functionals.

For a broad introduction to one of these themes, see our review [*Kagome metals*, Reviews of Modern Physics **98**, 015002 (2026)](https://doi.org/10.1103/1g9n-wm38). A complete list of articles is available on the [publications page]({{ '/publications/' | relative_url }}).

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{% if category == "research" %}Research directions{% else %}{{ category }}{% endif %}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
