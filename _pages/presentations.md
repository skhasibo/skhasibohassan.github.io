---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---

{% include base_path %}

Here you can find a list of my conference presentations, invited talks, and workshops.

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
