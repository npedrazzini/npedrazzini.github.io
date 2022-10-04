---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<p><i> Updated on 02-12-2021</i></p>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
