---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find me on <u><a href="{{author.googlescholar}}">Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

<p><i> Updated on 9-7-2024</i></p>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
