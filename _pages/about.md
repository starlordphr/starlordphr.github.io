---
layout: about
permalink: /
title: <strong>Prashant</strong> Rajput
description: Ph.D. Candidate | Computer Science | New York University | Nerd

profile:
  align: right
  image: profile.png
  address: >
    <p>pr1365@nyu.edu <a href="/assets/documents/prashant_resume.pdf">[Resume]</a></p>

news: true
social: true
years: [2021, 2020, 2019]
---

I'm a Ph.D. candidate in the Computer Science department at New York University, making this world a (cyber) secure place. As a part of the [MoMA Lab](https://wp.nyu.edu/momalab/), headed by [Prof. Michail Maniatakos](https://scholar.google.com/citations?user=aqQ_eLYAAAAJ&hl=en&authuser=1), my research focuses on embedded systems security and industrial control systems security. I extend the traditional malware detection and vulnerability patching approaches to less powerful ICS devices that bring unique challenges.

Before embarking on my Ph.D. journey, I was a part of the Bruin family at the University of California Los Angeles, where I completed my Master's Degree in Computer Science under the guidance of Prof. Rafail Ostrovsky.

If you have any questions or would like to collaborate, feel free to reach out through [email](mailto:pr1365@nyu.edu)!

<div class="post">

  {% if page.news %}
    {% include news.html %}
  {% endif %}

</div>

---

{: #publications}
## __Publications__

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
