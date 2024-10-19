---
layout: archive
title: "Writing Samples"
permalink: /writing-samples/
author_profile: true
---

{% include base_path %}

{% for post in site.writingsamples reversed %}
  {% include archive-single.html %}
{% endfor %}
