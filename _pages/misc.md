---
layout: archive
title: "Miscellaneous"
permalink: /Misc/
author_profile: false
---

The symbol * denotes equal contribution.

{% include base_path %}

{% for post in site.papers reversed %}
	{% if post.misc %}
	  {% include archive-single-abstract.html %}
	{% endif %}
{% endfor %}