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
* Library Invigilator (07/2025-present), Pembroke College (University of Cambridge)
* Admissions Observer (11/2025-12/2025), Pembroke College (University of Cambridge)
* Finance Fellow (05/2024-09/2024), George Whitesides for Congress
* Program Assistant (01/2023-05/2024), Deutsches Haus at NYU
* Research Assistant (09/2023-05/2024), Center for European and Mediterranean Studies at NYU
  
Skills
======
* English (C2)
* German (B2/C1)
* French (A2)
* Spanish (A2)
* Italian (A1)
* R programming platform
* LaTeX programming platform
* Microsoft Office suite
* iWork suite
* Google Workspace suite
* Canva suite
* CallTime.AI system
* Atlas.TI system

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
* LGBTQ+ Officer (12/2024-present), Pembroke College Graduate Parlour Committee
* Associate Editor (10/2024-12/2025), Cambridge Review of International Affairs
* Logistics Officer (12/2024-06/2025), Pembroke College May Ball Committee
* Contributor, Central and Eastern European Section (10/2023-04/2024), International Relations Insider
* Welcome Captain (09/2021-01/2024), New York University Centre for Student Life
* Director of Advocacy (09/2022-05/2023), Palladium Unified Government
 
Awards
======
* Cambridge Political Economy Society Trust
  * Date: February 2026
  * Title: Supplementary Doctoral Funding
  * Amount: GBP 5,000
 
Memberships
======
* Pembroke College (University of Cambridge), Lifetime Member
* University of Cambridge, Alumnus
* New York University, Alumnus
* New York University in Prague, Alumnus
* New York University in Berlin, Alumnus
* ΠΣΑ (ΒΗ Chapter), Lifetime Student Member
* ​ΦΒΚ Society (Β Chapter of New York), Lifetime Member
* Cambridge Union Society, Lifetime Member
* British Sociological Association, Member
* IMISCOE PhD Network, Member
* University and College Union, Member
