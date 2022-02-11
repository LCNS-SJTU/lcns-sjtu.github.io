---
layout: page
title: people
permalink: /people/
description:
nav: true
order: 1
display_categories: [Principal Investigator, PhD Candidate, Master's Student, Undergraduate, Visiting Scholar, Alumni]
header_background_image: assets/img/4.jpg
---

<!-- pages/people.md -->
<div class="people">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized people -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_people = site.people | where: "category", category -%}
  {%- assign sorted_people = categorized_people | sort: "year" %}
  <!-- Generate cards for each people -->
  <div class="row">
    {%- for people in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
  </div>
  {% endfor %}

{%- else -%}
<!-- Display people without categories -->
  {%- assign sorted_people = site.people | sort: "title" -%}
  <!-- Generate cards for each people -->
  <div class="row">
    {%- for people in sorted_people -%}
      {% include people.html %}
    {%- endfor %}
  </div>
{%- endif -%}
</div>
