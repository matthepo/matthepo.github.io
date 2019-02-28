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
<ul>
{% for post in site.publications reversed %}
  <li>{% include archive-single-publication.html %}<\li>
{% endfor %}
<\ul>
