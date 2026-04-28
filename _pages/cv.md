---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Sociology, University of Cambridge, 2029 (expected)
* M.Phil. in Politics and International Studies, University of Cambridge, 2025 (merit)
* B.A. in International Relations, New York University, 2024 (summa cum laude)

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
### Books
<ul>
{% for post in site.publications %}
  {% if post.category == "books" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>

### Journal Articles
<ul>
{% for post in site.publications %}
  {% if post.category == "articles" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>

### Academic Theses
<ul>
{% for post in site.publications %}
  {% if post.category == "theses" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Volunteer service
======
* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
 
Awards and honours
======
* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
 
Memberships
======
* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
