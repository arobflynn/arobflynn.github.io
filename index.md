---
layout: homepage
---

# About Me

I am a postdoctoral researcher with the [NBER](https://www.nber.org/) based at the [Wharton School](https://www.wharton.upenn.edu/) in Philadelphia, PA. My research sits at the intersection of innovation and organizational economics with a focus on digital user communities. I received my Ph.D. in Management from Boston University in 2026.

# Research

## Interests

<div class="interest-list">
  <span>user and innovation communities</span>
  <span>organizational design and structure</span>
  <span>open science</span>
  <span>distributed innovation</span>
  <span>digitization</span>
  <span>geopolitics and national innovation systems</span>
</div>

{% if site.data.publications.publications and site.data.publications.publications.size > 0 %}
## Publications

{% include_relative _includes/publications.html category="publications" %}
{% endif %}

{% if site.data.publications.working_papers and site.data.publications.working_papers.size > 0 %}
## Working Papers

{% include_relative _includes/publications.html category="working_papers" thumbnail_size="compact" %}
{% endif %}

{% if site.data.publications.work_in_progress and site.data.publications.work_in_progress.size > 0 %}
## Work in Progress

{% include_relative _includes/publications.html category="work_in_progress" thumbnails=false thumbnail_size="minimal" %}
{% endif %}
