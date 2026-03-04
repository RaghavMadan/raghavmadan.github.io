---
layout: single
title: "Research / Projects"
permalink: /research-projects/
author_profile: true
---

{% include base_path %}

Below are selected research projects and software I have developed or contributed to.

{% for project in site.data.projects %}
---
### {{ project.title }}
**{{ project.subtitle }}**

{% if project.image != nil and project.image != "" %}
<img src="{{ base_path }}/files/{{ project.image }}" alt="{{ project.title }}" style="max-width: 100%; height: auto; margin: 0.5em 0;" />
{% endif %}

{{ project.description }}

{% if project.repo_url != nil and project.repo_url != "" %}
**[GitHub repository]({{ project.repo_url }})**
{% endif %}

{% endfor %}
