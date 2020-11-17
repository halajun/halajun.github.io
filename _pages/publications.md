---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

More details can be seen by clicking figures on the left (or titles on the right).

{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

(\* equal contribution)&emsp;