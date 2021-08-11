---
layout: archive
title: "Game-Theoretic (Inverse) Path Planning"
permalink: /Gametheory/
author_profile: false
---

The symbol * denotes equal contribution.

{% include base_path %}

{% for post in site.papers reversed %}
	{% if post.gametheory %}
	  {% include archive-single-abstract.html %}
	{% endif %}
{% endfor %}