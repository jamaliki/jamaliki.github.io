---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find a more up-to-date list on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
