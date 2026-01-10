---
layout: page
title: papershelf
permalink: /papershelf/
description: Papers I am reading or finding interesting.
nav: true
topics: ["NLP", "Psychology"]
nav_order: 5
---

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% for topic in page.topics %}
  <h2 class="bibliography">{{ topic }}</h2>
  {% bibliography --file _papershelf/papers --query @*[topic={{topic}}] --group_by none %}
{% endfor %}

</div>
